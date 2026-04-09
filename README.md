# TCC – Classificação de Indícios de TEA com Machine Learning

Este repositório contém o código-fonte e o notebook desenvolvidos para o Trabalho de Conclusão de Curso do programa de Especialização em Data Science and Analytics (2026).

O projeto tem como objetivo aplicar técnicas de Machine Learning supervisionado para classificação de indícios de Transtorno do Espectro Autista (TEA), utilizando base pública estruturada.

---

## Base de Dados

Autistic Spectrum Disorder Screening Data for Children  
UCI Machine Learning Repository  

Disponível em:  
https://archive.ics.uci.edu/dataset/419/autistic+spectrum+disorder+screening+data+for+children

A variável alvo encontra-se associada à pontuação derivada do instrumento de triagem AQ-10.

---

## Modelos Implementados

- Regressão Logística
- Random Forest

Foram avaliadas métricas como acurácia, matriz de confusão e curva ROC/AUC.

---

## Protótipo

O trabalho inclui o desenvolvimento de um protótipo de Sistema de Apoio à Decisão Clínica, no qual os coeficientes estimados pelo modelo de Regressão Logística são utilizados para calcular uma probabilidade contínua de risco, representada por meio de um “termômetro” visual.

---

## Reprodutibilidade

O notebook foi disponibilizado sem outputs salvos para manter a integridade estrutural do arquivo e facilitar o versionamento.

Para reproduzir os resultados:
1. Execute o notebook sequencialmente em ambiente Google Colab ou Jupyter Notebook.
2. Certifique-se de instalar as bibliotecas necessárias (pandas, numpy, scikit-learn, matplotlib, seaborn, ipywidgets).

---

## Observação

Os modelos implementados reproduzem computacionalmente a estrutura matemática do instrumento de triagem utilizado na base pública. Os resultados devem ser interpretados sob perspectiva metodológica e não substituem avaliação clínica especializada.
