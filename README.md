# Previsão de Preços de Imóveis

Este projeto tem como objetivo desenvolver um modelo de previsão de preços a partir de um dataset de imóveis, analisando fatores que influenciam o valor de locação.

## 📊 Projeto em Detalhes

- **Objetivo:** Criar um modelo de machine learning para prever preços de imóveis e avaliar seu desempenho com métricas adequadas.
- **Contexto:** O projeto explora dados de propriedades, considerando localização, características do imóvel e outros fatores que possam influenciar no preço.
- **Principais Técnicas Utilizadas:**  
  - Análise Exploratória de Dados (EDA)
  - Engenharia de Atributos (Feature Engineering)
  - Modelos de Regressão (Linear, Random Forest, Gradient Boosting, SVR, entre outros)
  - Avaliação Estatística e Visualização de Dados
    
## 🛠️ Estrutura do Repositório

```
├── data/                          # Dados usados no projeto
├── modelos_transformacao_dados/   # Modelos usados para transformar o conjunto de dados
├── modelos_machine_learning/      # Modelos de Machine Learning salvos para uso posterior
├── main.ipynb                     # Notebook com os códigos e análises
├── requirements.txt               # Bibliotecas e suas versões usadas para o projeto
├── README.md                      # Documentação do projeto
```

## 🚀 Resultados e Insights

- Identificação de variáveis relevantes para a previsão de preços.
- Avaliação do impacto da localização e disponibilidade do imóvel no preço.
- Identificação de áreas de maiores preços e interesses.
- Comparação de diferentes modelos de regressão para determinar o mais eficiente.
- Previsão de preços dos imóveis.

## 🤷‍♂️ Como Usar

1. Clone este repositório:  
   ```bash
   git clone https://github.com/usuario/indicium.git
   ```
2. Instale as dependências:  
   ```bash
   pip install -r requirements.txt
   ```
3. Baixe o modelo "RandomForestRegressor.pkl" da pasta " https://drive.google.com/drive/u/2/folders/1h2_tPKczunrh-DnaGiToX1ddmXj2CWF7 " e adicione-o à pasta "modelos_machine_learning". Pelo limite de 100.0 MB por arquivo, o modelo de Random Forest foi armazenado em uma pasta pública do Google Drive.
4. Execute o notebook principal no Jupyter Notebook.

## 📈 Tecnologias Utilizadas

- **Linguagem:** Python  
- **Bibliotecas Principais:**  
  - `pandas`, `numpy` (manipulação de dados)  
  - `matplotlib`, `seaborn`, `folium` (visualização de dados)  
  - `scipy.stats`, `statsmodels` (testes estatísticos)  
  - `sklearn` (treinamento e avaliação de modelos)

## 📄 Licença

O projeto está licenciado sobre a GNU General Public License v3.0, publicada pela Free Software Foundation.
