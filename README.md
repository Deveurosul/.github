# .github

Arquivos padrão de comunidade da conta Deveurosul. Serve o template de Pull Request para todos os repositórios que não têm um próprio.

O GitHub usa os arquivos deste repositório como fallback para qualquer outro repositório da conta, inclusive os privados. Um repositório que tenha o próprio `.github/pull_request_template.md` continua usando o dele. Este repositório precisa ser público, exigência do GitHub para arquivos padrão.

## O que tem aqui

| Arquivo | Efeito |
|---|---|
| `.github/pull_request_template.md` | Preenche o corpo de toda PR nova que não tenha template local |

## O padrão

A estrutura do corpo e a regra do título (Conventional Commits) estão documentadas em `padroes/pull-request.md` do catálogo de soluções, que é a fonte de verdade. Alterou aqui, alinhe lá.

## Manutenção

Mudança neste arquivo vale para todas as PRs futuras da conta, então trate como mudança de processo: só mexa quando o padrão mudar de verdade, não para ajustar uma PR específica.
