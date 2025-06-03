# GQM - Fase de Definição  
**Projeto:** AgroMart  
**Disciplina:** Qualidade de Software 1 (FGA0315)  
**Professora:** Cristiane Ramos  
**Semestre:** 2025-1  

---

## Objetivo de Negócio do AgroMart

O AgroMart tem como objetivo principal facilitar a comercialização de produtos agroecológicos por meio da conexão direta entre agricultores familiares e consumidores, utilizando uma plataforma digital acessível e de fácil uso. A solução foi pensada especialmente para atender produtores com pouca familiaridade tecnológica e atuar como uma alternativa prática durante períodos de isolamento social, como na pandemia da COVID-19.

Com isso, o AgroMart contribui para o fortalecimento da agricultura de base familiar, a valorização do consumo local e a promoção de cadeias sustentáveis de produção e distribuição, alinhando-se aos Objetivos de Desenvolvimento Sustentável da ONU, como ODS 2 (Fome Zero), ODS 3 (Saúde e Bem-Estar) e ODS 12 (Consumo e Produção Responsáveis).

---

## Objetivo de Medição 1 – Usabilidade

**Analisar:** o sistema AgroMart (web e mobile)  
**Para o propósito de:** avaliar a facilidade de uso para agricultores e consumidores  
**Com respeito a:** navegabilidade, clareza de informações e curva de aprendizado  
**Do ponto de vista de:** usuários finais (produtores e consumidores)  
**No contexto de:** testes com usuários com diferentes níveis de familiaridade com tecnologia

### Questões do Objetivo de Medição 1

- **Q1:** Os usuários conseguem cadastrar lojas e produtos sem ajuda externa?  
  **Hipótese Q1:** 80% dos usuários concluem o cadastro sem suporte adicional.

- **Q2:** Os consumidores conseguem encontrar lojas próximas facilmente?  
  **Hipótese Q2:** A maioria dos consumidores localiza uma loja em menos de 2 minutos.

- **Q3:** A interface é compreensível e intuitiva para diferentes públicos?  
  **Hipótese Q3:** Mais de 75% dos usuários avaliam positivamente a interface em testes de usabilidade.

---

## Objetivo de Medição 2 – Compatibilidade

**Analisar:** o sistema AgroMart (web e mobile)  
**Para o propósito de:** garantir funcionamento em diferentes ambientes tecnológicos  
**Com respeito a:** navegadores, sistemas operacionais e dispositivos móveis  
**Do ponto de vista de:** desenvolvedores e equipe de QA  
**No contexto de:** testes automatizados e manuais em múltiplas plataformas

### Questões do Objetivo de Medição 2

- **Q1:** O sistema funciona corretamente em diferentes navegadores web (Chrome, Firefox, Edge)?  
  **Hipótese Q1:** O sistema apresenta desempenho e renderização consistentes em 100% dos navegadores testados.

- **Q2:** O aplicativo mobile funciona corretamente em diferentes versões do Android?  
  **Hipótese Q2:** Pelo menos 95% dos testes são concluídos com sucesso em versões Android 9 ou superior.

- **Q3:** Há falhas ou comportamentos inesperados ao alternar entre dispositivos ou sistemas?  
  **Hipótese Q3:** Ocorrências de incompatibilidades graves são inferiores a 2%.

---

## Relação entre Objetivos de Medição, Questões e Métricas

### Objetivo de Medição 1 – Usabilidade

| Questão                                                                 | Métrica                                       |
| ----------------------------------------------------------------------- | --------------------------------------------- |
| Q1: Os usuários conseguem cadastrar lojas e produtos sem ajuda externa? | M1: Taxa de sucesso no cadastro autônomo (%)  |
| Q2: Os consumidores conseguem encontrar lojas próximas facilmente?      | M2: Tempo médio para localizar uma loja (min) |
| Q3: A interface é compreensível e intuitiva para diferentes públicos?   | M3: Avaliação da interface (escala Likert)    |

### Objetivo de Medição 2 - Compatibilidade

| Questão                                                                                    | Métrica                                            |
| ------------------------------------------------------------------------------------------ | -------------------------------------------------- |
| Q1: O sistema funciona corretamente em diferentes navegadores web (Chrome, Firefox, Edge)? | M1: Taxa de sucesso de execução em navegadores (%) |
| Q2: O aplicativo mobile funciona corretamente em diferentes versões do Android?            | M2: Taxa de compatibilidade por versão Android (%) |
| Q3: Há falhas ou comportamentos inesperados ao alternar entre dispositivos ou sistemas?    | M3: Número médio de falhas por plataforma testada  |



---

## Tabela de Contribuição

| Matrícula | Nome do Integrante     | Contribuição (%) |
|-----------|------------------------|------------------|
| 242034483  | Bruno Duarte        | 20%              |
| 251035022  | Camile Oliveira        | 20%              |
| 221008570  | Diogo Ferreira        | 20%              |
| 221008580  | Eduardo Silva        | 20%              |
| 231035150  | Júlia Reis        | 20%              |

## Bibliografia

- **ISO/IEC 25010:2011.** *Systems and Software Engineering — Systems and Software Quality Requirements and Evaluation (SQuaRE) — System and Software Quality Models*. International Organization for Standardization, 2011.

- BASILI, Victor R.; CALDIERA, Gianluigi; ROMBACH, H. Dieter. *The Goal Question Metric Approach*. Encyclopedia of Software Engineering, 1994.

- PRESSMAN, Roger S. *Engenharia de Software: uma abordagem profissional*. 7. ed. São Paulo: McGraw-Hill, 2010.

## Referências Bibliográficas

- GITHUB. Hackathon FGA 2020 – AgroMart. Disponível em: [https://github.com/Hackathon-FGA-2020/AgroMart](https://github.com/Hackathon-FGA-2020/AgroMart). Acesso em: 3 jun. 2025.

- DEX/UnB – Decanato de Extensão. *Estudantes apresentam soluções inovadoras contra impactos da COVID-19*. Disponível em: [https://dex.unb.br/noticias/688-estudantes-apresentam-solucoes-inovadoras-contra-impactos-da-covid-19](https://dex.unb.br/noticias/688-estudantes-apresentam-solucoes-inovadoras-contra-impactos-da-covid-19). Acesso em: 3 jun. 2025.

- ONU – Organização das Nações Unidas. *Objetivos de Desenvolvimento Sustentável (Agenda 2030)*. Disponível em: [https://brasil.un.org/pt-br/sdgs](https://brasil.un.org/pt-br/sdgs). Acesso em: 3 jun. 2025.


## Histórico de versões
Versão |   Data  | Descrição | Autor(es) | Revisor(es)
------ | ---- | ------ | ---------- | ----------
| 1.0 | 02/06/2025 | Criação da página de definição. | [Diogo Ferreira](https://github.com/fdiogo1) | [Júlia Massuda](http://github.com/JuliaReis18)
| 1.1 | 03/06/2025 | Adicionando tabela de contribuição, Referências e Histórico de versões. | [Júlia Massuda](http://github.com/JuliaReis18) | Add revisor aqui 
