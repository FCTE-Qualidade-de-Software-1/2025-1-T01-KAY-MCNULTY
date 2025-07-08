# Gestão do Projeto com Métricas PSM/CID

**Projeto:** AgroMart  
**Disciplina:** FGA0315 - Qualidade de Software 1  
**Turma:** 01  
**Equipe:** Kay McNulty  
**Período:** 2025/1

Este documento apresenta a aplicação de métricas de acompanhamento do projeto _AgroMart_ com base no modelo **PSM/CID**, abrangendo as categorias:

- Desempenho dos Processos
- Calendário e Progresso
- Recursos e Custos

---

##  1. Calendário / Cronograma / Prazo

**Objetivo:** Avaliar a conformidade com o cronograma definido.  
**Métrica:** Conformidade com datas de entrega.  
**Como medir:** Checklist de datas planejadas vs. datas reais.

###  Checklist de Entregas

Março  
[x] 24/03 – Apresentação do Plano de Ensino  
[x] 26/03 – Formação das equipes

Abril  
[x] 07 e 09/04 – Não tem aula  
[x] 21/04 – Feriado  
[x] 24 a 30/04 – TAU1

Maio  
[x] 19/05 – PC1  
[x] 21/05 – EU1 / AP1  
[x] 28/05 a 02/06 – TAU2

Junho  
[x] 04/06 – PC2  
[x] 11/06 – EU2 / AP2  
[x] 25/06 – Desenvolvimento do Projeto  
[x] 30/06 – Continuação

Julho  
[x] 02/07 – PC Final  
[x] 07/07 – EU3 (Entrega da Unidade 3)  
[x] 07/07 – Ponto de Controle Final  
[x] 08/07 – Entrega Final  
[ ] 09/07 – Apresentação Final  
[ ] 10–13/07 – TAU3  
[ ] 14/07 – Apresentação Extra  
[ ] 16/07 – TAG + Avaliação por Pares  
[ ] 21/07 – Prova Substitutiva  
[ ] 23/07 – Revisão de Notas  
[ ] 28/07 – Revisão Final

**Conclusão:** 11 de 13 marcos principais cumpridos até 08/07 → **85% de conformidade**

---

##  2. Desempenho / Performance

**Objetivo:** Avaliar se as entregas foram realizadas corretamente e conforme as especificações.  
**Métrica:** Aderência às instruções da docente.  
**Como medir:** Verificação da entrega versus critérios (conteúdo, formato, prazo).

###  Fase 1: Estabelecer Requisitos de Avaliação

[x] Estabelecer propósito  
[x] Identificar produtos  
[x] Especificar modelo de qualidade (PSM)

###  Fase 2: Especificar a Avaliação

[x] Seleção de métricas GQM  
[x] Objetivo claro  
[x] Perguntas e hipóteses  
[x] Critérios e níveis  
[x] Gráfico GQM

###  Fase 3: Projetar a Avaliação

[x] Plano de avaliação  
[x] Cronograma  
[x] Responsáveis

###  Fase 4: Executar a Avaliação

[x] Coleta de dados (quantitativos e qualitativos)  
[x] Julgamento e melhorias (protótipo + proposta de melhoria)

**Conclusão:** 100% de tarefas entregues corretamente

---

##  3. Aplicação de Métricas PSM/CID

###  Cumulative Flow Diagram

<canvas id="cfdChart" width="600" height="300"></canvas>

###  Burndown Chart

<canvas id="burndownChart" width="600" height="300"></canvas>

###  Committed vs. Completed

<canvas id="commitChart" width="600" height="300"></canvas>

###  Cycle Time

<canvas id="cycleChart" width="600" height="300"></canvas>

---

##  4. Recursos e Custos

### a) Equipe e Ferramentas

| Categoria                  | Ferramenta / Recurso              | Observação                         |
| -------------------------- | --------------------------------- | ---------------------------------- |
| Versionamento              | Git + GitHub                      | Histórico de commits e organização |
| Documentação base          | ISO/IEC, GQM, PSM                 | Diretrizes para o projeto          |
| Avaliação de Qualidade     | GQM + PSM/CID                     | Modelos utilizados                 |
| Editor de documentos       | Google Docs                       | Produção colaborativa              |
| Prototipação               | Figma                             | Representação das telas            |
| Slides                     | Canva                             | Apresentações finais               |
| Organização de tarefas     | Canvas + GitHub Projects          | Kanban e To-do                     |
| Medições                   | Chart.js                          | Visualização de métricas           |
| Acessibilidade/Usabilidade | TalkBack + heurísticas de Nielsen | Testes internos                    |

**Conclusão:** 100% das ferramentas planejadas utilizadas

---

### b) Estimativa de Custos (Simulada)

| Item                      | Valor Unitário | Qtde | Total (R$)       |
| ------------------------- | -------------- | ---- | ---------------- |
| Mão de obra (320h x R$10) | R$ 3.200,00    | 5    | R$ 16.000,00     |
| Internet                  | R$ 600,00      | 5    | R$ 3.000,00      |
| Equipamentos              | R$ 3.000,00    | 5    | R$ 15.000,00     |
| **Total Geral**           | —              | —    | **R$ 34.000,00** |


---

## Indicadores Visuais de Desempenho da Sprint

A seguir são apresentados os principais gráficos utilizados para análise do desempenho da equipe de desenvolvimento do sistema **AgroMart** durante os ciclos de sprint. Os dados foram coletados manualmente a partir do acompanhamento do quadro Kanban e das ferramentas de versionamento utilizadas.

---

### 1. Gráfico de Fluxo Cumulativo (CFD)

Este gráfico representa a evolução das tarefas ao longo dos dias da Sprint 1, separadas por status:

| Dia | To Do | In Progress | Done |
|-----|-------|-------------|------|
| 1   | 9     | 7           | 0    |
| 2   | 7     | 5           | 2    |
| 3   | 5     | 3           | 4    |
| 4   | 2     | 1           | 7    |

**Observações**:
- Há uma redução progressiva nas tarefas "To Do", indicando avanço no fluxo.
- O número de tarefas "Done" cresceu de 0 para 7 ao final da Sprint.
- Isso demonstra um bom controle de WIP (Work in Progress) e estabilidade de entrega.

---

### 2. Gráfico de Burndown

Este gráfico compara o trabalho **planejado** com o trabalho **real** concluído na Sprint 1:

| Dia | Planejado | Real |
|-----|-----------|------|
| 1   | 20        | 20   |
| 2   | 16        | 17   |
| 3   | 12        | 15   |
| 4   | 8         | 12   |
| 5   | 0         | 10   |

**Observações**:
- O time permaneceu acima da linha planejada, indicando atrasos na finalização.
- Embora a linha real não tenha atingido o zero, houve progresso contínuo.

---

### 3. Gráfico de Comprometimento vs Conclusão

Comparação entre tarefas comprometidas e efetivamente entregues por sprint:

| Sprint  | Comprometido | Concluído |
|---------|--------------|-----------|
| Sprint 1 | 15           | 13        |
| Sprint 2 | 18           | 16        |
| Sprint 3 | 20           | 19        |

**Observações**:
- Há alta aderência entre o planejado e o realizado.
- Demonstra capacidade de estimativa e comprometimento da equipe.

---

### 4. Gráfico de Cycle Time

Tempo médio (em dias) para finalização de cada tarefa:

| Tarefa    | Cycle Time (dias) |
|-----------|-------------------|
| Tarefa 1  | 2                 |
| Tarefa 2  | 3                 |
| Tarefa 3  | 1                 |
| Tarefa 4  | 4                 |

**Observações**:
- A maioria das tarefas foi concluída entre 1 e 3 dias.
- A variação no tempo pode indicar diferenças na complexidade ou no tamanho das histórias.

---

**Conclusão**:  
A análise gráfica evidencia que, apesar de pequenos desvios entre o trabalho planejado e realizado, o time teve um desempenho estável ao longo da Sprint 1. A visualização dos dados possibilita ajustes estratégicos para as próximas sprints, principalmente no planejamento de capacidade e balanceamento de tarefas.

---
##  Tabela de Contribuição

| Nome completo                          | Contribuição (%) |
|----------------------------------------|------------------|
| [Júlia Massuda](http://github.com/JuliaReis18)                | 20%               |
| [Diogo Ferreira](https://github.com/fdiogo1)                  | 20%                |
| [Eduardo](http://github.com/Eduard0803)        | 20%                 |
| [Camile](http://github.com/Camile0318   )       | 20%                 |
| [Bruno Duarte]( https://github.com/bbduarte )                   | 20%                 |
---



## Histórico de versões

| Versão | Data       | Descrição                   | Autor          | Revisor     |
|--------|------------|-----------------------------|----------------|-------------|
| 1.0    | 08/07/2025 | Criação do documento de gestão     | [Bruno Duarte]( https://github.com/bbduarte )   | -   |
| 1.1   | 08/07/2025 | Organizando o padrão de estruturação da página   | [Júlia Massuda](http://github.com/JuliaReis18)   | -   |

