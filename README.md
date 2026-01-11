# 📈 Previsão de Aluguéis de Bicicletas com Prophet

## 📌 Contexto
Serviços de aluguel de bicicletas dependem fortemente de previsões de demanda
para planejamento operacional, alocação de recursos e tomada de decisão estratégica.
Fatores como sazonalidade semanal, mensal e padrões históricos influenciam diretamente
o volume de aluguéis.

Este projeto explora o uso de **modelos de séries temporais** para prever cenários futuros
de aluguéis diários de bicicletas a partir de dados históricos.

---

## 🎯 Objetivo
Construir um modelo de previsão capaz de:

- Identificar padrões e sazonalidades nos dados
- Prever a demanda para um horizonte de **5 meses**
- Avaliar a qualidade das previsões com métricas estatísticas

---

## 🧠 Abordagem
As principais etapas do projeto foram:

- Análise exploratória dos dados (EDA)
- Preparação e divisão dos dados em treino e teste
- Modelagem com **Prophet**
- Inclusão de **sazonalidade semanal** para aumentar a aderência do modelo
- Avaliação do desempenho com métricas quantitativas
- Visualização dos resultados com gráficos estáticos e interativos

---

## 🛠️ Tecnologias Utilizadas
- Python  
- Pandas  
- Matplotlib  
- Prophet  
- Scikit-learn  
- Plotly  

---

## 📊 Avaliação do Modelo

As previsões foram avaliadas utilizando as seguintes métricas:

- **RMSE (Root Mean Squared Error)**  
  Mede o erro médio entre os valores previstos e os valores reais.

- **R² Score**  
  Indica a proporção da variabilidade dos aluguéis explicada pelo modelo.

### 🔎 Resultados
- **Acurácia média:** 87,60% dos aluguéis diários previstos  
- **R² Score:** 76,18% da variabilidade explicada  

Os resultados indicam boa capacidade do modelo em capturar padrões históricos
e sazonalidades relevantes.

---

## 📉 Visualização dos Resultados
Além das visualizações tradicionais, foi criado um **gráfico de correlação interativo
com Plotly**, permitindo uma análise mais detalhada das previsões:

- Pontos pretos → dados históricos  
- Pontos vermelhos → valores reais do período previsto  
- Intervalos de confiança para análise de incerteza  

---

## 📎 Escopo do Projeto
Este projeto teve como foco a aplicação prática de modelos de séries temporais
com **Prophet**, visando a consolidação de conceitos de forecasting,
avaliação de modelos e comunicação de resultados.
