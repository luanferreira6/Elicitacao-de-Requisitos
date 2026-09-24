1. Empatia
Por que eu continuo jogando comida fora quase toda semana porque acabo esquecendo os alimentos no fundo da geladeira até passarem da data de validade?

2. Definição
O desperdício de alimentos na minha rotina não acontece por falta de preocupação ou desorganização consciente, mas sim porque os produtos ficam fora da minha linha de visão diária e não existe um alerta ativo no momento certo em que estou planejando as refeições.

3. Ideação
Notificação diária inteligente (Push): Um alerta no celular avisando sobre os itens que vão vencer nos próximos 3 dias, trazendo uma sugestão rápida de uso do ingrediente.

Widget na tela inicial: Um painel visual organizando os alimentos em categorias de urgência (Vermelho: vence em até 48h; Amarelo: vence na semana; Verde: validade ok).

Escaneamento de Nota Fiscal: Funcionalidade de leitura do QR Code da nota do supermercado para cadastrar automaticamente a data estimada de validade dos itens consumíveis sem digitação manual.

4. Escolha
Notificação diária inteligente (Push) com aviso prévio de vencimento.

5. Histórias de Usuário
História 1:

Como pessoa que cozinha em casa,

Quero receber uma notificação push no celular avisando quando um alimento estiver a 3 dias do vencimento,

Para que eu possa incluí-lo na minha próxima refeição e evitar jogá-lo fora.

História 2:

Como usuário do aplicativo,

Quero configurar o horário diário em que recebo as notificações de vencimento (por exemplo, às 18h),

Para receber os alertas no momento exato em que estou decidindo o que preparar para o jantar.

História 3:

Como usuário que busca praticidade,

Quero poder marcar um alimento como "consumido" diretamente pela notificação,

Para manter minha lista atualizada rapidamente sem precisar abrir o aplicativo.

6. Critérios de Aceitação
Critério 1:

Dado que um alimento cadastrado está a exatamente 3 dias da data de vencimento,

Quando o sistema executar a verificação diária no horário configurado pelo usuário,

Então uma notificação push deve ser enviada informando o nome do produto, a quantidade e a data limite de consumo.

Critério 2:

Dado que o usuário recebeu a notificação de um produto prestes a vencer,

Quando ele tocar na ação "Marcar como consumido" presente na própria notificação,

Então o sistema deve remover o item da lista de pendências e atualizar o status sem abrir a tela principal do app.

Critério 3:

Dado que o usuário não possui nenhum alimento cadastrado com vencimento nos próximos 3 dias,

Quando o sistema realizar a checagem diária automática,

Então nenhuma notificação push deve ser disparada.
