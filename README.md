Este projeto foi elaborado como projeto final da disciplina Modelo de Linguagens Neurais da Universidade Federal Fluminense semestre 2/2025

Este repositório contém um pipeline de PLN que combina duas tarefas de competições distintas — **CheckThat! 2025 Task 1** e **SemEval 2024 Task 3** — com o objetivo de investigar a hipótese de que **textos subjetivos apresentam causas emocionais mais explícitas que textos objetivos**.

O pipeline possui duas etapas principais:

1. **Detecção de Subjetividade em Notícias**  
2. **Análise de Causas de Emoções em Conversações**  

---

## 🎯 Objetivo

Construir um pipeline onde:

- Primeiro, o modelo identifica se um texto é **subjetivo** ou **objetivo**.  
- Apenas textos identificados como **subjetivos** são enviados para um modelo que realiza **Análise de Causa de Emoção (Emotion Cause Analysis – ECA)**.  

A hipótese investigada é que **a subjetividade do texto está correlacionada com causas emocionais mais claras e explícitas**.

