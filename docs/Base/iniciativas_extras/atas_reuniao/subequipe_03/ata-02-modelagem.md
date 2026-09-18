# Ata 02 - Modelagem (Entrega 02)

**Data:** 15/09/2026
**Subgrupo:** SubEquipe_03
**Canal:** Google Meet
**Liderança responsável:** Pedro Felipe Silva Vargas

### Participantes

| Nome do Membro | Presente |
| -- | :-: |
| Alberto Côrtes Cavalcante | Sim |
| Bruno Souza Assis Furtado | Sim |
| Kaio Amoury Sasaki Acacio | Sim |
| Pedro Felipe Silva Vargas | Sim |

### Gravação

<div style="text-align: center;">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/i1uvw6Q68YI" title="Modelagem - Entrega 02 - SubEquipe_03" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen referrerpolicy="strict-origin-when-cross-origin"></iframe>
</div>

### Resumo

Reunião de modelagem da SubEquipe_03 para a Entrega 02, dedicada à
definição da arquitetura MVC como padrão do sistema e à redução do
escopo técnico para garantir a entrega dentro do prazo, restringindo o
projeto ao sistema de anúncios online e excluindo a API de dados e o
módulo Teams. Após identificar falhas de precisão nos diagramas
gerados com apoio de IA generativa, o grupo optou por modelar
manualmente o diagrama de pacotes no Miro, estruturando as camadas
View, Controller e Model. O diagrama foi adotado provisoriamente como
modelo base, com validação final condicionada à revisão dos demais
integrantes, e o grupo definiu o cronograma para a modelagem dinâmica
e o diagrama de classes nos dias seguintes.

### Pauta

1. Discussão sobre a arquitetura do Stack Overflow e adoção da
   arquitetura MVC para o projeto
2. Avaliação do diagrama de componentes gerado com apoio de IA
   generativa
3. Redução do escopo do projeto para o sistema de anúncios online
4. Definição do cronograma de modelagem estática e dinâmica
5. Construção manual do diagrama de pacotes no Miro
6. Estruturação das camadas View, Controller e Model
7. Novas tentativas de geração de diagramas com IA generativa e
   avaliação dos resultados
8. Planejamento da modelagem dinâmica e encaminhamentos finais

### Detalhes da discussão

**Estratégia de arquitetura e análise do Stack Overflow.** Pedro Vargas
e Alberto Côrtes discutiram a adoção da arquitetura MVC
(Model-View-Controller) para o projeto, considerando-a a opção mais
eficiente para a organização da equipe. Ambos ponderaram que, embora
não tivessem certeza absoluta, acreditavam que o Stack Overflow utiliza
uma arquitetura monolítica, devido à complexidade e à variedade de seus
sistemas e pacotes (00:00:42).

**Modelagem estática e avaliação do diagrama gerado por IA.** Alberto
Côrtes apresentou um diagrama de componentes gerado com apoio de IA
generativa, destacando quatro quadrantes principais de receita do
Stack Overflow: Teams, anúncios, API e faturamento unificado
(00:02:12). A dupla analisou o funcionamento de cada subsistema,
discutindo a necessidade de autenticação corporativa para o Teams e a
integração de dados para faturamento (00:03:43). Alberto Côrtes
observou que, embora o diagrama tivesse trazido contexto útil, a
ferramenta falhou em seguir padrões estritos de modelagem,
apresentando problemas na direção das setas e sobreposição de
elementos (00:02:12, 00:06:55).

**Definição do escopo do projeto e ferramentas de modelagem.** A
equipe avaliou o uso de ferramentas como PlantUML e Mermaid, mas
relatou dificuldades em manter os padrões exigidos, com elementos
sobrepostos (00:06:55). Diante do prazo de um mês para a conclusão do
projeto, Pedro Vargas e Alberto Côrtes decidiram simplificar o escopo,
removendo a API de dados e possivelmente o módulo Teams, para
concentrar o trabalho exclusivamente na implementação do sistema de
anúncios (00:08:19). Avaliaram que a complexidade do módulo Teams
exigiria um tempo de desenvolvimento que a equipe não tinha disponível
no momento (00:09:38).

**Cronograma da modelagem.** Alberto Côrtes e Pedro Vargas alinharam o
cronograma para concluir toda a modelagem estática e dinâmica até o
dia seguinte, permitindo uma revisão geral na quinta-feira. Decidiram
utilizar o Miro para a criação manual dos diagramas, buscando corrigir
os erros de padronização observados anteriormente nos diagramas
gerados por IA (00:11:09).

**Alinhamento do diagrama de pacotes.** Pedro Vargas compartilhou um
diagrama de pacotes de outro subgrupo como referência, destacando o
uso de tags em campanhas, recurso que a equipe decidiu incorporar
(00:15:17). Discutiram a estrutura do diagrama, definindo que deveria
ser técnico e específico, focado em pacotes de publicidade e de
receita, anteriormente chamado de faturamento (00:23:38).

**Estrutura do modelo MVC.** Pedro Vargas detalhou a estrutura do
sistema baseada em MVC: a camada View conteria telas de gestão de
campanha, dashboards de relatórios e histórico de pagamentos; a camada
Controller processaria os dados dos formulários e gerenciaria métricas
e transações; e a camada Model seria responsável pelo armazenamento de
tabelas no banco de dados, incluindo dados de anúncios, campanhas,
estatísticas de cliques e visualizações, e faturas (00:44:42).

**Refinamento final do diagrama de pacotes.** A equipe refinou o
modelo, adicionando uma pasta dedicada à veiculação de anúncios para
representar a entrega ao fórum (00:52:53). Pedro Vargas e Alberto
Côrtes confirmaram que as setas no diagrama de pacotes deveriam ser
tracejadas, conforme as exigências do material da disciplina, e
concluíram que a proposta sintetizava adequadamente o funcionamento do
sistema (00:54:23).

**Novas tentativas de geração de diagramas com IA generativa.** Pedro
Vargas e Alberto Côrtes discutiram a dificuldade de utilizar IA
generativa para gerar diagramas de componentes e de classes.
Observaram que os diagramas de classes gerados pela ferramenta não
seguiam a estrutura adequada, com Pedro Vargas apontando que a
ferramenta parecia confundir diagramas de pacotes com diagramas de
classes, apresentando inconsistências visuais (00:57:29). Alberto
Côrtes mencionou que a versão utilizada consumia muitos tokens sem
entregar a precisão esperada (01:08:57).

**Disponibilidade da equipe.** Durante a conversa, Pedro Vargas
comentou sobre a dificuldade de manter a rotina devido ao acúmulo de
estágio e estudos, mencionando que a disponibilidade do grupo seria
afetada por compromissos de outros integrantes do projeto ao longo da
semana (01:08:57). Alberto Côrtes indicou que, ao tentar refinar as
gerações da IA, atingiu cerca de 90% do limite de uso da ferramenta
(01:14:11).

**Avaliação final e decisão técnica.** Ao analisar uma das saídas da
IA, Pedro Vargas identificou falhas técnicas, como a representação
incorreta de relações e a criação indesejada de uma classe específica
para prazos (01:12:40). Diante da complexidade e dos erros recorrentes
na automação, Pedro Vargas e Alberto Côrtes concordaram em adotar o
diagrama de pacotes construído manualmente como base para os próximos
artefatos (01:14:11).

**Planejamento da modelagem dinâmica.** Pedro Vargas e Alberto Côrtes
planejaram iniciar a modelagem dinâmica na quarta-feira, às 9h, para
otimizar o tempo disponível. O grupo pretende complementar a entrega
com um diagrama de classes na quinta-feira (01:16:36). Pedro Vargas
assumiu a responsabilidade de criar tarefas no GitHub na manhã
seguinte, para melhorar a rastreabilidade, e de compartilhar o
diagrama escolhido com os demais membros para revisão. Alberto Côrtes
confirmou que enviaria as gravações da reunião para o repositório do
GitHub (01:19:22).

### Encaminhamentos

| Responsável | Encaminhamento |
| -- | -- |
| Grupo | Finalizar a modelagem estática e dinâmica do sistema de anúncios até o dia seguinte, alinhando todas as etapas para revisão na quinta-feira |
| Alberto Côrtes | Gerar, com apoio de IA generativa, um diagrama de classes ou de componentes a partir do modelo de pacotes atual, utilizando texto de apoio para garantir a precisão técnica |
| Alberto Côrtes | Refazer o diagrama de classes, utilizando a IA generativa de forma mais criteriosa, com prompts mais específicos |
| Pedro Vargas | Registrar as tarefas como issues no GitHub, para melhorar a rastreabilidade das atividades |
| Pedro Vargas | Adicionar o diagrama de pacotes ao repositório do projeto |
| Pedro Vargas | Comunicar a equipe sobre o diagrama escolhido e solicitar revisões ou sugestões de melhoria |
| Alberto Côrtes | Enviar as gravações da reunião para o repositório do GitHub |
| Grupo | Iniciar a modelagem dinâmica na quarta-feira, a partir das 9h |

### Comprobatório

Gravação incorporada acima (Google Meet, publicada no YouTube):
<https://youtu.be/i1uvw6Q68YI>.
