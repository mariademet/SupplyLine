# 📌 MVP - Painel de Fiscalização de Equipes

## 🎯 Objetivo do MVP
  > Este MVP centraliza as principais informações de como as equipes estão atuando. Pautado em métricas fundamentais, é possível mapear de modo panorâmico a presente situação das equipes de fiscalização. Assim, o MVP propicia a gestão e o planejamento de soluções viáveis.

---

## 📝 Descrição da Solução
> Breve explicação do que será desenvolvido e entregue nesta etapa.

O MVP consiste em um **dashboard geográfico de fiscalizações**, que exibe em um mapa os locais onde as operações já foram realizadas e apresenta, em paralelo, indicadores básicos de produtividade e eficiência das equipes. O usuário poderá filtrar essas informações por município e tipo de fiscalização, além de visualizar detalhes pontuais de cada fiscalização diretamente no mapa.

- **Funcionalidades principais incluídas:**
  - Mapa interativo com a localização das fiscalizações realizadas
  - Dashboard com indicadores básicos (nº de fiscalizações, km percorridos, tempo médio)
  - Filtros por município e tipo de fiscalização
  - Tooltip com detalhes da fiscalização (data, tipo, equipe) ao passar o mouse sobre um ponto do mapa
  - Alternância entre tema claro e escuro

- **Limitações conhecidas:**
  - Sem edição ou cadastro de fiscalizações pela interface (somente visualização)
  - Filtros limitados a município e tipo de fiscalização (sem cruzamento avançado de variáveis)
  - Sem exportação de relatórios ou dados nesta etapa
  - Sem gestão de usuários/permissões diferenciadas por perfil

- **Escopo reduzido (somente o essencial para validar a ideia):**
  - Foco na visualização geográfica e nos indicadores essenciais de operação
  - Interface simples, priorizando clareza dos dados sobre customização
  - Validação da hipótese de que visão geográfica + indicadores básicos já geram valor de gestão para analistas e gestores

---

## 👥 Personas / Usuários-Alvo
- **Usuário:** persona que rege a acessibilidade e funcionalidades gerais do software, pensando na interface 
- **Analista de fiscalização:** focado nos resultados das operações, eficiência de fiscalizações, precisando ter um panorama da produtividade
- **Gestor de equipes:** pensa no manejo de pessoas, precisa entender a distribuição das equipes e facilitar sua gestão

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                 | Prioridade | Estimativa |
|-----|-----------------------------------------------------------------------------|------------|------------|
|1     |Eu, como analista de fiscalização, quero ver no mapa os locais das fiscalizações já realizadas, para entender a distribuição geográfica da operação atual                                               |Alta      |8         |
|2     |Eu, como analista de fiscalização, quero ver indicadores básicos (nº de fiscalizações, km percorridos, tempo médio) no dashboard, para ter uma visão geral da eficiência da operação                    |Alta      |5         |
|3     |Eu, como analista de fiscalização, quero filtrar o mapa e os indicadores por município e tipo de fiscalização, para identificar onde está concentrada a demanda                                         |Média     |3         |
|4     |Eu, como usuário, quero ver um tooltip com detalhes (data, tipo, equipe) ao passar o mouse sobre um ponto do mapa, para inspecionar uma fiscalização sem sair da visão geral                            |Baixa     |3         |
|5     |Eu, como usuário, quero alternar entre tema claro e escuro no dashboard, para usar em diferentes ambientes de trabalho                                                                                  |Baixa     |2         | 


---

## 📅 Sprint(s) Relacionadas
| Sprint | Entregas Principais                                                        | Status        |
|--------|------------------------------------------------------------------------------|---------------|
| 01     | US1 – Mapa com locais das fiscalizações; US2 – Indicadores básicos no dashboard | Planejado     |
| 01     | US3 – Filtros por município e tipo de fiscalização; US4 – Tooltip com detalhes no mapa | Planejado  |
| 01     | US5 – Alternância entre tema claro e escuro                                  | Planejado     |

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
