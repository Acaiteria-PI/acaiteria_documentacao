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
![modelagem](./imagens/WhatsApp%20Image%202025-04-04%20at%2008.07.58.jpeg)

