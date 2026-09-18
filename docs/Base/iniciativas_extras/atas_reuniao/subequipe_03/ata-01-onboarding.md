# Ata 01 - Onboarding (Entrega 02)

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
  <iframe width="560" height="315" src="https://www.youtube.com/embed/9CMz1kwc8mE" title="Onboarding - Entrega 02 - SubEquipe_03" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen referrerpolicy="strict-origin-when-cross-origin"></iframe>
</div>

### Resumo

Reunião de alinhamento da SubEquipe_03 para a Entrega 02, dedicada à
definição do escopo reduzido da entrega (um diagrama estático, um
dinâmico e um diagrama complementar, totalizando cerca de dez itens) e
à discussão técnica dos primeiros esboços de diagrama de componentes e
de diagrama de classes sobre o modelo de monetização do fórum. O grupo
debateu a pertinência de manter a seção de consumo de API corporativa
no escopo, decidiu isolar temporariamente esses elementos e alinhou o
desenvolvimento assíncrono de diagramas individuais no Miro, além da
abertura de issues no repositório para reforçar a rastreabilidade do
trabalho.

### Pauta

1. Acesso ao quadro no Miro e resolução de problemas técnicos iniciais
2. Definição do escopo reduzido da entrega e esclarecimento sobre os
   tipos de diagramas estáticos e dinâmicos
3. Apresentação do diagrama de componentes em PlantUML, inspirado no
   BPMN da Entrega 01
4. Revisão do diagrama de classes gerado com apoio de IA generativa
5. Debate sobre a pertinência do consumo de API corporativa no escopo
   do fórum
6. Alinhamento arquitetural com os demais subgrupos do projeto
7. Definição do trabalho assíncrono e abertura de issues no repositório

### Detalhes da discussão

**Acesso ao quadro no Miro.** No início da reunião, os participantes
utilizaram o link do Miro compartilhado por Pedro Vargas. Bruno Souza e
Kaio Amoury relataram problemas técnicos com a tela em branco,
resolvidos após Alberto Côrtes e Pedro Vargas indicarem o uso da opção
"voltar ao quadro" (back to canvas), no canto direito da tela.

**Definição do escopo da entrega.** Kaio Amoury questionou se a equipe
já havia definido as tarefas individuais. Pedro Vargas esclareceu que a
entrega não exige issues formais por se tratar de um escopo reduzido,
composto por um diagrama estático, um dinâmico e um diagrama tático,
totalizando cerca de dez itens a entregar (00:05:10).

**Esclarecimento sobre diagramas estáticos e dinâmicos.** Bruno Souza
comentou ter elaborado um diagrama único e genérico por falta de
clareza sobre os tipos exigidos, o que levou Pedro Vargas a detalhar as
diferenças entre diagramas estáticos (classes, componentes,
implantação, pacotes e casos de uso) e dinâmicos (sequência e
comunicação). Bruno Souza expressou preocupação com o conteúdo perdido
por faltas em aula, e Alberto Côrtes informou que concluiria seu
diagrama logo após a reunião (00:06:17).

**Apresentação do diagrama de componentes.** Pedro Vargas apresentou um
diagrama de componentes estruturado no PlantUML, escolhido por ser mais
visual e intuitivo para explicar a monetização do que o diagrama de
classes (00:09:04). O diagrama foi dividido em quatro partes, inspiradas
no BPMN elaborado na Entrega 01: empresas de API (consumo de tokens via
API Gateway e validação JWT), anunciantes B2B (gerenciamento de
campanhas e métricas), ambiente Enterprise (portal de autoatendimento,
provisionamento de SSO e Teams) e faturamento (geração de fatura mensal
unificada) (00:11:52).

**Avaliação coletiva e proposta de adaptação.** Alberto Côrtes, Bruno
Souza e Kaio Amoury avaliaram positivamente a clareza do fluxo
apresentado por Pedro Vargas, embora Alberto Côrtes e Kaio Amoury
tenham apontado que a fonte, em formato SVG, estava pequena para uma
visualização geral (00:19:14, 00:21:59). Alberto Côrtes sugeriu alinhar
as divisões do diagrama de componentes com um diagrama de classes
técnico complementar, ideia apoiada por Pedro Vargas, que considerou
transformar os componentes em classes para evitar redundância com o
BPMN (00:23:06).

**Revisão do diagrama de classes gerado com apoio de IA generativa.**
Bruno Souza compartilhou um diagrama de classes gerado rapidamente com
apoio de uma ferramenta de IA generativa, destacando pontos de atenção
como a duplicação da entidade empresa, o relacionamento do painel de
controle com o usuário, a associação direta entre anúncios e tags, e
detalhes de instâncias externas sugeridos pela ferramenta (00:26:09).

**Debate sobre a pertinência do consumo de API.** Pedro Vargas
questionou se fazia sentido manter a seção de submissão de tokens de
API corporativa no diagrama, já que o projeto é um fórum acadêmico de
pequeno porte. Bruno Souza e Pedro Vargas concordaram que, embora o
estudo realizado na Entrega 01 tivesse sido útil para entender a
monetização do Stack Overflow, sua aplicação direta ao fórum do projeto
poderia não ser coerente. Bruno Souza ponderou, ainda assim, que os
estudos prévios sobre planos corporativos não deveriam ser totalmente
descartados (00:27:39).

**Caracterização da entrega como versão inicial.** Pedro Vargas
esclareceu que a entrega atual representa uma versão 1.0, de rascunho,
baseada em premissas iniciais, servindo como ponto de partida que
passará por ajustes após a implementação real do fórum (00:30:14).
Alberto Côrtes alertou sobre o trabalho adicional de rastreabilidade em
caso de alteração de diagramas já implementados, reforçando a
importância de alinhar o escopo com os demais subgrupos do projeto
(00:31:30).

**Alinhamento arquitetural com os demais subgrupos.** Alberto Côrtes e
Pedro Vargas discutiram a necessidade de uma reunião geral com os
demais subgrupos para garantir a consistência do escopo do fórum,
mencionando que o subgrupo de Kaio Amoury planejava utilizar a
arquitetura Model-View-Controller (00:32:40). Durante a conversa, Pedro
Vargas editou o quadro no Miro para isolar e remover temporariamente as
seções questionadas sobre a API corporativa (00:33:56).

**Definição do trabalho assíncrono.** Diante de restrições de agenda de
Kaio Amoury para o dia seguinte, o grupo definiu o desenvolvimento
assíncrono de diagramas individuais até a noite seguinte, para posterior
consolidação no Miro (00:36:44). Apesar da ponderação de Kaio Amoury
sobre o baixo volume de tarefas, Alberto Côrtes defendeu a abertura de
issues no repositório para manter o controle de rastreabilidade, com a
concordância final de Pedro Vargas (00:37:58).

### Encaminhamentos

| Responsável | Encaminhamento |
| -- | -- |
| Grupo | Elaborar individualmente, de forma assíncrona, um diagrama (classe, implantação ou pacote) no quadro do Miro até o dia seguinte à reunião |
| Pedro Vargas | Criar issues no repositório para manter o controle da rastreabilidade do trabalho realizado |

### Comprobatório

Gravação incorporada acima (Google Meet, publicada no YouTube):
<https://youtu.be/9CMz1kwc8mE>.
