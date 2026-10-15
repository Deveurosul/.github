# Política de segurança

Vale para todo repositório da conta que não tenha um `SECURITY.md` próprio.

## Como reportar

Não abra issue pública sobre vulnerabilidade ou segredo exposto. Avise o mantenedor pelo e-mail
`dev@eurosul.com`, com o repositório, o arquivo ou a URL, e como reproduzir.

## Regras básicas

- **Segredo fora do código.** Token, senha, chave e string de conexão moram só no cofre da
  plataforma de deploy ou de CI, como variável protegida. Nunca em código, commit, issue, PR, chat
  ou arquivo versionado.
- **Modelo sem valor.** O repositório traz `.env.example` com os nomes das variáveis, sem valor, e o
  `.gitignore` barra `.env*` e arquivos de chave.
- **Menor privilégio.** Token fine-grained, só com as permissões e os repositórios necessários, só
  leitura quando bastar, e com data de validade.
- **Senha como hash.** Senha de aplicação fica guardada como hash com sal (scrypt, bcrypt ou
  argon2), nunca em texto puro.
- **Varredura no CI.** Todo PR roda uma varredura de segredos no histórico (gitleaks).
- **Vazou, troca.** Segredo exposto se revoga e se troca na hora. Apagar o commit não basta: o
  histórico e os clones guardam o valor.

## Projeto novo

Nasce do repositório template da conta, que já traz `.gitignore`, `.gitattributes`,
`.editorconfig`, `.env.example` e o CI com a varredura de segredos.
