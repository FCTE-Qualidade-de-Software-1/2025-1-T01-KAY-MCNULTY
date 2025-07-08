# 📊 Gestão do Projeto com Métricas PSM/CID

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

## ✅ 1. Calendário / Cronograma / Prazo

**Objetivo:** Avaliar a conformidade com o cronograma definido.  
**Métrica:** Conformidade com datas de entrega.  
**Como medir:** Checklist de datas planejadas vs. datas reais.

### 📅 Checklist de Entregas

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

## ⚙️ 2. Desempenho / Performance

**Objetivo:** Avaliar se as entregas foram realizadas corretamente e conforme as especificações.  
**Métrica:** Aderência às instruções da docente.  
**Como medir:** Verificação da entrega versus critérios (conteúdo, formato, prazo).

### ✔️ Fase 1: Estabelecer Requisitos de Avaliação

[x] Estabelecer propósito  
[x] Identificar produtos  
[x] Especificar modelo de qualidade (PSM)

### ✔️ Fase 2: Especificar a Avaliação

[x] Seleção de métricas GQM  
[x] Objetivo claro  
[x] Perguntas e hipóteses  
[x] Critérios e níveis  
[x] Gráfico GQM

### ✔️ Fase 3: Projetar a Avaliação

[x] Plano de avaliação  
[x] Cronograma  
[x] Responsáveis

### ✔️ Fase 4: Executar a Avaliação

[x] Coleta de dados (quantitativos e qualitativos)  
[x] Julgamento e melhorias (protótipo + proposta de melhoria)

**Conclusão:** 100% de tarefas entregues corretamente

---

## 📈 3. Aplicação de Métricas PSM/CID

### 🔷 Cumulative Flow Diagram

<canvas id="cfdChart" width="600" height="300"></canvas>

### 🔷 Burndown Chart

<canvas id="burndownChart" width="600" height="300"></canvas>

### 🔷 Committed vs. Completed

<canvas id="commitChart" width="600" height="300"></canvas>

### 🔷 Cycle Time

<canvas id="cycleChart" width="600" height="300"></canvas>

---

## 👥 4. Recursos e Custos

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

## 👤 5. Tabela de Contribuição dos Integrantes

| Matrícula | Nome do Integrante | Contribuição (%) |
| --------- | ------------------ | ---------------- |
| 242034483 | Bruno Duarte       | 20%              |
| 251035022 | Camile Oliveira    | 20%              |
| 221008570 | Diogo Ferreira     | 20%              |
| 221008580 | Eduardo Silva      | 20%              |
| 231035150 | Júlia Reis         | 20%              |

---

<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<script>
const cfdCtx = document.getElementById('cfdChart').getContext('2d');
new Chart(cfdCtx, {
  type: 'line',
  data: {
    labels: ['Dia 1', 'Dia 2', 'Dia 3', 'Dia 4'],
    datasets: [
      {
        label: 'To Do',
        data: [9, 7, 5, 2],
        borderColor: '#b0bec5',
        backgroundColor: 'rgba(176,190,197,0.3)',
        fill: true,
        tension: 0.3
      },
      {
        label: 'In Progress',
        data: [7, 5, 3, 1],
        borderColor: '#ffa726',
        backgroundColor: 'rgba(255,167,38,0.3)',
        fill: true,
        tension: 0.3
      },
      {
        label: 'Done',
        data: [0, 2, 4, 7],
        borderColor: '#66bb6a',
        backgroundColor: 'rgba(102,187,106,0.3)',
        fill: true,
        tension: 0.3
      }
    ]
  },
  options: {
    responsive: true,
    plugins: {
      title: { display: true, text: 'Cumulative Flow - Sprint 1' },
      legend: { position: 'bottom' }
    },
    scales: {
      y: { beginAtZero: true, title: { display: true, text: 'Tarefas' } },
      x: { title: { display: true, text: 'Dias' } }
    }
  }
});

const burndownCtx = document.getElementById('burndownChart').getContext('2d');
new Chart(burndownCtx, {
  type: 'line',
  data: {
    labels: ['Dia 1', 'Dia 2', 'Dia 3', 'Dia 4', 'Dia 5'],
    datasets: [
      {
        label: 'Planejado',
        data: [20, 16, 12, 8, 0],
        borderColor: '#90caf9',
        tension: 0.4
      },
      {
        label: 'Real',
        data: [20, 17, 15, 12, 10],
        borderColor: '#f44336',
        tension: 0.4
      }
    ]
  },
  options: {
    plugins: {
      title: { display: true, text: 'Burndown Chart - Sprint 1' },
      legend: { position: 'bottom' }
    },
    scales: {
      y: { beginAtZero: true, title: { display: true, text: 'Tarefas Restantes' } }
    }
  }
});

const commitCtx = document.getElementById('commitChart').getContext('2d');
new Chart(commitCtx, {
  type: 'bar',
  data: {
    labels: ['Sprint 1', 'Sprint 2', 'Sprint 3'],
    datasets: [
      {
        label: 'Comprometido',
        data: [15, 18, 20],
        backgroundColor: '#42a5f5'
      },
      {
        label: 'Concluído',
        data: [13, 16, 19],
        backgroundColor: '#66bb6a'
      }
    ]
  },
  options: {
    plugins: {
      title: { display: true, text: 'Committed vs Completed' },
      legend: { position: 'bottom' }
    },
    responsive: true,
    scales: {
      y: { beginAtZero: true, title: { display: true, text: 'Tarefas' } }
    }
  }
});

const cycleCtx = document.getElementById('cycleChart').getContext('2d');
new Chart(cycleCtx, {
  type: 'bar',
  data: {
    labels: ['Tarefa 1', 'Tarefa 2', 'Tarefa 3', 'Tarefa 4'],
    datasets: [{
      label: 'Cycle Time (dias)',
      data: [2, 3, 1, 4],
      backgroundColor: '#ab47bc'
    }]
  },
  options: {
    plugins: {
      title: { display: true, text: 'Cycle Time por Tarefa' },
      legend: { display: false }
    },
    scales: {
      y: { beginAtZero: true, title: { display: true, text: 'Dias' } }
    }
  }
});
</script>
