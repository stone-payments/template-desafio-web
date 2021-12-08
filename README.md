# Desafio web

Seu desafio será construir uma aplicação de conversão de montante em DÓLAR para REAL. 

A aplicação terá duas etapas, inserir os valores e mostrar os valores retornados.

Primeira Etapa

- A aplicação deve mostrar a cotação do dia

    Para cotação você pode usar a API: [https://docs.awesomeapi.com.br/api-de-moedas](https://docs.awesomeapi.com.br/api-de-moedas)

    **Exemplo:**

    - Cotação do dia: `R$ 4,15`
- Deve-se ter um campo para digitar o valor desejado em dólar e a taxa do estado

    **Exemplo:** 

    - Digite o valor em Dólar: `US$ 1200.00`
    - Taxa do estado: `9,5%`
- Deve-se ter um __radio button__ para selecionar se a compra é em dinheiro ou cartão

2. Segunda Etapa

- A aplicação deve mostrar os seguintes dados
    1. Cotação do Dollar
    2. IOF
    3. Total em dólar sem imposto
    4. Total em dólar com imposto
    5. Total em real sem imposto
    6. Total em real com imposto

### Possíveis dúvidas:

- IOF é um imposto federal e tem com intuito ser um regulador da economia nacional.
    - **Exemplo: Em dinheiro é 1,1%, em cartão 6.4%**
- Taxa do estado é: Em EUA cada estado tem sua politica de cobrança de impostos
    - **Exemplo: Orlando: 6,5%, Las Vegas: 8,19%, Nova Iorque: 8,87%**
- Sobre as operações financeiras, é correto afirmar que:
    1. Comprando com dinheiro: [(Valor do produto em dólar) + (imposto do estado aonde esta comprando)] x (valor do dólar + IOF da compra de dólar)
        - **Exemplo: (USD$ 149,00 + 8,87%) * (R$ 4,15 + 1,10%)**
    2. Comprando com cartão: [(Valor do produto em dólar) + (imposto do estado aonde esta comprando) + (IOF de transações internacionais)] x (valor do dólar)
        - **Exemplo: [(USD$ 149 + 8,87%) * R$ 4,15] + 6,38%**

### Layout
O layout está disponível no [figma](https://www.figma.com/file/y8IcDbllfaFAzXrEXR05PE/Teste-Front-Web-Stone)


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
- O código foi entregue com um arquivo de __README__ claro de como instalar e codificar no projeto?
- O código possui comentários pertinentes?
- O código está em algum controle de versão?
- Os __commits__ são pequenos e consistentes?
- As mensagens de __commit__ são claras?

### Deploy
- Publique sua aplicação([now](https://zeit.co/)/[heroku](https://www.heroku.com)/[netlify](https://www.netlify.com)/outros)
- Publique seu código no seu perfil no GitHub em um **repositório privado**

### Outras informações
- Utilize **React**
- Utilize **TypeScript**
- Se possível utilize styled-components
- Se puder, crie um cliente HTTP com axios
- Utilize uma bilbioteca de cache como swr ou react-query

### **Material de Estudo**
- [Boas Práticas na Stone](https://github.com/stone-payments/stoneco-best-practices/blob/master/README_pt.md)
- [Airbnb Javascript](https://github.com/airbnb/javascript)

