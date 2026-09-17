# .github

Arquivos padrão de comunidade da conta Deveurosul. Serve o template de Pull Request para todos os repositórios que não têm um próprio.

O GitHub usa os arquivos deste repositório como fallback para qualquer outro repositório da conta, inclusive os privados. Um repositório que tenha o próprio `.github/pull_request_template.md` continua usando o dele. Este repositório precisa ser público, exigência do GitHub para arquivos padrão.

## O que tem aqui

| Arquivo | Efeito |
|---|---|
| `.github/pull_request_template.md` | Preenche o corpo de toda PR nova que não tenha template local |

## O padrão

A estrutura do corpo e a regra do título (Conventional Commits) seguem o padrão de Pull Request da
conta. A fonte de verdade fica no ferramental interno, e alterar aqui exige alinhar lá.

## O que nunca entra aqui

Este repositório é público, e o GitHub exige que seja público para os arquivos padrão valerem nos
outros repositórios, inclusive os privados. Portanto:

- Nada de nome de cliente em contexto interno, host interno, URL interna ou nome de repositório
  privado.
- Nada de credencial, token, identificador ou caminho de máquina.
- Nada de dado pessoal, perfil ou nota de processo.

Só conteúdo genérico: template, texto de processo e política de contribuição.

## Manutenção

Mudança neste arquivo vale para todas as PRs futuras da conta, então trate como mudança de processo: só mexa quando o padrão mudar de verdade, não para ajustar uma PR específica.
