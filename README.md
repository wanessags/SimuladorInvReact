## Etapa 7 — Lógica de cálculo

A função calculateInvestmentResults fica em src/util/investment.js,
separada dos componentes que exibem a interface.

Ela retorna um array com um objeto por ano de investimento.

No exemplo com investimento inicial de 1000, aporte anual de 100,
taxa de 10% e duração de 2 anos:

- Ano 1: juros de 100 e saldo final de 1200.
- Ano 2: juros de 120 e saldo final de 1420.

O aporte é adicionado ao fim de cada ano.

O formatter exibe os valores em USD, sem alterar o cálculo.
