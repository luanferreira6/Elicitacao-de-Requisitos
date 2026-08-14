
Acompanhar pedido
História de usuário:
Como usuário, quero acompanhar o status do meu pedido, para saber onde o pedido se encontra.
Critérios de aceitação:
- Dado que o usuário possui um pedido em andamento, quando acessar o acompanhamento do pedido, então o sistema deve apresentar o status atual do pedido.
- Dado que o pedido foi enviado pelo restaurante, quando o usuário consultar o pedido, então o sistema deve informar que o pedido está a caminho.
- Dado que o pedido foi entregue, quando o usuário consultar o acompanhamento, então o sistema deve informar que o pedido foi concluído.

Item indisponível
História de usuário:
Como restaurante, quero informar quando um item do cardápio estiver indisponível, para evitar que clientes façam pedidos de produtos que não estão em estoque.
Critérios de aceitação:
- Dado que um item está disponível no cardápio, quando o restaurante marcá-lo como indisponível, então o sistema deve atualizar seu status para : item indisponivel.
- Dado que um item está marcado como indisponível, quando um cliente visualizar o cardápio, então o sistema deve indicar que o item não está disponível para pedido.
- Dado que um item está indisponível, quando um cliente tentar adicioná-lo ao pedido, então o sistema não deve permitir sua inclusão.

Reportar problema durante a entrega
História de usuário:
Como entregador, quero reportar problemas durante uma entrega, para informar os responsáveis.
Critérios de aceitação:
- Dado que o entregador possui uma entrega em andamento, quando selecionar a opção de reportar problema, então o sistema deve permitir que ele informe o tipo do problema.
- Dado que o entregador informou um problema, quando confirmar o reporte, então o sistema deve registrar a ocorrência relacionada à entrega.
- Dado que o reporte foi registrado, quando a operação for concluída, então o sistema deve informar ao entregador que o problema foi enviado com sucesso.

 MoSCoW:
 Acompanhar pedido: Must Have 
 Informar item indisponível: Should Have
 Reportar problema durante a entrega: Could Have 
