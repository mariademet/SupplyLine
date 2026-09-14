# 📌 MVP - Painel de Fiscalização de Equipes

## 🎯 Objetivo do MVP
  > Este MVP centraliza as principais informações de como as equipes estão atuando. Pautado em métricas fundamentais, é possível mapear de modo panorâmico a presente situação das equipes de fiscalização. Assim, o MVP propicia a gestão e o planejamento de soluções viáveis.

---

## 📝 Descrição da Solução
> Breve explicação do que será desenvolvido e entregue nesta etapa.

O MVP (Sprint 1) consiste em um **dashboard geográfico de fiscalizações**, que exibe em um mapa os locais onde as operações já foram realizadas e apresenta, em paralelo, indicadores básicos de produtividade e eficiência das equipes. O usuário poderá filtrar essas informações por município e tipo de fiscalização, além de visualizar detalhes pontuais de cada fiscalização diretamente no mapa. Esta entrega é a base sobre a qual as Sprints 2 e 3 vão evoluir o produto (rotas otimizadas, simulação de cenários, comparativos e exportação de relatórios).

- **Funcionalidades principais incluídas (Sprint 1):**
  - Mapa interativo com a localização das fiscalizações realizadas
  - Dashboard com indicadores básicos (nº de fiscalizações, km percorridos, tempo médio)
  - Filtros por município e tipo de fiscalização
  - Tooltip com detalhes da fiscalização (data, tipo, equipe) ao passar o mouse sobre um ponto do mapa
  - Alternância entre tema claro e escuro

- **Limitações conhecidas (nesta etapa, já previstas para as próximas sprints):**
  - Não inclui rotas otimizadas nem comparação entre rota histórica e otimizada no mapa — previsto para a **Sprint 2**
  - Não inclui simulação de cenários de alocação de equipes (nº de equipes, distribuição de carga de trabalho) — previsto para a **Sprint 2**
  - Não inclui atalhos/bookmarks para visões do dashboard — previsto para a **Sprint 2**
  - Não inclui comparativo entre indicadores do cenário real e otimizado, nem o conjunto completo de indicadores de desempenho — previsto para a **Sprint 3**
  - Não inclui exportação de relatórios, snapshots do dashboard ou resumo automático em texto — previsto para a **Sprint 3**
  - Não inclui alertas visuais para indicadores fora da faixa esperada nem modo de apresentação em tela cheia — previsto para a **Sprint 3**

- **Escopo reduzido (somente o essencial para validar a ideia na Sprint 1):**
  - Foco na visualização geográfica e nos indicadores essenciais de operação
  - Interface simples, priorizando clareza dos dados sobre customização
  - Validação da hipótese de que visão geográfica + indicadores básicos já geram valor de gestão para analistas e gestores, antes de investir nas funcionalidades mais custosas de otimização de rotas e simulação (Sprint 2)

---

## 👥 Personas / Usuários-Alvo
- **Usuário:** persona que rege a acessibilidade e funcionalidades gerais do software, pensando na interface 
- **Analista de fiscalização:** focado nos resultados das operações, eficiência de fiscalizações, precisando ter um panorama da produtividade
- **Gestor de equipes:** pensa no manejo de pessoas, precisa entender a distribuição das equipes e facilitar sua gestão

---

## 🔑 User Stories (Backlog Completo)
| ID  | Sprint | User Story                                                                                                                                                                                                | Prioridade | Estimativa |
|-----|--------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|------------|
| 1   | 1      | Eu, como analista de fiscalização, quero ver no mapa os locais das fiscalizações já realizadas, para entender a distribuição geográfica da operação atual                                             | Alta       | 8          |
| 2   | 1      | Eu, como analista de fiscalização, quero ver indicadores básicos (nº de fiscalizações, km percorridos, tempo médio) no dashboard, para ter uma visão geral da eficiência da operação                  | Alta       | 5          |
| 3   | 1      | Eu, como analista de fiscalização, quero filtrar o mapa e os indicadores por município e tipo de fiscalização, para identificar onde está concentrada a demanda                                       | Média      | 3          |
| 4   | 1      | Eu, como usuário, quero ver um tooltip com detalhes (data, tipo, equipe) ao passar o mouse sobre um ponto do mapa, para inspecionar uma fiscalização sem sair da visão geral                          | Baixa      | 3          |
| 5   | 1      | Eu, como usuário, quero alternar entre tema claro e escuro no dashboard, para usar em diferentes ambientes de trabalho                                                                                 | Baixa      | 2          |
| 6   | 2      | Eu, como gestor de equipes, quero ver as rotas históricas e as rotas otimizadas lado a lado no mapa, para planejar melhor a alocação das equipes nos próximos ciclos                                   | Alta       | 20         |
| 7   | 2      | Eu, como gestor de equipes, quero ver como a carga de trabalho ficaria distribuída entre as equipes no cenário otimizado, para avaliar se a divisão está equilibrada                                  | Alta       | 8          |
| 8   | 2      | Eu, como gestor de equipes, quero simular um cenário alterando parâmetros simples (ex: nº de equipes), para testar diferentes formas de alocar minha equipe                                           | Alta       | 8          |
| 9   | 2      | Eu, como usuário, quero salvar atalhos (bookmarks) para as visões mais usadas do dashboard, para navegar mais rápido entre análises                                                                    | Baixa      | 3          |
| 10  | 2      | Eu, como usuário, quero ver uma transição animada ao alternar entre rota histórica e rota otimizada no mapa, para perceber mais claramente a diferença entre as duas                                  | Baixa      | 2          |
| 11  | 3      | Eu, como analista de fiscalização, quero comparar lado a lado os indicadores do cenário real e do otimizado, para quantificar os ganhos de eficiência conquistados pelo modelo                        | Alta       | 8          |
| 12  | 3      | Eu, como analista de fiscalização, quero ver o conjunto completo de indicadores de desempenho no dashboard, para acompanhar a eficiência da operação de forma abrangente                              | Alta       | 5          |
| 13  | 3      | Eu, como gestor de equipes, quero exportar relatórios com mapas, indicadores e comparativos, para compartilhar os resultados do planejamento das equipes com a diretoria do IPEM                      | Alta       | 5          |
| 14  | 3      | Eu, como gestor de equipes, quero refinar a simulação de cenários permitindo ajustar mais parâmetros (restrições de equipe, prioridade de município), para ter mais flexibilidade ao planejar a alocação | Média      | 8          |
| 15  | 3      | Eu, como usuário, quero ver um resumo automático em texto destacando os principais insights do período selecionado, para entender rapidamente o que mudou sem ler todos os gráficos                   | Baixa      | 5          |
| 16  | 3      | Eu, como usuário, quero um modo de apresentação em tela cheia, para ter uma experiência mais imersiva ao navegar pelo dashboard                                                                        | Baixa      | 2          |
| 17  | 3      | Eu, como usuário, quero receber alertas visuais (cor/ícone) quando algum indicador sair da faixa esperada, para identificar problemas de forma rápida e intuitiva                                     | Baixa      | 3          |
| 18  | 3      | Eu, como usuário, quero exportar um "snapshot" (imagem) do dashboard com um clique, para compartilhar rapidamente por e-mail ou WhatsApp                                                               | Baixa      | 3          |

> **Observação:** o MVP em si corresponde apenas às histórias da Sprint 1 (IDs 1–5); as demais (Sprints 2 e 3) compõem a evolução planejada do produto e sustentam as limitações listadas na seção de Descrição da Solução.

---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                                                                                                                                             | Status        |
|--------|--------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|
| 01 *(MVP)* | US1 – Mapa com locais das fiscalizações; US2 – Indicadores básicos; US3 – Filtros por município e tipo; US4 – Tooltip com detalhes; US5 – Tema claro/escuro | Em andamento  |
| 02     | US6 – Rotas históricas x otimizadas no mapa; US7 – Distribuição de carga de trabalho simulada; US8 – Simulação de cenários (nº de equipes); US9 – Bookmarks de visões; US10 – Transição animada entre rotas | Planejado     |
| 03     | US11 – Comparativo real x otimizado; US12 – Conjunto completo de indicadores; US13 – Exportação de relatórios; US14 – Simulação com parâmetros avançados; US15 – Resumo automático; US16 – Modo apresentação; US17 – Alertas visuais; US18 – Snapshot do dashboard | Planejado     |

---

## 📊 Critérios de Aceitação
- O MVP deve permitir que o usuário visualize no mapa todos os pontos de fiscalização já realizados, com filtragem por município e tipo (US1, US3)
- O sistema deve registrar e exibir corretamente os indicadores de nº de fiscalizações, km percorridos e tempo médio por operação (US2)
- Ao passar o mouse sobre um ponto do mapa, o sistema deve exibir um tooltip com data, tipo de fiscalização e equipe responsável, sem exigir navegação para outra tela (US4)
- O usuário deve conseguir alternar entre tema claro e escuro a qualquer momento, com a preferência mantida durante a sessão (US5)
- Métricas coletadas: tempo de carregamento do mapa e dashboard, taxa de uso dos filtros, frequência de uso do tooltip e do alternador de tema

---

## 📈 Métricas de Validação
- Número de usuários que testaram o MVP  
- Feedback qualitativo (positivo/negativo)  
- Indicadores de negócio (exemplo: % de adesão, redução de custo, etc.)  

---

## 🚀 Próximos Passos
- Melhorias planejadas após feedback  
- Ajustes de usabilidade  
- Expansão de funcionalidades para próximo incremento  

---

## 📂 Anexos / Evidências
- Prints de tela  
- Fluxos ou protótipos  
- Vídeo (MVP)
