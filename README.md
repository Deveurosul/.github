# .github

Arquivos padrão de comunidade da conta: template de Pull Request para todos os repositórios.

Repositório público que guarda os arquivos padrão da conta. O GitHub usa os arquivos deste repositório como fallback para os demais repositórios da conta que não têm os seus próprios.

## Security

Este repositório é público, então só entra conteúdo genérico: template, texto de processo e política de contribuição. Nada de nome de cliente, host ou URL interna, nome de repositório privado, credencial, caminho de máquina ou dado pessoal.

## Background

O GitHub exige que este repositório seja público para que os arquivos padrão valham também nos repositórios privados da conta. A estrutura do corpo de PR e a regra do título (Conventional Commits) seguem o padrão de Pull Request da conta. A fonte de verdade fica no ferramental interno, e alterar aqui exige alinhar lá.

## Usage

Não há comando. Os arquivos deste repositório valem automaticamente:

- o `.github/pull_request_template.md` preenche o corpo de toda PR nova em repositório da conta que não tem template próprio;
- repositório com `.github/pull_request_template.md` próprio continua usando o dele.

| Arquivo | Efeito |
|---|---|
| `.github/pull_request_template.md` | preenche o corpo de toda PR nova que não tenha template local |

## Maintainers

[@Deveurosul](https://github.com/Deveurosul)

## Contributing

Mudança neste repositório vale para todas as PRs futuras da conta, então trate como mudança de processo: só mexa quando o padrão mudar de verdade, não para ajustar uma PR específica. Abra PR com título em Conventional Commits, em português.

## License

Software proprietário. Uso interno da Eurosul, todos os direitos reservados.
