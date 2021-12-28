# Avalição

Avaliador: <%= props.evaluator %>

## Entrega

- O resultado final está completo para ser executado?
  <%= props.delivery[0] %>
- O resultado final atende ao que se propõe fazer?
  <%= props.delivery[1] %>
- O resultado final atende totalmente aos requisitos propostos?
  <%= props.delivery[2] %>
- O resultado final é visualmente elegante?
  <%= props.delivery[3] %>

## Boas práticas

- O código está de acordo com o guia de estilo da linguagem?
  <%= props.bestPractices[0] %>
- O código está bem estruturado?
  <%= props.bestPractices[1] %>
- O código faz o bom uso de Design Patterns?
  <%= props.bestPractices[2] %>
- O código possui testes?
  <%= props.bestPractices[3] %>

## Documentação

- O código foi entregue com um arquivo de README claro de como instalar e codificar no projeto?
  <%= props.documentation[0] %>

- O código possui comentários pertinentes?
  <%= props.documentation[1] %>

- O código está em algum controle de versão?
  <%= props.documentation[2] %>

- Os commits são pequenos e consistentes?
  <%= props.documentation[3] %>

- As mensagens de commit são claras?
  <%= props.documentation[4] %>

## Outras observações

<%= props.aditionalInfo %>
