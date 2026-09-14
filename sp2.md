# 📌 MVP - Painel de Fiscalização de Equipes (Sprint 2 – Otimização de Rotas e Simulação)

## 🎯 Objetivo do MVP
> Descrever de forma clara qual é o propósito do MVP:

- **Qual problema resolve?** Gestores de equipes hoje não têm como comparar visualmente as rotas históricas com uma alternativa otimizada, nem como estimar o impacto de mudanças na alocação de equipes antes de aplicá-las na operação.
- **Qual hipótese será validada?** Se o gestor conseguir visualizar rotas otimizadas lado a lado com o histórico e simular cenários simples de alocação (variando o número de equipes), ele tomará decisões de planejamento mais rápidas e embasadas.
- **Qual valor será entregue ao usuário final?** Redução do tempo de planejamento de rotas, maior equilíbrio na distribuição de carga entre equipes e uma primeira camada de simulação que evolui, na Sprint 3, para parâmetros mais avançados de restrição e priorização.

---

## 📝 Descrição da Solução
> Breve explicação do que será desenvolvido e entregue nesta etapa.

Esta etapa evolui o dashboard geográfico entregue na Sprint 1, adicionando a comparação entre rotas históricas e rotas otimizadas, a simulação de cenários de alocação de equipes e recursos de navegação mais rápidos no dashboard (bookmarks e transições animadas).

- **Funcionalidades principais incluídas:**
  - Visualização lado a lado de rotas históricas e rotas otimizadas no mapa
  - Distribuição simulada da carga de trabalho entre equipes no cenário otimizado
  - Simulação de cenário com ajuste de parâmetro simples (nº de equipes)
  - Bookmarks (atalhos) para as visões mais usadas do dashboard
  - Transição animada ao alternar entre rota histórica e rota otimizada

- **Limitações conhecidas (nesta etapa, já previstas para a Sprint 3):**
  - A simulação de cenários aceita apenas o parâmetro "nº de equipes" — ajuste de restrições de equipe e priorização por município fica para a **Sprint 3**
  - Não inclui comparativo quantitativo entre os indicadores do cenário real e do otimizado — previsto para a **Sprint 3**
  - Não inclui o conjunto completo de indicadores de desempenho do dashboard — previsto para a **Sprint 3**
  - Não inclui exportação de relatórios, snapshots do dashboard ou resumo automático em texto — previsto para a **Sprint 3**
  - Não inclui alertas visuais de indicadores fora da faixa esperada nem modo de apresentação em tela cheia — previsto para a **Sprint 3**

- **Escopo reduzido (somente o essencial para validar a ideia nesta etapa):**
  - Simulação de cenário limitada a um único parâmetro (nº de equipes), para validar se o conceito de "simular antes de alocar" já gera valor percebido
  - Comparação de rotas focada na visualização no mapa, sem quantificação numérica de ganhos (isso fica para a Sprint 3)
  - Bookmarks e transições animadas como melhorias de usabilidade, sem personalização avançada (ex.: compartilhamento de bookmarks entre usuários)

---

## 👥 Personas / Usuários-Alvo
- **Gestor de equipes:** foco principal desta sprint — precisa comparar rotas e simular cenários de alocação para planejar a distribuição das equipes de forma mais equilibrada e eficiente
- **Usuário:** beneficiado pelas melhorias de navegação (bookmarks e transições animadas), que tornam o uso do dashboard mais ágil no dia a dia

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                                                                                                            | Prioridade | Estimativa |
|-----|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|------------|
| 6   | Eu, como gestor de equipes, quero ver as rotas históricas e as rotas otimizadas lado a lado no mapa, para planejar melhor a alocação das equipes nos próximos ciclos    | Alta       | 20         |
| 7   | Eu, como gestor de equipes, quero ver como a carga de trabalho ficaria distribuída entre as equipes no cenário otimizado, para avaliar se a divisão está equilibrada    | Alta       | 8          |
| 8   | Eu, como gestor de equipes, quero simular um cenário alterando parâmetros simples (ex: nº de equipes), para testar diferentes formas de alocar minha equipe             | Alta       | 8          |
| 9   | Eu, como usuário, quero salvar atalhos (bookmarks) para as visões mais usadas do dashboard, para navegar mais rápido entre análises                                     | Baixa      | 3          |
| 10  | Eu, como usuário, quero ver uma transição animada ao alternar entre rota histórica e rota otimizada no mapa, para perceber mais claramente a diferença entre as duas    | Baixa      | 2          |

> **Observação:** IDs mantidos consistentes com o backlog completo do projeto (US6–US10 correspondem às histórias da Sprint 2).

---

## 📅 Sprint(s) Relacionadas
| Sprint          | Entregas Principais                                                                                                                                           | Status        |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|
| 01              | US1 – Mapa com locais das fiscalizações; US2 – Indicadores básicos; US3 – Filtros por município e tipo; US4 – Tooltip com detalhes; US5 – Tema claro/escuro | Concluído     |
| 02 *(este MVP)* | US6 – Rotas históricas x otimizadas; US7 – Distribuição de carga de trabalho simulada; US8 – Simulação de cenário (nº de equipes); US9 – Bookmarks; US10 – Transição animada | Em andamento  |
| 03              | US11 a US18 – Comparativo real x otimizado, indicadores completos, exportação de relatórios, simulação avançada, resumo automático, apresentação, alertas e snapshot | Planejado     |

---

## 📊 Critérios de Aceitação
- O sistema deve exibir, no mesmo mapa, a rota histórica e a rota otimizada de forma visualmente distinguível (US6)
- O sistema deve calcular e exibir a distribuição de carga de trabalho entre as equipes no cenário otimizado (US7)
- O usuário deve conseguir alterar o número de equipes em um cenário simulado e visualizar o resultado atualizado sem recarregar a página (US8)
- O usuário deve conseguir salvar, nomear e acessar bookmarks de visões do dashboard (US9)
- Ao alternar entre rota histórica e otimizada, o sistema deve exibir uma transição animada perceptível, sem impacto significativo no tempo de resposta (US10)
- Métricas coletadas: tempo de execução da simulação, frequência de uso de bookmarks, nº de cenários simulados por gestor

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
