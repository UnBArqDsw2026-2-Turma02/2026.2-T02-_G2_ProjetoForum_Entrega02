# Ata de Reunião — Arquitetura DSW

**Data:** 15/09/2026  
**Duração:** 1h35  
**Participantes:** Luis Zarbielli, Artur Camargos, Caio Soares e Maria Laura

## Objetivo da reunião

Realizar uma sessão de trabalho para discussão, construção e evolução dos artefatos de arquitetura do projeto, buscando alinhar a representação das funcionalidades, as relações entre os componentes do sistema e as fronteiras do subdomínio.

## Atividades e discussões

A reunião foi dedicada à construção e evolução dos artefatos arquiteturais, com os participantes trabalhando simultaneamente na elaboração dos diagramas e na discussão das funcionalidades que deveriam ser representadas.

Luis Zarbielli desenvolveu o **diagrama de comunicação da funcionalidade de publicar pergunta**, enquanto Artur Camargos desenvolveu o **diagrama de comunicação da funcionalidade de responder pergunta**. Durante a atividade, foram discutidas as funcionalidades envolvidas e a forma adequada de elaborar os diagramas de comunicação, buscando alinhar a representação dos fluxos ao funcionamento previsto do sistema.

Na sequência, Caio Soares evoluiu a construção dos diagramas seguindo o **padrão apresentado pela professora**, sem realizar aumento ou ampliação das funcionalidades consideradas no escopo. Nesse processo, desenvolveu o **diagrama de comunicação da etapa de escolher uma tag**.

Maria Laura desenvolveu o **diagrama de comunicação da funcionalidade de editar conteúdo**, mantendo discussões com o restante do time para delimitar as fronteiras desse subdomínio em relação ao **domínio de Reputação (Subgrupo 2)**.

Posteriormente, Caio Soares retomou o **diagrama de pacotes**, trabalhando na inclusão da **persistência de dados** e na explicitação das **semânticas das setas** utilizadas no diagrama. Paralelamente, Caio e Maria Laura trabalharam em conjunto na construção do **diagrama de classes** e também colaboraram na elaboração do **diagrama de comunicação**.

Durante a construção do diagrama de classes, foi discutida especificamente a questão dos **diferentes níveis de acesso para edição e gerenciamento das perguntas**. Foi levantado, como exemplo, que um usuário pode possuir permissão para editar uma questão, enquanto um moderador pode possuir responsabilidades adicionais, como **fechar um tópico**.

Maria Laura acrescentou que o **moderador também possui a responsabilidade de aprovar respostas**, reforçando durante a discussão a existência de uma **distinção clara de papéis e permissões** entre usuário e moderador.

## Resultado da reunião

A reunião resultou na construção e evolução de diversos artefatos de arquitetura, incluindo diagramas de comunicação para diferentes funcionalidades, evolução do diagrama de pacotes com representação de persistência e semânticas das relações, e construção colaborativa do diagrama de classes.

Também foram levantadas questões relacionadas à delimitação do subdomínio, especialmente em relação ao domínio de Reputação, e às diferentes responsabilidades e permissões associadas aos papéis de usuário e moderador.

## Encaminhamentos

**Caio Soares e Maria Laura** ficaram responsáveis pelo desenvolvimento das **iniciativas extras** e do **Foco 3**.

**Luis Zarbielli e Artur Camargos** ficaram responsáveis por discutir e documentar **como a Inteligência Artificial foi utilizada no processo de diagramação e modelagem**.
