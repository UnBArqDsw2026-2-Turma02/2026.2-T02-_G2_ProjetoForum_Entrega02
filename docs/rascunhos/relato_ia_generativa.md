# Relato de Uso da IA Generativa (SubEquipe_02)

O trabalho com a IA Generativa ocorreu de forma iterativa e consultiva, focando na compreensão das regras de negócio do subdomínio de **Conteúdo** e na tradução dessas regras para a **Modelagem Dinâmica (Diagrama de Comunicação)**.

Abaixo, um resumo de como a IA auxiliou no processo até aqui:

## 1. Levantamento e Análise de Funcionalidades (Engenharia Reversa)
Primeiramente, a IA analisou os relatórios da Entrega 01 e da SubEquipe_01 para mapear as **7 principais funcionalidades** idealizadas para o Fórum (Editor de Texto, Sistema de Tags, Duplicatas, Resposta Aceita, Edição Wiki, Fechamento e Reputação).

Em seguida, a IA fez um mapeamento do repositório via `git` para localizar o que já havia sido modelado, encontrando o diagrama de "Aceitar Resposta" feito por outro membro, servindo como base visual e técnica (padrão de camadas MVC, numeração hierárquica e linearidade).

## 2. Escolha do Cenário para Modelagem Dinâmica
A IA avaliou as funcionalidades restantes e sugeriu quais se encaixariam melhor em um **Diagrama de Comunicação**. A funcionalidade do **Sistema de Tags** foi escolhida devido à sua riqueza em interação entre camadas, especialmente na resolução de "sinônimos" por debaixo dos panos (onde a View não precisa conhecer a lógica de negócios).

## 3. Estruturação do Fluxo de Mensagens (UML)
A partir da funcionalidade escolhida, a IA ajudou a construir o fluxo passo a passo:
- **Refinamento de Nomenclatura:** Os nomes dos métodos foram simplificados para o padrão de código real (ex: `addTag`, `getCanonical`, `attach`).
- **Simplicidade e Linearidade:** Após um rascunho inicial complexo (com bifurcações), a IA foi orientada a simplificar o modelo para um fluxo único, direto e linear, focando no "caminho feliz" da inserção de um sinônimo (ex: usuário digita `js` e o sistema resolve para `javascript`).

## 4. Geração de Artefatos
Por fim, a IA gerou os insumos finais para compor o relatório da SubEquipe_02:
- Um rascunho em **Markdown** contendo a Metodologia, a explicação do Modelo Dinâmico e a Tabela de Rastreabilidade (vinculando as mensagens do diagrama às decisões do SIG da Entrega 01).
- Esboços de diagramas em **Mermaid** (tanto fluxo quanto sequência), corrigindo inclusive sintaxe de setas de retorno (`-->>`).
- Um **guia prático (passo a passo)** orientando como desenhar o Diagrama de Comunicação manualmente no canvas do Miro, distribuindo os atores, instâncias e numerando as mensagens.

## 5. Assistência na Organização, Revisão e Rastreabilidade
Durante o processo de fechamento do relatório, a IA continuou prestando suporte vital na qualidade técnica dos artefatos entregues e na organização do repositório:
- **Organização de Assets:** Os diagramas de diversas versões gerados ao longo do tempo foram agrupados estruturalmente (ex.: `assets/v1`, `assets/v2`, `IAZARB/v0`, etc.), com as referências no Markdown devidamente atualizadas via scripts automatizados sem quebrar o relatório.
- **Revisão Técnica de Modelos UML:** A IA ajudou a identificar e redigir as mudanças técnicas feitas de uma versão para a outra (ex.: do v1.0 para v2.0), destacando as correções semânticas da UML como a adoção do boneco (stick figure `«ator»`) para atores em diagramas de comunicação e a correção dos tipos de setas indicativas de mensagens (evitando misturar setas de Diagramas de Sequência em Comunicação).
- **Adequação da Rastreabilidade:** A IA também ajudou a refinar a seção de Rastreabilidade, corrigindo a classificação de Modelos Estáticos (como Diagrama de Pacotes e Diagrama de Classes) que haviam sido erroneamente listados no FOCO_02 (Modelagem Dinâmica), realocando-os para o FOCO_01 e vinculando cada modelo de volta às features (como Sistema de Tags, Duplicatas, etc.) extraídas da Engenharia Reversa da Entrega 01.
