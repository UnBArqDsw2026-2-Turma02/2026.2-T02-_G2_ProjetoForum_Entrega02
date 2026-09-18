# Ata 03 - Deadline (Entrega 02)

**Data:** 17/09/2026
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
  <iframe width="560" height="315" src="https://www.youtube.com/embed/yQ5UOgAwfq8" title="Deadline - Entrega 02 - SubEquipe_03" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen referrerpolicy="strict-origin-when-cross-origin"></iframe>
</div>

### Resumo

Reunião de fechamento da SubEquipe_03 para a Entrega 02, dedicada à
configuração do repositório do GitHub para centralizar as entregas, à
definição do escopo final de monetização restrito a anúncios
(descartando a API para empresas e o módulo Teams) e ao detalhamento
das linhas de vida do diagrama de sequência do fluxo de exibição de
anúncios, faturamento e inadimplência. O grupo distribuiu as tarefas
finais entre os integrantes para carregar os diagramas no repositório,
avaliar criticamente o uso de IA generativa e consolidar a
documentação até o prazo de entrega, no meio-dia do dia seguinte.

### Pauta

1. Configuração do repositório no GitHub e definição dos modelos
   estático e dinâmico
2. Definição do escopo final de monetização restrito a anúncios
3. Detalhamento das linhas de vida do diagrama de sequência
4. Fluxo de exibição de anúncios e registro de métricas de estatísticas
5. Fluxo de processamento de pagamento, faturamento e inadimplência
6. Avaliação de modelos alternativos de diagramas (Teams e API)
7. Prazos de entrega e distribuição de tarefas no GitHub

### Detalhes da discussão

**Configuração do repositório e definição dos modelos.** Pedro Vargas
informou que criou um repositório no GitHub para centralizar todas as
entregas do projeto. Ficou estabelecido que a modelagem estática
utilizaria diagramas de classes e de pacotes, enquanto a modelagem
dinâmica usaria um diagrama de sequência (00:00:23). Bruno Souza
relatou que havia concluído o diagrama de sequência baseado no
template de monetização de negócio para negócio, por processo de
pagamento, e Pedro Vargas carregou os relatórios e o diagrama no Miro
(00:03:39).

**Escopo de monetização e estrutura das linhas de vida.** Pedro Vargas
explicou que, devido ao tempo limitado de desenvolvimento, a equipe
decidiu manter apenas os anúncios como forma de monetização,
descartando as funcionalidades de API para empresas e o módulo Teams
(00:11:13). Em seguida, detalhou as linhas de vida do diagrama de
sequência: o controlador de entrega (motor que recebe requisições,
cruza tags e entrega banners), a entidade pergunta (conteúdo do fórum
associado a tags), o controlador de campanha (gestão de campanhas dos
anunciantes), a campanha (orçamento, tags e status cadastrados pelo
anunciante) e o anúncio contextual (00:13:42).

**Fluxo de exibição de anúncios e métricas.** Pedro Vargas apresentou o
passo a passo em que o acesso de um usuário a uma pergunta aciona o
controlador de entrega, que consulta as tags e busca campanhas ativas
no controlador de campanha por meio de um loop (00:16:49). Havendo
compatibilidade, o anúncio contextual retorna um banner personalizado;
caso contrário, o sistema instancia um anúncio genérico, que é
renderizado e depois destruído. As interações disparam o incremento de
visualizações e cliques na entidade de estatísticas, além de debitar
cliques diretamente na campanha (00:18:26).

**Processamento de pagamento, faturamento e inadimplência.** Pedro
Vargas explicou a sequência voltada ao faturamento e à inadimplência:
o encerramento de um período comercial gera uma fatura que interage
com as estatísticas para calcular o valor devido (00:20:06). No
caminho padrão, o pagamento ocorre por meio da tela de pagamento e da
confirmação da transação. Em caso de inadimplência, com status
positivo e sem pagamento, a campanha é suspensa por meio de uma
chamada ao controlador de campanha (00:21:36). Se o pagamento ocorrer
posteriormente, em atraso, a campanha é reativada; caso o pagamento
não seja efetuado, o contrato e a fatura são cancelados (00:22:58).
Kaio Amoury e Bruno Souza avaliaram que o diagrama ficou completo,
claro e fácil de entender (00:25:43).

**Avaliação de modelos alternativos de diagramas.** Bruno Souza
ponderou que o diagrama desenvolvido havia focado na contratação de
planos internos do Teams, enquanto Kaio Amoury havia focado na API do
Stack Overflow. Pedro Vargas considerou positivo manter ambos os
modelos como referência, caso a equipe decida retomar essas ideias
futuramente, validando a manutenção dos diagramas já apresentados
(00:29:44).

**Prazos de entrega e distribuição de tarefas.** Pedro Vargas informou
que a entrega, feita por meio de vídeo, tem prazo até o meio-dia do
dia seguinte (00:30:47). Para a organização no GitHub, as tarefas
foram distribuídas: Bruno Souza ficou responsável pelo diagrama de
pacotes, Kaio Amoury pelo diagrama de classes, e Pedro Vargas pelo
diagrama de sequência (00:34:00). Alberto Côrtes ficou encarregado do
quadro de participações e das atas, enquanto a avaliação crítica e as
lições aprendidas sobre IA generativa seriam desenvolvidas por todos
os integrantes (00:32:42). Por fim, Pedro Vargas reforçou a
necessidade de manter o versionamento na documentação e de submeter
os pull requests para revisão (00:35:23).

### Encaminhamentos

| Responsável | Encaminhamento |
| -- | -- |
| Bruno Souza | Carregar o diagrama de pacotes no repositório do GitHub |
| Kaio Amoury | Carregar o diagrama de classes no repositório do GitHub |
| Pedro Vargas | Carregar o diagrama de sequência no repositório do GitHub |
| Grupo | Registrar as lições aprendidas e a avaliação crítica sobre IA generativa no repositório |
| Alberto Côrtes | Consolidar o relatório, preencher o quadro de participações e finalizar a documentação do projeto |
| Grupo | Verificar a configuração do controle de versão ao realizar os commits na documentação |

### Comprobatório

Gravação incorporada acima (Google Meet, publicada no YouTube):
<https://youtu.be/yQ5UOgAwfq8>.
