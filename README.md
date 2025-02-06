# 📌 Previsão de Preços de Aluguel em NYC
![NYC](https://github.com/DannielLisardo/previsao_alugueis_NYC/blob/main/NYC)

## 📊 Sobre o Projeto
Este projeto tem como objetivo prever o preço de aluguel de imóveis na cidade de Nova York utilizando técnicas de análise de dados e Machine Learning. A análise abrange a identificação de padrões, tratamento de outliers e desenvolvimento de um modelo preditivo.

---

## 🧐 Perguntas de Negócio
Durante a análise, as seguintes perguntas de negócio foram respondidas:

1️⃣ **Quais são os principais fatores que influenciam o preço do aluguel em NYC?**  
2️⃣ **Há bairros ou tipos de imóveis que apresentam preços significativamente diferentes?**  
3️⃣ **O modelo de previsão consegue fornecer estimativas precisas para novos imóveis?**

Com base nessas perguntas, foram levantadas hipóteses que direcionaram o processo de modelagem.

---

## 📝 Hipóteses Formuladas
Para responder às perguntas de negócio, trabalhamos com as seguintes hipóteses:

✔️ **O preço do aluguel está diretamente relacionado ao bairro onde o imóvel está localizado.**
✔️ **Imóveis com maior disponibilidade tendem a ter preços mais competitivos.**
✔️ **O número de avaliações pode indicar demanda e afetar o preço do aluguel.**
✔️ **O número de crimes da área onde o imóvel se encontra influencia negativamenteo valor do aluguel.**

---

## 🔧 Ferramentas e Técnicas Utilizadas
Para resolver as questões levantadas, utilizamos as seguintes técnicas:

### 📌 **Pré-processamento de Dados**
- Tratamento de valores nulos
- Transformação de variáveis categóricas em numéricas (One-Hot Encoding)
- Conversão de datas para formato datetime
- Remoção de outliers utilizando o método IQR

### 📌 **Exploração dos Dados**
- Estatísticas descritivas e visualização de distribuição dos dados
- Matriz de correlação para identificar relações entre variáveis
- Análises comparativas entre bairros e tipos de imóveis

### 📌 **Modelagem Preditiva**
- **Modelo Utilizado:** Random Forest Regressor
- **Métricas Avaliadas:**
  - MAE (Erro Médio Absoluto)
  - RMSE (Raiz do Erro Quadrático Médio)

### 📌 **Visualização de Dados**
- Mapas de calor para análise de correlação
- Gráficos de dispersão para relação entre variáveis

---

## 🚀 Resultados Obtidos
Após a remoção de outliers e ajustes no modelo, as métricas de erro obtidas foram:
- **MAE:** 46.203 (Erro médio de aproximadamente 46 dólares)
- **RMSE:** 58.33 (Desvio padrão da previsão em relação ao preço real)

Esses valores indicam que o modelo pode prever preços com uma margem de erro aceitável, mas melhorias podem ser feitas para otimização.

---

## 📌 Próximos Passos
🔹 Testar outros algoritmos de regressão como XGBoost e Gradient Boosting  
🔹 Refinar a seleção de variáveis para melhorar a precisão  
🔹 Implementar técnicas de Feature Engineering para enriquecer os dados  

---

📍 **Autor:** _[Danniel Lisardo]_  
📍 **Tecnologias:** Python, Pandas, Scikit-Learn, Seaborn, Matplotlib  
📍 **Dataset:** Dados de aluguel de NYC
