
Processo 1: Registro de Pedidos (Vendedores)

Requisito 1.1: O sistema deve permitir a busca rápida de produtos pelo nome ou código de referência durante o atendimento.
  Fonte 1: Observação da rotina de vendas por telefone (shadowing). Fonte humana, nível operacional, classe de usuário: vendedor   
  Fonte 2: Análise de sistemas de concorrentes de venda direta (como Avon ou Natura). Fonte não humana, categoria: concorrência.

Requisito 1.2: O sistema deve funcionar em modo offline (sem internet) no celular, sincronizando os pedidos assim que a conexão for restabelecida (crucial para vendas presenciais).
Fonte 1: Entrevista com a gerência comercial sobre os desafios das vendas de porta em porta. Fonte humana, nível tático.
Fonte 2: Relatórios atuais de vendas perdidas ou atrasadas por falta de sinal no caderno de pedidos. Fonte não humana, categoria: documentação.

Requisito 1.3: O sistema deve registrar o endereço de entrega do cliente no momento do fechamento do pedido, validando o formato do CEP.
   Fonte 1: Bate-papo com a equipe de logística sobre os erros mais comuns nas entregas atuais. Fonte humana, nível tático (ou operacional, dependendo do entrevistado).
   Fonte 2: Consulta à base de dados dos Correios sobre padronização de CEPs. *Fonte não humana, categoria: norma/padronização externa.

 Processo 2: Gestão de Produtos (Administrador)

Requisito 2.1: O sistema deve permitir o cadastro de novos produtos, incluindo campos obrigatórios para nome, descrição, código SKU e preço de venda.
  Fonte 1: Reunião com o diretor de operações sobre as informações essenciais para lançar um produto. Fonte humana, nível estratégico.
  Fonte 2: Planilha atual do Excel onde o catálogo de produtos é mantido hoje. Fonte não humana, categoria: sistema legado (ou documentação).

Requisito 2.2: O sistema deve permitir a inativação de um produto (remover da vitrine de vendas), mas mantendo seu histórico para consultas de vendas passadas (nunca excluir definitivamente).
Fonte 1: Conversa com o administrador atual do sistema sobre o histórico de auditoria. Fonte humana, nível operacional, classe de usuário: administrador.
Fonte 2: Legislação sobre guarda de documentos fiscais e histórico de transações. Fonte não humana, categoria: norma (legal).

Requisito 2.3: O sistema deve aceitar o upload de pelo menos uma imagem para cada produto cadastrado.
Fonte 1: Solicitação do time de marketing para melhorar o material de apoio dos vendedores presenciais. Fonte humana, nível tático.
Fonte 2: Análise do catálogo impresso atual usado pelos vendedores. Fonte não humana, categoria: documentação.

Processo 3: Controle de Quantidade (Estoque)

Requisito 3.1: O sistema deve dar baixa automática na quantidade disponível de um produto assim que um pedido de venda for confirmado pelo vendedor.
Fonte 1: Entrevista com o estoquista sobre o fluxo ideal de separação de mercadoria. Fonte humana, nível operacional, classe de usuário: equipe de estoque.
Fonte 2: Manuais de boas práticas de gestão de armazéns (WMS). Fonte não humana, categoria: documentação/literatura técnica.

Requisito 3.2: O sistema deve permitir o registro manual de entrada de produtos (notas fiscais de compra), atualizando o saldo em estoque.
Fonte 1:Acompanhamento do processo de recebimento de mercadorias no galpão. Fonte humana, nível operacional, classe de usuário: equipe de estoque.
Fonte 2: Verificação das notas fiscais de fornecedores recebidas na última semana. Fonte não humana, categoria: documentação.

Requisito 3.3: O sistema deve gerar um alerta visual (ou relatório) para produtos cujo estoque atinja a quantidade mínima de segurança definida pelo administrador.
Fonte 1:Reunião com o gerente de compras sobre os critérios de reposição. Fonte humana, nível tático.
Fonte 2:Sistema ERP/planilha de compras antiga que já possuía uma lógica de "ponto de pedido". *Fonte não humana, categoria: sistema legado.
