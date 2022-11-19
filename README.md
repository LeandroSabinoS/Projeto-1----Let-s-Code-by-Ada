# Projetos---Let-s-Code-by-Ada

## Tabelas de amortização

Duas modalidades bastante comuns de financiamento são a tabela Price, estudada nos exercícios, e a tabela SAC.

Ao contrário da tabela Price, a SAC não possui valor fixo de prestação. Ao invés disso ela possui valor fixo de amortização. Ou seja, amortiza-se o mesmo valor todo mês.

Logo no início do cálculo podemos dividir o saldo devedor pelo número total de meses para obter o valor da amortização.

Em cada mês, iremos aplicar a taxa de juros ao saldo devedor da mesma maneira que na tabela Price para descobrir quanto pagaremos de juros naquele mês. Em seguida, podemos somar taxa de juros e amortização (que é constante) para obter o valor da prestação. O novo saldo devedor é obtido subtraindo o valor amortizado, como na tabela Price.

## Amortizações extraordinárias
Normalmente, quando fazemos um empréstimo (por qualquer uma das duas tabelas), fazemos 1 pagamento por período (geralmente por mês). Porém, é possível fazer o que chamamos de **amortização extraordinária**: se temos dinheiro sobrando, podemos fazer pagamentos adicionais fora do prazo. Há duas modalidades de amortização extraordinária: por redução de prazo e redução de valor da prestação.

### Amortização por redução de prazo
Quando optamos pela redução de prazo, são removidas linhas do final da tabela. Por exemplo, o valor a ser amortizado (ou seja, a parte sem juros) todo mês é 1000 reais e você antecipa 50 mil reais, são removidas as últimas 50 linhas da tabela (reduzimos em 50 meses o prazo para finalizar o empréstimo). Todos esses 50 mil são considerados como amortização, ou seja, reduzem o seu saldo devedor. Apesar do nome, você também deve recalcular o valor de todas as prestações posteriores à amortização extraordinária por redução de prazo, pois como o seu saldo devedor reduziu, os juros pagos em cada mês subsequente também será menor.

### Amortização por redução de valor da prestação
Neste modelo, o valor pago é considerado uma amortização, ou seja, será integralmente usado para reduzir o saldo devedor. Porém, não são removidas linhas da tabela: é mantido o prazo original do empréstimo. Assim, respeitando as peculiaridades de cada tabela (Price ou SAC), deve-se recalcular a partir daquele mês o valor de prestação ou de amortização para todos os meses subsequentes. Essa modalidade tende a reduzir mais o valor da parcela do que a outra, mas resulta em mais tempo com incidência de juros.
