# História de Usuário — Controle de Entrada e Saída de Mercadorias

## Contexto

O Sr. Jerônimo é responsável pelo gerenciamento de uma **boca de fumo** e necessita de um sistema para controlar a entrada e a saída das mercadorias comercializadas no estabelecimento.

Para garantir maior controle e segurança das informações, somente o Sr. Jerônimo poderá realizar o registro de entrada de mercadorias e gerar relatórios referentes às vendas realizadas.

## História de Usuário

**Como** Sr. Jerônimo, responsável pelo estabelecimento,
**quero** gerenciar a entrada e a saída das mercadorias,
**para** ter controle sobre o estoque e acompanhar tudo o que foi vendido.

## Regras de Negócio

* Somente o **Sr. Jerônimo** poderá registrar a entrada de mercadorias no sistema.
* O sistema deverá registrar a quantidade e a descrição das mercadorias recebidas.
* As saídas deverão ser registradas conforme as mercadorias forem vendidas.
* O estoque deverá ser atualizado após cada saída registrada.
* Somente o **Sr. Jerônimo** poderá gerar relatórios das mercadorias vendidas.
* Os relatórios deverão permitir visualizar as informações das vendas realizadas.
* As informações deverão permanecer registradas para consulta posterior.

## Critérios de Aceitação

### Entrada de mercadorias

* [ ] O sistema deve permitir que o Sr. Jerônimo registre a entrada de uma mercadoria.
* [ ] Usuários que não sejam o Sr. Jerônimo não devem possuir permissão para registrar entradas.
* [ ] A quantidade disponível em estoque deve ser atualizada após uma entrada.

### Saída de mercadorias

* [ ] O sistema deve registrar a saída de mercadorias.
* [ ] A quantidade em estoque deve ser reduzida após uma venda.
* [ ] O sistema não deve permitir uma saída superior à quantidade disponível em estoque.

### Relatórios

* [ ] Somente o Sr. Jerônimo poderá acessar a área de relatórios.
* [ ] O relatório deve apresentar as mercadorias vendidas.
* [ ] O relatório deve apresentar as respectivas quantidades.
* [ ] O relatório deve permitir consultar o histórico das vendas.

## Objetivo

Desenvolver um sistema simples e seguro para que o Sr. Jerônimo tenha **controle sobre o estoque, as entradas, as saídas e o histórico de vendas** do estabelecimento.
# sr_jeronimo