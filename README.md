## Como executar

Com Node.js compatível com o Vite 8 instalado, execute na pasta do projeto:

```bash
npm install
npm run dev
```

Abra no navegador o endereço indicado pelo terminal.

## Compilação para produção

```bash
npm run build
```

Os arquivos de produção são gerados na pasta dist.

## Funcionamento

O simulador recebe investimento inicial, aporte anual, taxa de retorno
e duração. A tabela atualiza automaticamente os resultados de cada ano,
exibindo saldo, juros anuais, juros acumulados e capital investido em USD.

Duração inferior a 1 oculta a tabela e exibe uma orientação.

## Validação

- Campos iniciais: 10000, 1200, 6 e 10.
- Quantidade de linhas acompanha a duração.
- Alterações nos campos atualizam os resultados.
- Duração zero oculta a tabela; duração válida restaura os resultados.
- Cenário 1000 / 100 / 10 / 2: saldos de $1,200 e $1,420.
- Console sem erros ou avisos de key.
- Compilação com Vite 8.3.0 concluída com sucesso.
