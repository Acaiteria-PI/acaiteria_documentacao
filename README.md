Pé de açai 

Um modelo para o desenvolvimento do Projeto Integrador do Curso de Técnico em Desenvolvimento de Sistemas para a Internet Integrado ao Ensino Médio do IFC - Campus Araquari.

  Este projeto consiste em um sistema de autoatendimento para restaurantes, que integra a realização de pedidos dos clientes diretamente com a cozinha sistema permite que os clientes selecionem seus pedidos por meio de um terminal de autoatendimento, sendo identificados por nome e CPF. O pedido só é enviado para a cozinha após a confirmação do pagamento, garantindo que o preparo comece somente após a transação ser concluída. A cozinha tem a responsabilidade de gerenciar o estoque e de dar o comando de "pedido finalizado" quando o prato estiver pronto para ser servido. Além disso, o sistema mantém um histórico dos pedidos anteriores do cliente, facilitando futuras compras e o controle de pedidos realizados. O objetivo é otimizar a experiência do cliente e aumentar a eficiência no atendimento.

IMPORTANTE: link do projeto

Professor: Marco André Lopes Mendes


Equipe:
- Maria Helena de Oliveira Lotin (https://github.com/lotinmaria)
- João Vitor da Silva Sousa (https://github.com/Jaotarzan)
- Manoel Francisco de Jesus (https://github.com/ManoelFranciscoDias) 

Links do Projeto:

Backend: https://github.com/Acaiteria-PI/back-end.git
Frontend: https://github.com/Acaiteria-PI/front-end.git


1. Desenvolvimento

Ponto de Vendas (PDV) e Ordem de Serviço (O.S.)

 O sistema de autoatendimento para pedidos de açaí permitirá que os clientes realizem seus pedidos de forma autônoma por meio de um terminal ou plataforma digital. O cliente seleciona os ingredientes e complementos desejados, insere seu nome e CPF e finaliza com o pagamento. Somente após a confirmação do pagamento, o pedido será enviado automaticamente para a cozinha, onde será preparado. A equipe da cozinha terá acesso ao sistema para visualizar, gerenciar e concluir pedidos, além de poder adicionar, remover ou editar itens do cardápio. Quando o pedido estiver pronto, ele será marcado como "Concluído" e ficará registrado no histórico da loja para controle e futuras consultas. Esse sistema visa agilizar o atendimento, reduzir erros e melhorar a experiência do cliente, garantindo um processo eficiente e organizado. Após analisar o funcionamento do restaurante e os desafios enfrentados, identificamos que um sistema de autoatendimento poderia reduzir filas, agilizar pedidos, minimizar erros e aumentar a eficiência da cozinha. Além disso, o controle automatizado de estoque e o acompanhamento dos pedidos facilitariam a gestão do estabelecimento.


1. Situação Problema
   
Introdução
O Pé de Açaí é uma pequena empresa especializada na venda de açaí e outros produtos naturais. Fundada há três anos por João Ferreira, a empresa cresceu rapidamente devido à qualidade dos seus produtos e ao atendimento personalizado. Atualmente, a loja conta com quatro funcionários: João, que administra o negócio, dois atendentes responsáveis pelo caixa e atendimento ao cliente, e um funcionário na cozinha que prepara os pedidos.

O estabelecimento possui um alto fluxo de clientes, especialmente nos finais de semana e horários de pico, o que pode gerar filas e aumentar o tempo de espera. Com a crescente demanda, João percebeu a necessidade de otimizar o atendimento para evitar congestionamentos e melhorar a experiência dos clientes.

Situação Atual e Problema Identificado
Atualmente, os clientes chegam ao Pé de Açaí e fazem seus pedidos diretamente no balcão, informando os ingredientes e complementos desejados para o preparo do açaí. O atendente anota o pedido manualmente, recebe o pagamento e encaminha a solicitação para a cozinha. O funcionário responsável então prepara o pedido e chama o cliente pelo nome quando está pronto.

Esse processo, embora funcional, apresenta diversas dificuldades:

Filas e demora no atendimento: Durante os horários de pico, os atendentes ficam sobrecarregados, gerando lentidão no atendimento e insatisfação dos clientes.

Erros na anotação dos pedidos: Como o pedido é anotado manualmente, há chances de erros na escolha dos ingredientes ou na digitação, resultando em desperdício e retrabalho.

Falta de um controle eficiente do estoque: Como não há um sistema integrado, os funcionários não sabem com precisão quais ingredientes estão disponíveis, podendo ocorrer a venda de produtos em falta.

Dificuldade na organização dos pedidos: Não há um método eficaz para acompanhar os pedidos em andamento, e muitas vezes clientes aguardam sem saber se seu pedido já está pronto.

Conclusão e Solução Proposta
Para solucionar esses problemas, identificamos que um sistema de autoatendimento pode trazer diversos benefícios ao Pé de Açaí. Com ele, os clientes poderão realizar seus pedidos de forma autônoma em um terminal ou plataforma digital, escolhendo os ingredientes desejados e finalizando com o pagamento. Isso reduzirá filas, minimizará erros e permitirá que a cozinha receba os pedidos automaticamente, agilizando a produção.

Além disso, a cozinha poderá gerenciar o estoque em tempo real, evitando a venda de produtos indisponíveis, e acompanhar os pedidos de forma organizada. Com a conclusão do pedido, ele será registrado no histórico da loja para futuras análises.

Esse sistema visa otimizar o atendimento, melhorar a experiência do cliente e tornar a gestão do negócio mais eficiente, garantindo um serviço mais rápido e preciso.
   
   
   Descrição da proposta
Após entender o problema, proponha uma solução que será útil nos aspectos de dificuldade encontrados. Assim, aqui você deverá explicar de maneira resumida, e preferencialmente mais textual, como o software funcionará. Pense nesse texto como uma introdução ao seu cliente do que você pretende fazer por ele, para que ele confirme se realmente está dentro do desejado e permita sua continuidade.

Alguns pontos importantes a se destacar são:

Qual o foco de ação do software relacionado com os problemas levantados na análise da situação-problema. O que realmente o software vai fazer. Por exemplo, o foco de ação do Gmail é permitir o envio e recebimento de e-mails.
Os níveis de usuário do sistema. Somente o gestor tem acesso? E os funcionários? Talvez seja para ambos, ou para funcionários de cargos diferentes, etc.
O que poderá ser feito no software.Apenas o principal, sem pensar em telas ou detalhes específicos, pois isso será feito em outro momento.
Se houver mais de um nível de usuário, ressaltar as diferenças entre eles na descrição da proposta.
Tenha em mente que essa é uma etapa relativamente breve. Não é necessário um texto gigantesco, apenas dar uma noção do funcionamento do sistema. Mais adiante precisaremos ser bem detalhistas, todavia agora a intenção é apenas fazer algo que permita ao cliente nos dizer se estamos no caminho certo.

1. Modelagem de Dados
(Nessa parte a equipe deve descrever a modelagem de dados que será implementada no sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.)

Defina as entidades e relacionamentos que farão parte do sistema. Desenhe o diagrama de entidade-relacionamento (DER) e descreva as entidades e relacionamentos que farão parte do sistema.

4. Regras de negócio
(Nessa parte a equipe deve descrever as regras de negócio que serão implementadas no sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.)

As Regras de negócio são orientações e restrições que ajudam a regular as operações de uma empresa. Regras foram criadas para colaborar com o funcionamento, seja da sociedade, de uma escola, de um jogo, etc. Não seria diferente nas organizações. Vamos abordar melhor sobre esse assunto. Entender o que são as regras de negócio, sua importância, como são aplicadas e automatizadas na gestão por processo.

4.1 O que são regras de negócio?

Um negócio funciona por processos que, por sua vez, são formados por atividades relacionadas entre si.

As funções das áreas de compras, estoque, logística, finanças, vendas e marketing, por exemplo, compõem um processo de fornecimento de um produto ao cliente.

Dentro desses processos, existem regras que devem ser seguidas durante a execução das atividades, que ajudam a definir COMO as operações devem ser realizadas e gerenciadas, POR QUEM, QUANDO, ONDE e POR QUÊ.

Podemos dizer que as regras de negócio são limites impostos às operações, de forma que elas sigam corretamente em direção às políticas e aos objetivos da instituição.

4.2 Regras para a criação de regras de negócio

De maneira geral, as regras de negócio devem:

Ser simples, isto é, ter apenas uma função.
Ser completas, com início, meio e fim.
Ser possíveis de mensurar e rastrear.
Estar em consonância com a legislação.
Estar atualizadas e sempre revisadas.
Refletir a política e os valores da organização.
Ser inteligíveis para os colaboradores e envolvidos no processo.
4.3 Por que ter regras de negócio?

Padronização de processos: padronizam os processos e auxiliam a fluirem de forma mais eficiente e automatizada.
Controle de processos: auxiliam no controle de processos, pois falhas são identificadas e corrigidas mais rapidamente.
Tomada de decisão: auxiliam na tomada de decisão e no cumprimento de estratégias pré-estabelecidas.
4.4 Exemplos de regras de negócio

Em um controle de qualidade de granja, pode-se dizer que a cada 100 ovos impróprios para consumo, o lote será descartado.
Em um banco, clientes com faturamento mensal de mais de R$ 25 mil e CPF sem restrições, serão atendidos pelo gerente Premium pessoa física.
Para conclusão de licitações, devem ser feitos três orçamentos e o vencedor será sempre o de menor preço final.
Em um processo de seleção de RH, o candidato só pode ser aprovado se tiver mais de 5 anos de experiência na área, diploma de pós-graduação, espanhol fluente e pretensão salarial abaixo de R$ 8.000,00.
Em um processo de vendas, o vendedor só pode vender um produto se o cliente tiver mais de 18 anos, renda familiar acima de R$ 5.000,00 e não tiver restrições no CPF.
Em um processo de compras, o fornecedor só pode ser contratado se tiver nota fiscal, certificado de qualidade e preço abaixo de R$ 10,00 por unidade.
Em um processo de logística, o pedido só pode ser enviado se o cliente tiver mais de 18 anos, endereço de entrega no mesmo estado e não tiver restrições no CPF.
4.5 Como escrever regras de negócio?

Número identificador.
Nome da regra.
Data de criação e data da última alteração para comparações e controle.
Nome dos Autores das versões.
Número da versão (1, 2 etc).
Dependências: insira o identificador das regras atreladas, às quais a regra em questão depende.
Uma descrição detalhada para compreensão da regra.
4.6 Exemplos de regras de negócio com formatação

RN01 – Criação Comanda: Para iniciar um atendimento no balcão, é necessário primeiro abrir uma nova comanda.
RN02 – Inserir Produtos Comanda: Para inserir um produto na comanda, é necessário que o produto esteja cadastrado no sistema e que a quantia comprada seja acima de zero.
RN03 – Cadastro de Leitores: Os leitores precisam fazer o cadastro para realizar o empréstimo.
RN04 – Realizar Empréstimo: Para realizar o empréstimo, apenas leitores com cadastro e nenhuma multa em aberto.
RN05 – Registro de Empréstimo: O gerente deve possuir acesso aos registros de empréstimos.
RN06 – Pagamento de Multa: O leitor que passar de 15 dias com o livro deverá pagar a multa de um real por dia de atraso.
RN07 – Impressão de Orçamento: Com as informações do orçamento registradas, a atendente deve imprimir o orçamento e repassar ao cliente para aprovação, e caso o cliente aprovar, a atendente deve solicitar a sua assinatura para aprovar a execução do serviço.
RN08 – Abertura de OS: Com o atendimento aprovado pelo cliente, a atendente deverá inserir os dados do cliente e do orçamento em um novo documento, para registros internos, realizando a abertura da OS.
RN09 – Relatório de Fluxo de Caixa: O relatório de fluxo de caixa será permitido somente para o administrador.
5. Requisitos funcionais
(Nessa parte a equipe deve descrever os requisitos funcionais que serão implementados no sistema. O texto abaixo descreve o que essa etapa deve conter e pode ser apagado depois.)

5.1 O que são requisitos funcionais?

Um requisito funcional é uma declaração de como um sistema deve se comportar. Define o que o sistema deve fazer para atender às necessidades ou expectativas do usuário. Os requisitos funcionais podem ser pensados ​como recursos que o usuário detecta.

Os requisitos funcionais são compostos de duas partes: função e comportamento.

A função é o que o sistema faz. Por exemplo: “calcular imposto sobre vendas”.
O comportamento é como o sistema faz. Por exemplo: “O sistema deve calcular o imposto sobre vendas multiplicando o preço de compra pela alíquota do imposto.”.
5.2 Tipos de requisitos funcionais

Os requisitos funcionais podem ser classificados em:

Regulamentos de Negócios
Requisitos de Certificação
Requisitos de relatório
Funções Administrativas
Níveis de autorização
Rastreamento de auditoria
Interfaces Externas
Gestão de dados
Requisitos Legais e Regulamentares
5.3 Diretrizes para a elaboração de requisitos funcionais

Cada requisito funcional precisa ser:

Específico sobre o que o sistema deve fazer.
Mensurável para que você possa dizer se o sistema está fazendo isso
Alcançável dentro do prazo que você definiu
Relevante para seus objetivos de negócios
Limitado no tempo para que você possa acompanhar o progresso
5.4 Estrutura do requisito funcional

Um requisito funcional deve ser estruturado da seguinte forma:

Nome do requisito funcional: descrição do requisito.
Dados necessários: dado 1, dado 2, dado 3.
Usuários: todos os níveis de usuário.
5.4.1 Nome do requisito funcional

R.F. 99 - Nome do requisito funcional: é o nome da função que o software terá. Sugerimos, por padronização, que tenha o prefixo R.F. (requisito funcional) seguida da numeração, para melhor identificação do requisito, acrescido do formato “Substantivo + onde será feita a ação”. Por exemplo:

R.F. 01 - Registro de Funcionários
R.F. 15 - Gerenciamento de consultas
R.F. 04 - Débito em conta corrente
Deixe para definir as numerações ao final, tendo em vista que mudanças podem acontecer e não é prático sempre ficar reajustando os números.

5.4.2 Descrição do requisito funcional

Descrição do requisito: local para descrever a função deste requisito.

Sempre se preocupe em esclarecer dois pontos: o que o requisito faz e o motivo de sua existência. Isso é especialmente importante se a ação executada nesse requisito não for algo que já acontece naturalmente na empresa. Um exemplo é um Registro de funcionários, que talvez não exista hoje mas para o software é necessário para viabilizar uma autenticação de usuários. Outro exemplo é algo que faz sentido apenas para um software, como a própria autenticação.

5.4.3 Dados necessários

Dados necessários: aqui devem ser colocados os nomes dos dados que serão usados para que esse requisito atenda o que precisa fazer.

Nas entradas e processos, em geral, são os dados que serão salvos (seja algo digitado pelo usuário ou captado do sistema, como a hora atual).

Já nas saídas, são os dados que serão exibidos em tela (sejam eles vindos diretamente do banco, ou criados por um cálculo ou busca na sessão do usuário).

5.4.4 Usuários

Usuários: aqui devem ser colocados os nomes dos usuários que terão acesso a esse requisito, conforme enumerados na descrição do sistema.

5.4.5 Exemplo de requisito funcional

R.F. 01 - Autenticação de usuário: tem como propósito autenticar o acesso ao sistema, verificando se o usuário pode acessá-lo e, caso possa, o direcionando para a página principal de seu perfil de acesso.
Dados necessários: login, senha, nível de permissão.
Usuários: todos os níveis de usuário.
5.4.6 Organização dos requisitos funcionais

As funcionalidades devem ser organizadas em: entradas, processos e saídas.

Entradas: São as funcionalidades que alimentarão o software com as informações essenciais para seu uso.

Exemplos de entradas:

“Registro de usuário” (para permitir depois seu acesso ao software).
“Registro de paciente” (que seria útil caso nosso software fosse ppara uma clínica, evitando registrar várias vezes os mesmos dados da pessoa a cada consulta e viabilizando um histórico de seus atendimentos).
Processos: Em geral, englobam toda ação que executa cálculos, processamentos de tomada de decisão ou transforma dados em novos dados.

Exemplos de processos:

“Autenticação de usuário”, que usará os dados de “Registro de usuário” em sua execução.
“Agendamento de consulta”, que usará dados do “Registro de paciente” e talvez do “Registro de funcionário” em sua execução.
Saídas: São os relatórios, gráficos, impressões, etc., que utilizarem os dados do software para gerar informações pertinentes ao negócio, mas sem intenção de alterá-los, apenas permitindo sua visualização e filtragem.

Exemplos de saídas:

“Relatório de consultas por paciente”.
Relatório de vendas”.
“Log de usuários autenticados”.
Todos esses podem ser consideradas saídas, pois usam informações de entradas e processos de modo a mostrar informações relevantes ao negócio. Lembre-se que, diferentemente das entradas e processos, aqui os dados necessários devem ser os que a tela exibirá.

5.4.7 Exemplo de organização dos requisitos funcionais

(A seguir, um exemplo de organização de requisitos funcionais, com entradas, processos e saídas.)

Entradas:

R.F. 01 - Nome do requisito funcional: descrição do requisito.

Dados necessários: dado 1, dado 2, dado 3.
Usuários: todos os níveis de usuário.
R.F. 02 - Nome do requisito funcional: descrição do requisito.

Dados necessários: dado 1, dado 2, dado 3.
Usuários: todos os níveis de usuário.
Processamento:

R.F. 03 - Nome do requisito funcional: descrição do requisito.

Dados necessários: dado 1, dado 2, dado 3.
Usuários: todos os níveis de usuário.
R.F. 04 - Nome do requisito funcional: descrição do requisito.

Dados necessários: dado 1, dado 2, dado 3.
Usuários: todos os níveis de usuário.
Saídas:

R.F. 05 - Nome do requisito funcional: descrição do requisito.

Dados necessários: dado 1, dado 2, dado 3.
Usuários: todos os níveis de usuário.
R.F. 06 - Nome do requisito funcional: descrição do requisito.

Dados necessários: dado 1, dado 2, dado 3.
Usuários: todos os níveis de usuário.
6. Requisitos não funcionais
Requisitos não funcionais (RNFs) são as restrições impostas a um sistema que definem seus atributos de qualidade.

Eles geralmente são indicados por adjetivos como segurança, desempenho e escalabilidade.

6.1 Categorias de requisitos não funcionais

Os requisitos não funcionais são importantes porque ajudam a garantir que o sistema atenda às necessidades do usuário.

Os Requisitos Não Funcionais explicam as limitações e restrições do sistema a ser projetado. Esses requisitos não têm nenhum impacto na funcionalidade do aplicativo. Além disso, existe uma prática comum de subclassificar os requisitos não funcionais em várias categorias:

Interface de Usuário
Confiabilidade
Segurança
Atuação
Manutenção
Os requisitos não funcionais podem ser divididos em duas categorias:

Atributos de qualidade: Estas são as características do sistema que determinam sua qualidade geral. Exemplos de atributos de qualidade incluem segurança, desempenho e usabilidade.
Restrições: Estas são as limitações impostas ao sistema. Exemplos de restrições incluem tempo, recursos e ambiente.
6.2 Vantagens dos requisitos não funcionais

Os requisitos não funcionais ajudam a garantir que o sistema seja:

Adaptado às necessidades do usuário.
Adequado à finalidade.
Escalável, seguro e confiável.
Fácil de usar e manter.
6.3 Exemplos de requisitos não funcionais

Aqui estão alguns exemplos de requisitos não funcionais:

Segurança: O sistema deve ser protegido contra acesso não autorizado.
Atuação: O sistema deve ser capaz de lidar com o número necessário de usuários sem qualquer degradação no desempenho.
Escalabilidade: O sistema deve ser capaz de aumentar ou diminuir conforme necessário.
Disponibilidade: O sistema deve estar disponível quando necessário.
Manutenção: O sistema deve ser fácil de manter e atualizar.
Portabilidade: O sistema deve ser capaz de rodar em diferentes plataformas com alterações mínimas.
Confiabilidade: O sistema deve ser confiável e atender aos requisitos do usuário.
Usabilidade: O sistema deve ser fácil de usar e entender.
Compatibilidade: O sistema deve ser compatível com outros sistemas.
Conformidade: O sistema deve cumprir todas as leis e regulamentos aplicáveis.
6.4 Exemplo de organização dos requisitos não funcionais

(A seguir, um exemplo de organização de requisitos não funcionais.)

Requisitos não funcionais:

R.N.F. 01 - Nome do requisito não funcional: descrição do requisito.
R.N.F. 02 - Nome do requisito não funcional: descrição do requisito.
Exemplos de requisitos não funcionais:

Sistema de Padaria:

R.N.F. 01 - Navegador homologado: O sistema deverá ser homologado para os navegadores Google Chrome e Mozilla Firefox.
R.N.F. 02 - Processador: É recomendado para o sistema no mínimo um processador Intel i3, similar ou superior a geração 7100 ou AMD Ryzen 3 da geração similar ou superior ao 3100, para que o servidor funcione em sua melhor performance.
R.N.F. 03 - Memória RAM: é recomendável que o sistema possua no mínimo 2GB de RAM para melhor performance.
R.N.F. 04 - Arquitetura: Será utilizada a arquitetiura MVC para o desenvolvimento do sistema, com uso de uma API REST para comunicação com o banco de dados.
R.N.F. 05 - Banco de dados: O sistema será implementado com o banco de dados MySQL.
R.N.F. 06 - Conexão com banco de dados: Para conexão com o banco de dados, o sistema utilizará a ferramenta de MySQL Connector.
R.N.F. 07 - Implementação: O sistema deverá ser desenvolvido com linguagem Python, Javascript, HTML5, CSS3 e SQL.
R.N.F. 08 - Segurança: Ficará a critério do responsável do estabelecimento a segurança dos acessos ao sistema, tendo consciência das pessoas que possua permissão para acesso.
R.N.F. 09 - Ambiente de Desenvolvimento Integrado (IDE): Para criação do sistema, será utilizado o editor de texto Visual Studio Code.
R.N.F. 10 - Disponibilidade: O sistema irá atender 99% do tempo de uso, somente ocorreria problemas de cadastro, remoção, inserção ou alteração em casos de falta de rede ou energia.
R.N.F. 11 - Legais: O sistema deve atender às exigências da LGPD (Leis Gerais da Proteção de Dados).
Sistema de Ordem de Serviço:

R.N.F. 01 - Navegadores homologados: o sistema deverá ser homologado para os navegadores Google Chrome e Mozilla Firefox.
R.N.F. 02 - Tecnologia Front-end: Para a exibição em front-end, o software utilizará o CSS3 e o HTML5, além do framework Vue.js.
R.N.F. 03- Tecnologia Back-end: O software será desenvolvido pela linguagem de programação Python, com o framework Django e a API REST com Django REST Framework.
R.N.F. 04 - Interoperabilidade: O banco de dados será o MySQL, com a linguagem SQL de banco, sendo todo produzido através do MySQL Workbench .
R.N.F. 05 - Forma de uso do software: O sistema por fazer parte de um ambiente interno, provavelmente será utilizado de acordo com as horas de trabalho da empresa, mas estará ativo 24 horas por dia em 7 dias por semana.
R.N.F. 06 - Desempenho: Para a utilização correta e com uma qualidade e eficiência melhor, é recomendado que se use o SO mais atualizado, com recursos de hardware equivalentes a um processador intel i3 5°Gen ou semelhante, e 8GB de memória RAM, assim como os navegadores homologados.
R.N.F. 07- Autenticação: Para realizar o acesso ao sistema é necessário ter um usuário de autenticação criado pelo administrador, além da possibilidade de solicitar um envio de redefinição de senha.
R.N.F. 08 - Web Server: O servidor web utilizado será o Apache Tomcat, nas versões mais atualizadas.
R.N.F. 09 - Níveis de segurança: O software terá diferentes tipos de acesso para cada tipo de login, tendo as permissões ideais a função de cada um.
6.6 Conclusão

Requisitos não funcionais são essenciais para qualquer sistema. Eles ajudam a garantir que o sistema atenda às necessidades do usuário e seja capaz de funcionar como pretendido.

É importante considerar cuidadosamente todos os requisitos não funcionais antes de projetar e desenvolver um sistema. Eles ajudam a garantir que o sistema atenda às necessidades do usuário e seja capaz de funcionar como pretendido.