# Viagens a Dois

App de gastos de viagem do Sérgio e da Victoria: lançar cada compra com quem pagou, definir limite de gastos, ver o acerto de contas e os gastos por categoria de cada viagem.

- Página única (`index.html`), sem build.
- Dados no Supabase (projeto `viagens-a-dois`). As tabelas ficam fechadas e só são acessadas por funções que exigem o código do casal, que não fica neste repositório.
- Para instalar no celular: abra o link do casal no Safari ou Chrome e use "Adicionar à Tela de Início".

## Publicar uma mudança
Ao alterar o app, troque a constante `VERSAO` no `index.html` e o valor em `version.json` para o mesmo texto novo. O app aberto no celular compara os dois e recarrega sozinho com a versão nova, sem precisar refazer o atalho da tela de início.
