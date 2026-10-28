<!-- Uma linha ou um parágrafo curto, em linguagem simples e sem negrito: o problema que se via e o que muda. Tudo em primeira pessoa ("corrigi", "testei"). -->

## Por que
<!-- O problema ou o motivo, com a evidência (print, erro, número). Issue resolvida inteira: `Closes #123`; parte: cite sem a palavra-chave. -->

## O que muda
<!-- Um item por arquivo ou mudança: o caminho e o que mudou nele, com o commit (SHA curto) quando ajudar. -->

## Como testar
<!-- Passos numerados, com o resultado esperado. Depois, a validação rodada (teste, typecheck, build, lint) com a saída resumida, e o que não foi conferido. -->

## Risco e rollback
<!-- O risco, o efeito colateral e como voltar (ex.: `git revert` do commit). Sem risco: "nenhum", com o motivo em meia linha. -->

## Decisões
<!-- Só se houver. Cada escolha com o motivo e a alternativa descartada. Sem decisão, apague a seção. -->

## Revisão
<!-- Só se houve revisão de código. Corrigido e Ignorado, cada item com o motivo. Sem revisão, apague a seção. -->

## Checklist
- [ ] Teste novo escrito antes do código e visto falhando, quando há lógica nova
- [ ] Teste, typecheck e build passando
- [ ] Sem segredo e sem travessão no diff; migration, se houver, commitada e imutável
- [ ] Teste na tela, por quem pediu
