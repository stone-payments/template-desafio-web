# Desafio web
O desafio é criar uma aplicação de conversão de valores de Dóllar para Real. 

A aplicação terá duas etapas, uma para inserir o valor que se deseja converter e outra para mostrar os valores convertidos.

Para isso você deve buscar a cotação na API [QUOTATION_API].

A aplicação deve mostrar os seguintes dados:

1. Cotação do Dollar
2. IOF
3. Total em dólar sem imposto
4. Total em dólar com imposto
5. Total em real sem imposto
6. Total em real com imposto

## Cálculo dos valores 

### Comprando com dinheiro 

`[(Valor do produto em dólar) + (imposto do estado aonde esta comprando)] x (valor do dólar + IOF da compra de dólar)`

### Comprando com cartão 

`[(Valor do produto em dólar) + (imposto do estado aonde esta comprando) + (IOF de transações internacionais)] x (valor do dólar)`


## Possíveis dúvidas:

- IOF é um imposto federal e tem com intuito ser um regulador da economia nacional. Em dinheiro seu valor é 1,1%, em cartão 6.4%
- Nos EUA cada estado tem sua politica de cobrança de impostos. Por exemplo, a de Orlando é 6,5%, a de Nevada é 8,19 e Nova Iorque 8,87


## Layout
O layout está disponível no [figma](https://www.figma.com/file/y8IcDbllfaFAzXrEXR05PE/Teste-Front-Web-Stone)

## Requisitos
- Utilize React
- Utilize TypeScript
- Crie um cliente HTTP com axios
- Faça testes unitários dos seus componentes
- Utilize uma bilbioteca de cache como swr ou react-query
- Utlize styled-components


## Critérios de avaliação 

### Entrega
- O resultado final está completo para ser executado?
- O resultado final atende ao que se propõe fazer?
- O resultado final atende totalmente aos requisitos propostos?
- O resultado final é visualmente elegante?

### Boas Práticas
- O código está de acordo com o guia de estilo da linguagem?
- O código está bem estruturado?
- O código faz o bom uso de *Design Patterns*?
- O código possui testes?

### Documentação
- O código foi entregue com um arquivo de _README_ claro de como instalar e codificar no projeto?
- O código possui comentários pertinentes?
- O código está em algum controle de versão?
- Os _commits_ são pequenos e consistentes?
- As mensagens de _commit_ são claras?

### Deploy
- Publique sua aplicação([now](https://zeit.co/)/[heroku](https://www.heroku.com)/[netlify](https://www.netlify.com)/outros)
- Publique seu código no seu perfil no GitHub em um **repositório privado**


### **Material de Estudo**
- [Boas Práticas na Stone](https://github.com/stone-payments/stoneco-best-practices/blob/master/README_pt.md)
- [Airbnb Javascript](https://github.com/airbnb/javascript)

[QUOTATION_API]: https://docs.awesomeapi.com.br/api-de-moedas

