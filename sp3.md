# 📌 MVP - Painel de Fiscalização de Equipes (Sprint 3 – Comparativos, Exportação e Refinamentos)

## 🎯 Objetivo do MVP
> Descrever de forma clara qual é o propósito do MVP:

- **Qual problema resolve?** Após validar a visualização geográfica (Sprint 1) e a simulação básica de cenários (Sprint 2), falta aos analistas e gestores uma forma de quantificar os ganhos obtidos com a otimização, refinar a simulação com mais critérios e compartilhar esses resultados formalmente com a diretoria do IPEM.
- **Qual hipótese será validada?** Se o dashboard oferecer comparação quantitativa entre cenário real e otimizado, simulação com parâmetros avançados e exportação de relatórios/snapshots, o produto passará de uma ferramenta de análise individual para um instrumento de apoio à decisão e comunicação institucional.
- **Qual valor será entregue ao usuário final?** Capacidade de mensurar e comunicar ganhos de eficiência, mais flexibilidade no planejamento de alocação e uma experiência de uso mais completa (resumos automáticos, alertas, modo apresentação e compartilhamento rápido).

---

## 📝 Descrição da Solução
> Breve explicação do que será desenvolvido e entregue nesta etapa.

Esta é a etapa final do MVP, que fecha o ciclo iniciado na Sprint 1 (visualização geográfica) e na Sprint 2 (rotas otimizadas e simulação). Aqui o foco é quantificar resultados, refinar a simulação e permitir que os achados sejam exportados e comunicados.

- **Funcionalidades principais incluídas:**
  - Comparativo lado a lado dos indicadores do cenário real e do cenário otimizado
  - Conjunto completo de indicadores de desempenho no dashboard
  - Exportação de relatórios com mapas, indicadores e comparativos
  - Refinamento da simulação de cenários com parâmetros avançados (restrições de equipe, prioridade de município)
  - Resumo automático em texto com os principais insights do período selecionado
  - Modo de apresentação em tela cheia
  - Alertas visuais (cor/ícone) para indicadores fora da faixa esperada
  - Exportação de "snapshot" (imagem) do dashboard com um clique

---

## 👥 Personas / Usuários-Alvo
- **Analista de fiscalização:** precisa quantificar os ganhos de eficiência do modelo otimizado e acompanhar o conjunto completo de indicadores para justificar decisões operacionais com dados
- **Gestor de equipes:** precisa exportar relatórios formais para a diretoria do IPEM e refinar simulações com restrições reais de equipe e prioridade de município antes de aplicar mudanças na operação
- **Usuário:** se beneficia dos recursos que tornam o uso do dashboard mais rápido e comunicável no dia a dia — resumo automático, alertas, apresentação em tela cheia e snapshot

---

## 🔑 User Stories (Backlog do MVP)
| ID  | User Story                                                                                                                                                                | Prioridade | Estimativa |
|-----|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|------------|
| 11  | Eu, como analista de fiscalização, quero comparar lado a lado os indicadores do cenário real e do otimizado, para quantificar os ganhos de eficiência conquistados pelo modelo | Alta       | 8          |
| 12  | Eu, como analista de fiscalização, quero ver o conjunto completo de indicadores de desempenho no dashboard, para acompanhar a eficiência da operação de forma abrangente        | Alta       | 5          |
| 13  | Eu, como gestor de equipes, quero exportar relatórios com mapas, indicadores e comparativos, para compartilhar os resultados do planejamento das equipes com a diretoria do IPEM | Alta       | 5          |
| 14  | Eu, como gestor de equipes, quero refinar a simulação de cenários permitindo ajustar mais parâmetros (restrições de equipe, prioridade de município), para ter mais flexibilidade ao planejar a alocação | Média      | 8          |
| 15  | Eu, como usuário, quero ver um resumo automático em texto destacando os principais insights do período selecionado, para entender rapidamente o que mudou sem ler todos os gráficos | Baixa      | 5          |
| 16  | Eu, como usuário, quero um modo de apresentação em tela cheia, para ter uma experiência mais imersiva ao navegar pelo dashboard                                            | Baixa      | 2          |
| 17  | Eu, como usuário, quero receber alertas visuais (cor/ícone) quando algum indicador sair da faixa esperada, para identificar problemas de forma rápida e intuitiva          | Baixa      | 3          |
| 18  | Eu, como usuário, quero exportar um "snapshot" (imagem) do dashboard com um clique, para compartilhar rapidamente por e-mail ou WhatsApp                                   | Baixa      | 3          |

> **Observação:** IDs mantidos consistentes com o backlog completo do projeto (US11–US18 correspondem às histórias da Sprint 3, etapa final do MVP).

---

## 📅 Sprint(s) Relacionadas
| Sprint          | Entregas Principais                                                                                                                                           | Status        |
|-----------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------|
| 01              | US1 – Mapa com locais das fiscalizações; US2 – Indicadores básicos; US3 – Filtros por município e tipo; US4 – Tooltip com detalhes; US5 – Tema claro/escuro | Concluído     |
| 02              | US6 – Rotas históricas x otimizadas; US7 – Distribuição de carga de trabalho simulada; US8 – Simulação de cenário (nº de equipes); US9 – Bookmarks; US10 – Transição animada | Concluído     |
| 03 *(este MVP)* | US11 – Comparativo real x otimizado; US12 – Indicadores completos; US13 – Exportação de relatórios; US14 – Simulação avançada; US15 – Resumo automático; US16 – Modo apresentação; US17 – Alertas visuais; US18 – Snapshot | Em andamento  |

---

## 📊 Critérios de Aceitação
- O sistema deve exibir os indicadores do cenário real e do cenário otimizado lado a lado, com a diferença percentual/absoluta destacada (US11)
- O dashboard deve apresentar o conjunto completo de indicadores de desempenho definidos para a operação, não apenas os básicos da Sprint 1 (US12)
- O usuário deve conseguir exportar um relatório (mapas, indicadores e comparativos) em um formato compartilhável (ex.: PDF) (US13)
- O sistema deve permitir configurar restrições de equipe e prioridade de município na simulação de cenários, refletindo o resultado atualizado (US14)
- O sistema deve gerar automaticamente um resumo em texto com os principais insights do período selecionado (US15)
- O usuário deve conseguir alternar o dashboard para modo de apresentação em tela cheia, ocultando elementos de navegação (US16)
- O sistema deve destacar visualmente (cor/ícone) qualquer indicador que esteja fora da faixa esperada, definida previamente (US17)
- O usuário deve conseguir gerar e baixar/compartilhar um snapshot em imagem do dashboard com um único clique (US18)
- Métricas coletadas: nº de relatórios exportados, nº de snapshots gerados, frequência de uso do modo apresentação, nº de alertas disparados

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
