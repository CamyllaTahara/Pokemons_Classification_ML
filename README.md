🎮 Classificação de Pokémons usando SVM 🔍

📌 Descrição do Projeto

Este projeto foi apresentando no SUMMIT 2024 na categoria Pesquisa, utiliza Machine Learning, especificamente Support Vector Machine (SVM), para classificar Pokémons em quatro categorias: Lendários, Sub-Lendários, Míticos e Comuns. O objetivo é treinar um modelo capaz de identificar corretamente a categoria de um Pokémon com base em suas estatísticas e atributos.

🛠 Metodologia

📥 Carregamento do Dataset: Utilizamos um dataset da plataforma Kaggle, que contém informações detalhadas sobre os Pokémons.

🧹 Pré-processamento dos Dados: Tratamos os dados, removendo valores nulos e normalizando atributos relevantes para garantir melhor desempenho do modelo.

📊 Divisão do Conjunto de Dados: Separarmos os dados em 80% para treinamento e 20% para teste, garantindo que o modelo possa aprender e ser avaliado corretamente.

🤖 Treinamento do Modelo: Utilizamos SVM (Support Vector Machine) para classificação, treinando o modelo com os dados processados.

📈 Avaliação do Modelo: Medimos o desempenho utilizando Recall, Precisão e F1-Score, além de interpretar a Matriz de Confusão.

📊 Métricas de Avaliação

🔍 Recall: Mede a capacidade do modelo de encontrar corretamente todos os Pokémons lendários.

🎯 Precisão: Mede a exatidão do modelo ao classificar um Pokémon como lendário.

⚖️ F1-Score: Equilibra recall e precisão para garantir uma classificação eficaz.

📊 Matriz de Confusão: Visualiza os acertos e erros do modelo em cada categoria.

🚀 Tecnologias Utilizadas

Python 🐍

Bibliotecas:

scikit-learn (para machine learning)

pandas (para manipulação de dados)

numpy (para cálculos matemáticos)

matplotlib e seaborn (para visualização de dados)
