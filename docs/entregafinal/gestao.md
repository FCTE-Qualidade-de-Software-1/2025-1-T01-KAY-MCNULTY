# Gestão do Projeto com Métricas PSM/CID

**Projeto:** AgroMart  
**Disciplina:** FGA0315 - Qualidade de Software 1  
**Turma:** 01  
**Equipe:** Kay McNulty  
**Período:** 2025/1

---

## Avaliação da Qualidade do AGROMART
**Objetivo:** Avaliar se as entregas foram realizadas corretamente e conforme as especificações.  
**Métrica:** Adequação aos temas ministrados em sala.  

###  Fase 1: Estabelecer Requisitos de Avaliação

A avaliação do projeto AgroMart tem como objetivo central garantir que o produto final atenda aos parâmetros de qualidade e às expectativas estabelecidas. Para isso, utilizamos o PSM (Practical Software Measurement), uma ferramenta de gestão que proporciona uma visão clara e objetiva do status e da saúde do projeto. O PSM ajuda a identificar áreas de otimização, facilitando a tomada de decisões e assegurando que o software AgroMart atinja os padrões de qualidade desejados.


###  Fase 2: Especificar a Avaliação

No contexto da avaliação do projeto, a fase de especificação da avaliação é útil para a seleção estratégica das métricas GQM (Goal-Question-Metric) e para garantir que estamos medindo o que realmente importa. Objetivamente, formulamos perguntas e hipóteses detalhadas que direcionam nossa coleta de dados. Em seguida, definimos critérios e níveis para interpretar os resultados e, por fim, visualizamos essa estrutura complexa em um Gráfico GQM, proporcionando uma visão coesa de como a qualidade será avaliada.

###  Fase 3: Projetar a Avaliação

Esta fase do projeto AgroMart detalha o Plano de Avaliação, que guiará a análise de qualidade do sistema focando em usabilidade e confiabilidade. Utilizando métricas pré-definidas e o método "pensar em voz alta" com usuários em cenários reais, a equipe coletará dados quantitativos e qualitativos. O sucesso será medido se 70% das métricas atingirem níveis "Bom" ou "Excelente", visando aprimorar continuamente a experiência do usuário do AgroMart.

###  Fase 4: Executar a Avaliação

A avaliação de compatibilidade do AgroMart, na Fase 4 (Q1), focou em garantir o funcionamento consistente do sistema em Chrome, Firefox e Edge. Com uma hipótese de 100% de sucesso, testes manuais e automatizados revelaram uma compatibilidade geral de 99,3%. Embora o sistema apresente alta performance e layout consistente, uma pequena distorção no Firefox foi identificada, indicando uma área para melhoria contínua.

**Conclusão:** Todas as fases foram percorridas adequadamente.

---

## Gestão do Projeto com Métricas PSM/CID

O **PSM (Practical Software Measurement)** é um modelo de medição que oferece uma abordagem estruturada para coletar e analisar dados de projetos de software, visando **melhorar processos e produtos**. Ele foca em métricas práticas de **tamanho, esforço, cronograma, qualidade e desempenho de processos**. O termo **CID** é frequentemente adicionado para reforçar o foco em **custo, informações e desempenho (Cost, Information, and Performance Data)**, enfatizando a importância de coletar e usar dados acionáveis para otimizar a gestão e os resultados do projeto.

---

### 1. Abordagem de Avaliação PSM/CID no AgroMart

Ao utilizarmos o **PSM/CID** em conjunto, priorizamos a coleta e análise de dados que impactam diretamente o custo, a qualidade das informações e o desempenho real dos processos e do produto. Isso assegura que a medição seja uma ferramenta prática para aprimorar a entrega do projeto. O **PSM** define "como medir" e organiza as categorias, enquanto o **CID** destaca "o que é mais crítico medir" nessas categorias, garantindo que as informações de custo, dados e performance estejam sempre disponíveis para uma tomada de decisão eficaz.

---

### 2. Como o PSM Guia a Medição de Performance no AgroMart

O PSM oferece a estrutura essencial para avaliarmos o desempenho do AgroMart de forma sistemática e relevante, focando em informações que realmente importam para o sucesso do projeto.

#### 2.1. Foco em Propósitos e Perguntas (GQM - Goal-Question-Metric) no AgroMart

No AgroMart, o paradigma **GQM** é a base para definir o que e como medir:

* **Goals (Objetivos) no AgroMart:**
    * **Melhorar a Eficiência da Entrega:** Reduzir o tempo que as tarefas levam para serem concluídas desde a concepção até a finalização.
    * **Garantir a Qualidade do Produto:** Assegurar que as funcionalidades desenvolvidas atendam aos requisitos e apresentem poucos defeitos.
    * **Manter o Cronograma:** Cumprir os marcos e entregas planejados para o projeto.

* **Questions (Perguntas) para o AgroMart:**
    * **Para "Melhorar a Eficiência da Entrega":**
        * Qual é o **tempo médio de ciclo** das nossas histórias de usuário ou tarefas?
        * Qual é a nossa **vazão** (throughput) de tarefas concluídas por sprint?
        * Temos gargalos no nosso fluxo de trabalho (como mostra o CFD)?
    * **Para "Garantir a Qualidade do Produto":**
        * Quantos **defeitos** são encontrados durante os testes de usabilidade e compatibilidade (Fase 4)?
        * Qual a **taxa de sucesso** nos testes de funcionalidade e compatibilidade?
        * As entregas estão aderindo 100% às instruções da docente?
    * **Para "Manter o Cronograma":**
        * Estamos dentro ou fora do **cronograma planejado** (como mostra o Burndown Chart)?
        * Qual o **percentual de conformidade** com as datas de entrega dos marcos?
        * Nossa capacidade de **comprometimento versus conclusão** é consistente ao longo das sprints?

* **Metrics (Métricas) para o AgroMart:**
    * **Para Eficiência:** `Cycle Time Médio (em dias)`, `Número de Tarefas/Histórias Concluídas por semana`.
    * **Para Qualidade:** `Número de Defeitos Reportados pós-teste`, `Percentual de Sucesso em Testes de Compatibilidade/Usabilidade`, `Percentual de Aderência aos Critérios de Entrega`.
    * **Para Cronograma:** `Desvio da Linha Real em relação à Planejada no Burndown Chart`, `Percentual de Marcos Entregues no Prazo`, `Razão entre Tarefas Comprometidas e Concluídas`.

#### 2.2. Categorias de Medição Definidas no AgroMart

Aplicamos as cinco categorias do PSM para ter uma visão completa:

* **Tamanho:** No AgroMart, poderíamos estimar o **Tamanho das Histórias de Usuário** (e.g., em Pontos de História, se utilizarmos Scrum) ou o número de requisitos funcionais implementados.
* **Esforço e Custo:** Medimos as **Horas de trabalho investidas** pela equipe (ex: 60h por membro) e o **Custo total simulado** (R$ 173.750,00), acompanhando o orçamento.
* **Cronograma:** Avaliamos a **Conformidade com Datas de Entrega** (seu checklist de 85%) e o progresso das sprints através do **Burndown Chart**.
* **Qualidade:** Verificamos a **Aderência às Instruções da Docente** (100% de conformidade) e a **Compatibilidade em Diferentes Navegadores** (99,3% de sucesso no Q1 da Fase 4).
* **Desempenho dos Processos:** Analisamos o **Cumulative Flow Diagram (CFD)** para entender o fluxo de trabalho e WIP, o **Burndown Chart** para a taxa de progresso, o **Committed vs. Completed** para a capacidade de entrega e o **Cycle Time** para a eficiência da finalização de tarefas.

#### 2.3. Foco em Dados Acionáveis para o AgroMart

Para o AgroMart, as métricas devem gerar informações que nos permitam agir:

* A distorção no Firefox (Q1) leva à ação de **corrigir o CSS/layout**.
* O Burndown acima da linha planejada nos leva a **reavaliar as estimativas** ou identificar impedimentos.
* Um aumento no Cycle Time pode nos levar a **revisar o fluxo** de trabalho ou a complexidade das tarefas.

#### 2.4. Ciclo de Medição Contínua no AgroMart

A avaliação do AgroMart não é um evento único, mas um ciclo:

1.  **Planejar:** Definir os objetivos de cada fase e as métricas para avaliá-las (como feito nas Fases 1 e 2).
2.  **Coletar:** Registrar os dados dos testes de usabilidade, compatibilidade, acompanhamento do Kanban e GitHub (como descrito na Fase 3 e 4).
3.  **Analisar:** Interpretar os gráficos (CFD, Burndown, etc.) e os resultados dos testes (ex: 99,3% de compatibilidade).
4.  **Agir:** Implementar melhorias no código, no processo de estimativa ou no gerenciamento de tarefas com base nas conclusões.
5.  **Aprender:** Documentar os resultados e as lições aprendidas em cada fase e sprint para refinar abordagens futuras do projeto.

Ao aplicar o PSM dessa forma, o projeto AgroMart não só mede seu progresso, mas também obtém insights valiosos para otimizar continuamente seu desenvolvimento e garantir a entrega de um produto de alta qualidade.

---

### 3. Como o CID Age no Contexto do AgroMart

O **CID** atua como uma lente que **prioriza e destaca as informações mais críticas** para a gestão do projeto, complementando o "como medir" do PSM.

#### 3.1. Cost (Custo) no AgroMart

O CID foca na **eficiência dos recursos financeiros e de mão de obra** do AgroMart:

* **Comparar o Real vs. Orçado:** Analisaria se as 320 horas de mão de obra por membro e o custo de R$ 34.000,00 estão sendo utilizados conforme o planejado e se geram o retorno esperado.
* **Identificar Desperdícios:** Observaria horas extras não justificadas, retrabalho excessivo (falhas de qualidade que geram custo adicional) ou uso ineficiente de ferramentas.
* **Análise de ROI (Retorno sobre Investimento) Simplificada:** Mesmo que simulado, o CID incentivaria a pensar se o investimento simulado está gerando as entregas e a qualidade esperadas.

#### 3.2. Information (Informação) no AgroMart

O CID avalia a **qualidade e a disponibilidade dos dados de gestão** do AgroMart:

* **Clareza e Pontualidade dos Relatórios:** Verificaria se os relatórios (como seu documento de gestão) são fáceis de entender, completos e gerados a tempo para a tomada de decisão.
* **Integridade dos Dados:** Checaria se os dados coletados (do Kanban, GitHub) são precisos e consistentes. Inconsistências (ex: no Burndown) podem indicar problemas de dados ou processo.
* **Acesso à Informação:** Avaliaria se a equipe e stakeholders têm acesso fácil às métricas e relatórios importantes.

#### 3.3. Performance Data (Dados de Desempenho) no AgroMart

Esta parte alinha-se com suas métricas, mas o CID as enfatiza sob uma ótica de "impacto crítico":

* **Velocidade e Qualidade da Entrega:** Analisaria os dados do seu **Cycle Time**, **Burndown** e **Committed vs. Completed** como indicadores diretos da capacidade de entrega e da qualidade do produto.
* **Eficiência do Fluxo de Trabalho:** Observaria o **Cumulative Flow Diagram (CFD)** para identificar rapidamente se o WIP está aumentando descontroladamente ou se há gargalos persistentes, impactando diretamente a performance.

---

### 4. Pontos Críticos Apontados pelo CID no AgroMart

Com base nos dados que você já apresentou, o CID apontaria os seguintes pontos como **críticos ou de atenção imediata**:

1.  **Desalinhamento no Burndown Chart (Performance Data):**
    * **Ponto Crítico:** Sua observação de que "o time permaneceu acima da linha planejada, indicando atrasos na finalização".
    * **Por que é Crítico:** Sugere estimativas irrealistas, impedimentos não resolvidos ou capacidade da equipe superestimada. Isso afeta diretamente o **cronograma** e, potencialmente, o **custo**, impactando a **previsibilidade e controle do projeto**.

2.  **Pequena Distorção em Modal no Firefox (Performance Data / Qualidade):**
    * **Ponto Crítico:** A falha de 2% no Firefox.
    * **Por que é Crítico:** Mesmo pequena, falhas de layout podem impactar a **usabilidade** e **experiência do usuário**. O CID destacaria que problemas de qualidade que afetam a interação do usuário precisam de correção para manter a **percepção de qualidade do produto** e evitar **custos futuros de manutenção**.

3.  **Variação no Cycle Time (Performance Data):**
    * **Ponto Crítico:** A Tarefa 4 levou 4 dias, enquanto a maioria ficou entre 1-3 dias.
    * **Por que é Crítico:** O CID buscaria a razão dessa variação. Um *cycle time* inconsistente pode indicar tarefas mal compreendidas, bloqueios intermitentes ou fluxo de trabalho não fluido, impactando a **previsibilidade** e **eficiência** do processo de entrega.

4.  **Uso Eficiente do Orçamento Simulado (Cost):**
    * **Ponto Crítico (a ser monitorado):** O CID questionaria: "Estamos obtendo o máximo de valor desse investimento?"
    * **Por que é Crítico:** Se o Burndown continuar atrasado, mas o custo for mantido, isso pode indicar baixa produtividade ou valor por hora investida.

---

### 5. Indicadores Visuais de Desempenho da Sprint

A seguir são apresentados os principais gráficos utilizados para análise do desempenho da equipe de desenvolvimento do sistema **AgroMart** durante os ciclos de sprint. Os dados foram coletados manualmente a partir do acompanhamento do quadro Kanban e das ferramentas de versionamento utilizadas.

#### 5.1. Gráfico de Fluxo Cumulativo (CFD)

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

#### 5.2. Gráfico de Burndown

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

#### 5.3. Gráfico de Comprometimento vs Conclusão

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

#### 5.4. Gráfico de Cycle Time

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



**Conclusão**:  
A análise gráfica evidencia que, apesar de pequenos desvios entre o trabalho planejado e realizado, o time teve um desempenho estável ao longo da Sprint 1. A visualização dos dados possibilita ajustes estratégicos para as próximas sprints, principalmente no planejamento de capacidade e balanceamento de tarefas.

---

##  2. Calendário / Cronograma / Prazo

**Objetivo:** Obter um planejamento adequado com as datas de entrega.  
**Métrica:** Conformidade com datas de entrega.  

### Calendário de Entregas do Projeto AgroMart

Este calendário visualiza as principais entregas e marcos do projeto AgroMart.

#### Março de 2025

| Dom | Seg | Ter | Qua | Qui | Sex | Sáb |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|     |     |     |     |     |     | 1   |
| 2   | 3   | 4   | 5   | 6   | 7   | 8   |
| 9   | 10  | 11  | 12  | 13  | 14  | 15  |
| 16  | 17  | 18  | 19  | 20  | 21  | 22  |
| 23  | **24** | **25** | **26** | 27  | 28  | 29  |
| 30  | 31  |     |     |     |     |     |

* **24/03** – Apresentação do Plano de Ensino
* **26/03** – Formação das equipes

---

#### Abril de 2025

| Dom | Seg | Ter | Qua | Qui | Sex | Sáb |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|     |     | 1   | 2   | 3   | 4   | 5   |
| 6   | **7** | 8   | **9** | 10  | 11  | 12  |
| 13  | 14  | 15  | 16  | 17  | 18  | 19  |
| 20  | **21** | 22  | 23  | **24** | **25** | **26** |
| **27** | **28** | **29** | **30** |     |     |     |

* **07/04 e 09/04** – Não tem aula
* **21/04** – Feriado
* **24 a 30/04** – TAU1 (Teste de Aceitação do Usuário 1)

---

#### Maio de 2025

| Dom | Seg | Ter | Qua | Qui | Sex | Sáb |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|     |     |     |     | 1   | 2   | 3   |
| 4   | 5   | 6   | 7   | 8   | 9   | 10  |
| 11  | 12  | 13  | 14  | 15  | 16  | 17  |
| 18  | **19** | 20  | **21** | 22  | 23  | 24  |
| 25  | 26  | 27  | **28** | **29** | **30** | **31** |

* **19/05** – PC1 (Ponto de Controle 1)
* **21/05** – EU1 / AP1 (Entrega da Unidade 1 / Apresentação 1)
* **28/05 a 02/06** – TAU2 (Teste de Aceitação do Usuário 2 - **continua em junho**)

---

#### Junho de 2025

| Dom | Seg | Ter | Qua | Qui | Sex | Sáb |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1   | **2** | 3   | **4** | 5   | 6   | 7   |
| 8   | 9   | 10  | **11** | 12  | 13  | 14  |
| 15  | 16  | 17  | 18  | 19  | 20  | 21  |
| 22  | 23  | 24  | **25** | 26  | 27  | 28  |
| 29  | **30** |     |     |     |     |     |

* **02/06** – Continuação de TAU2
* **04/06** – PC2 (Ponto de Controle 2)
* **11/06** – EU2 / AP2 (Entrega da Unidade 2 / Apresentação 2)
* **25/06** – Desenvolvimento do Projeto
* **30/06** – Continuação do Desenvolvimento

---

#### Julho de 2025

| Dom | Seg | Ter | Qua | Qui | Sex | Sáb |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|     |     | 1   | **2** | 3   | 4   | 5   |
| 6   | **7** | **8** | **9** | **10** | **11** | **12** |
| **13** | **14** | 15  | **16** | 17  | 18  | 19  |
| 20  | **21** | 22  | **23** | 24  | 25  | 26  |
| 27  | **28** | 29  | 30  | 31  |     |     |

* **02/07** – PC Final (Ponto de Controle Final)
* **07/07** – EU3 (Entrega da Unidade 3)
* **07/07** – Ponto de Controle Final
* **08/07** – Entrega Final
* **09/07** – Apresentação Final
* **10–13/07** – TAU3 (Teste de Aceitação do Usuário 3)
* **14/07** – Apresentação Extra
* **16/07** – TAG + Avaliação por Pares
* **21/07** – Prova Substitutiva
* **23/07** – Revisão de Notas
* **28/07** – Revisão Final

**Conclusão:** As entregas foram realizadas em conformidade com o calendário.

---

##  3. Recursos e Custos

### a) Equipe e Ferramentas

| Categoria                  | Ferramenta / Recurso              | Observação                         |
| -------------------------- | --------------------------------- | ---------------------------------- |
| Versionamento              | Git + GitHub                      | Histórico de commits e organização |
| Documentação base          | ISO/IEC, GQM, PSM,Template da Disciplina de Qualidade de Software             | Diretrizes para o projeto          |
| Avaliação de Qualidade     | GQM + PSM/CID                     | Modelos utilizados                 |
| Editor de documentos       | Vscode e Vim                       | Produção colaborativa              |
| Simulação               | Gitpage                            | Representação das telas            |
| Slides                     | Canva                             | Apresentações finais               |

**Conclusão:** A utilização de ferramentas adequadas viabiliza o desenvolvimento do projeto.

---

### b) Estimativa de Custos (Simulada)

| Item                      | Valor Unitário | Qtde | Total (R$)       |
| ------------------------- | -------------- | ---- | ---------------- |
| Mão de obra (300h x R$20) | R$ 6.000,00    | 5    | R$ 30.000,00     |
| Internet                  | R$ 750,00      | 5    | R$ 3.750,00      |
| Equipamentos              | R$ 10.000,00    | 5    | R$ 50.000,00     |
| **Total Geral**           | —              | —    | **R$ 83.750,00** |

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

## 📝 Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Revisor(es) |
| ------ | ---- | --------- | --------- | ----------- |
| 1.0    | 08/07/2025 | Criação do documento de gestão     | [Bruno Duarte]( https://github.com/bbduarte ) | [Eduardo Belarmino](https://github.com/eduard0803) | 
| 1.1   | 08/07/2025 | Organizando o padrão de estruturação da página   | [Júlia Massuda](http://github.com/JuliaReis18) | [Eduardo Belarmino](https://github.com/eduard0803) | 

