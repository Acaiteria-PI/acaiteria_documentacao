# Pé de açai 

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

  Este projeto consiste em um sistema de autoatendimento para restaurantes, que integra a realização de pedidos dos clientes diretamente com a cozinha sistema permite que os clientes selecionem seus pedidos por meio de um terminal de autoatendimento, sendo identificados por nome e CPF. O pedido só é enviado para a cozinha após a confirmação do pagamento, garantindo que o preparo comece somente após a transação ser concluída. A cozinha tem a responsabilidade de gerenciar o estoque e de dar o comando de "pedido finalizado" quando o prato estiver pronto para ser servido. Além disso, o sistema mantém um histórico dos pedidos anteriores do cliente, facilitando futuras compras e o controle de pedidos realizados. O objetivo é otimizar a experiência do cliente e aumentar a eficiência no atendimento.

### IMPORTANTE: link do projeto (https://github.com/Acaiteria-PI)

Professor: Marco André Lopes Mendes (https://github.com/marrcandre)


Equipe:
- [Maria Helena de Oliveira Lotin] (https://github.com/lotinmaria)
- [João Vitor da Silva Sousa] (https://github.com/Jaotarzan)
- [Manoel Francisco de Jesus] (https://github.com/ManoelFranciscoDias) 

Links do Projeto:

- Backend: https://github.com/Acaiteria-PI/back-end.git
- Frontend: https://github.com/Acaiteria-PI/front-end.git


# 1 Desenvolvimento

## Ponto de Vendas (PDV) e Ordem de Serviço (O.S.)

 O sistema de autoatendimento para pedidos de açaí permitirá que os clientes realizem seus pedidos de forma autônoma por meio de um terminal ou plataforma digital. O cliente seleciona os ingredientes e complementos desejados, insere seu nome e CPF e finaliza com o pagamento. Somente após a confirmação do pagamento, o pedido será enviado automaticamente para a cozinha, onde será preparado. A equipe da cozinha terá acesso ao sistema para visualizar, gerenciar e concluir pedidos, além de poder adicionar, remover ou editar itens do cardápio. Quando o pedido estiver pronto, ele será marcado como "Concluído" e ficará registrado no histórico da loja para controle e futuras consultas. Esse sistema visa agilizar o atendimento, reduzir erros e melhorar a experiência do cliente, garantindo um processo eficiente e organizado. Após analisar o funcionamento do restaurante e os desafios enfrentados, identificamos que um sistema de autoatendimento poderia reduzir filas, agilizar pedidos, minimizar erros e aumentar a eficiência da cozinha. Além disso, o controle automatizado de estoque e o acompanhamento dos pedidos facilitariam a gestão do estabelecimento.


# 2 Situação Problema
   
### **Introdução**

O Pé de Açaí é uma empresa especializada na venda de combos de açaí, oferecendo produtos de alta qualidade e um atendimento diferenciado. Fundada há quatro anos por Marco, a empresa conquistou uma clientela fiel, crescendo de forma significativa. Atualmente, todas as operações da empresa são realizadas de forma manual, desde o preparo dos pedidos até a gestão financeira, controle de estoque e atendimento ao cliente. Os pedidos são anotados manualmente pelos atendentes, e o faturamento é contabilizado de forma tradicional, o que pode gerar inconsistências e dificuldades na organização.

### **Clientes**

O Pé de Açaí busca modernizar seu atendimento e proporcionar uma experiência mais prática e ágil para seus clientes. Para isso, será implementado um sistema de autoatendimento por meio de um tablet, onde os clientes poderão personalizar seus pedidos de forma intuitiva.

Ao utilizar o tablet, o cliente poderá adicionar ou remover ingredientes conforme sua preferência, montando o combo de açaí ideal. Após finalizar a escolha dos ingredientes, ele informará seu nome e CPF e concluirá o pedido com o pagamento direto na plataforma.

Com esse sistema, os pedidos serão enviados automaticamente para a cozinha, agilizando o preparo e reduzindo erros. Além disso, a nova tecnologia garantirá um processo mais eficiente, organizado e prático, melhorando a experiência tanto para os clientes quanto para a equipe do Pé de Açaí.
 
 ### **Gestão de estoque**

 Além da modernização do atendimento, o **Pé de Açaí** contará com um **sistema de gestão de estoque** para garantir um controle mais eficiente dos ingredientes e materiais utilizados no preparo dos pedidos.  

Com essa ferramenta, será possível **adicionar e remover ingredientes automaticamente** conforme os pedidos são realizados, evitando desperdícios e garantindo que os produtos estejam sempre disponíveis. Além disso, o sistema permitirá o **cadastro e acompanhamento de insumos essenciais**, como embalagens e utensílios, ajudando a manter a organização do estoque e a reposição no momento certo.  

Essa automação tornará a gestão mais precisa, evitando erros manuais, reduzindo perdas e garantindo que o Pé de Açaí continue oferecendo produtos de qualidade sem interrupções.

### **Histórico**

O sistema também contará com um **histórico de pedidos**, permitindo que tanto os clientes quanto a administração tenham acesso aos registros de compras anteriores. Isso facilitará a **repetição de pedidos** frequentes, agilizando o atendimento, além de possibilitar um melhor acompanhamento do consumo e preferências dos clientes. Para os administradores, o histórico será uma ferramenta valiosa para **análises de vendas**, ajudando na gestão do estoque e no planejamento de estratégias para otimizar o negócio.

### **Conclusão**

Atualmente, o **Pé de Açaí** enfrenta desafios na gestão de pedidos, controle de estoque e organização das vendas devido à falta de um sistema automatizado. O processo manual utilizado na loja pode resultar em erros na preparação dos pedidos, dificuldades no acompanhamento dos ingredientes disponíveis e lentidão no atendimento, especialmente em horários de pico.  

A implementação de um **sistema informatizado** permitirá otimizar esses processos, proporcionando um atendimento mais ágil e eficiente, reduzindo falhas operacionais e garantindo um controle mais preciso do estoque. Com essa solução, o **Pé de Açaí** poderá melhorar a experiência dos clientes, aumentar a produtividade da equipe e fortalecer sua gestão, garantindo um serviço mais organizado e confiável.
   
# 3 Proposta   


Para solucionar os desafios enfrentados pelo **Pé de Açaí**, será desenvolvido um sistema que automatiza o processo de pedidos, otimiza a gestão de estoque e melhora o controle operacional da empresa. O objetivo principal do software é agilizar o atendimento, reduzir erros na produção e oferecer maior controle sobre os insumos utilizados.  

O sistema contará com **níveis de acesso** diferenciados: os clientes poderão realizar seus pedidos diretamente em um tablet, personalizando os ingredientes e finalizando com nome, CPF e pagamento. Os funcionários terão acesso à interface de produção para acompanhar e preparar os pedidos com mais eficiência. Já a administração poderá gerenciar o estoque, acompanhar o fluxo de vendas e acessar relatórios para melhor tomada de decisão.  

Além disso, o sistema armazenará um **histórico de pedidos**, permitindo que os clientes repitam compras facilmente e possibilitando à empresa uma análise detalhada das vendas. A **gestão de estoque** será integrada, registrando automaticamente a entrada e saída de ingredientes, evitando desperdícios e garantindo um controle mais preciso dos insumos disponíveis.  

Com essa solução, o **Pé de Açaí** terá um atendimento mais rápido e organizado, um estoque bem gerenciado e um controle eficiente das operações, resultando em uma melhor experiência para os clientes e maior eficiência para o negócio.

# 4 Modelagem de Dados
![modelagem](./imagens/Imagem%20do%20WhatsApp%20de%202025-05-09%20à(s)%2016.16.40_778050db.jpg)

# 4. Regras de negócio

RN01 - Cadastro de produtos: Todo produto (açaí, complementos, embalagens) deve ser cadastrado com informações como nome, categoria, preço, unidade de medida e quantidade em estoque.

RN 02 - Atualização de estoque: Ao realizar uma venda ou registrar uma entrada de mercadoria, o sistema deve atualizar automaticamente o estoque correspondente.

RN 03 - Alerta de estoque mínimo: Quando a quantidade de um produto atingir o nível mínimo definido, o sistema deve gerar um alerta para reposição.

RN04 - Cadastro de cliente: Clientes podem ser cadastrados com informações como nome, telefone, e-mail e histórico de compras para facilitar futuras interações e promoções.

RN 05 - Registro de pedidos: Todos os pedidos devem ser registrados com detalhes do cliente, itens solicitados, quantidades, preços e forma de pagamento.

RN 06 - Integração com o caixa: Os pedidos finalizados devem ser automaticamente enviados para o módulo de caixa para processamento do pagamento.

RN 07 - Emissão de comprovante: Após o pagamento, o sistema deve emitir um comprovante detalhado da transação para o cliente

RN08 - Relatório gerenciais: O sistema deve gerar relatórios periódicos sobre vendas, estoque, fluxo de caixa e desempenho de produtos.

# 5. Requisitos funcionais

REQUISITOS FUNCIONAIS:	

R.F 01 - Cadastro de produtos: Permitir o cadastro de novos produtos com informações detalhadas.
- dados necessários: Nome, categoria, preço, unidade de medida, quantidade inicial.
- usuários: administrador e gerente.

R.F 02 - Cadastro de clientes: Permitir o cadastro de clientes para facilitar futuras vendas e  promoções.
- dados necessários: Nome, telefone, e-mail, data de nascimento.
- usuários: Atendente, Gerente.
	
R.F.03  –  Registro de Pedidos : Registrar pedidos realizados pelos clientes, associando-os aos  produtos e clientes correspondentes.
 - Dados Necessários: ID do cliente, lista de produtos, quantidades, forma de pagamento.
 - Usuários: Atendente

R.F 04 - Atualização automática de estoque: Reduzir automaticamente a quantidade em estoque dos produtos vendidos.

- Dados necessários: ID do produto, quantidade vendida.
- Usuários: Sistema (processo automático).

R.F 05 - Geração de relatórios: Gerar relatórios sobre vendas, estoque e desempenho de produtos.

- Dados necessários:  Período de análise, categorias de produtos, dados de vendas.
- usuários: Administrador, Gerente.

R.F F06 - Emissão de comprovante de venda: Emitir comprovantes detalhados das vendas    realizadas para os clientes.
					
- dados necessários: Detalhes do pedido, valores, forma de pagamento.
- usuários: Atendente, Cliente.

R.F 07 - Alerta de estoque mínimo: Notificar os responsáveis quando o estoque de um produto atingir o nível mínimo.

- Dados necessários: ID do produto, quantidade atual, quantidade mínima definida.
- Usuários: Administrador, Gerente.


# 6. Requisitos não funcionais

R.N.F. 01 - Banco de dados: O sistema será implementado com o banco de dados MySQL.

R.N.F. 02 - Navegador homologado: O sistema deverá ser homologado para os navegadores Google Chrome e Mozilla Firefox.

R.N.F. 03 - Implementação: O sistema deverá ser desenvolvido com linguagem Python, Javascript, e o framework vuejs

R.N.F. 04 - Ambiente de Desenvolvimento Integrado (IDE): Para criação do sistema, será utilizado o editor de texto Visual Studio Code.

R.N.F05 - Segurança: Implementar autenticação de usuários e controle de acesso baseado em permissões para proteger dados sensíveis.

R.N.F06 - Portabilidade: O sistema deve ser compatível com os principais navegadores e dispositivos, incluindo desktops, tablets e smartphones.


SISTEMA DE ORDEM DE SERVIÇO:

R.N.F. 01 - Navegadores homologados: o sistema deverá ser homologado para os navegadores Google Chrome e Mozilla Firefox.

R.N.F. 02 - Tecnologia Front-end: Para a exibição em front-end, o software utilizará o framework VueJS

R.N.F. 03- Tecnologia Back-end: O software será desenvolvido pela linguagem de programação Python, com o framework Django e a API REST com Django REST Framework.

R.N.F. 04 - Interoperabilidade: O banco de dados será o MySQL, com a linguagem SQL de banco, sendo todo produzido através do MySQL Workbench .


