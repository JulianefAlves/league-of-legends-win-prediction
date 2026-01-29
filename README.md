# league-of-legends-win-prediction

🎮 Predição de Vitória aos 10 Minutos com Machine Learning

📋 Sobre o Projeto
Este projeto foi desenvolvido para analisar o impacto das vantagens iniciais (Early Game) no resultado final de partidas ranqueadas de League of Legends. Utilizando um dataset de partidas de alto nível, o objetivo foi criar um modelo preditivo capaz de identificar o vencedor aos 10 minutos de jogo, analisando métricas como ouro, experiência e abates para entender o fenômeno do "Snowball".

🛠 Tecnologias Utilizadas
Linguagem: Python (Pandas, Numpy)

Visualização: Matplotlib, Seaborn

Machine Learning: Scikit-Learn (Regressão Logística, Random Forest, Decision Tree)

📊 Principais Resultados (Modelo Otimizado)
Acurácia: 73% (O modelo prevê corretamente o vencedor em 7 de cada 10 partidas).

Modelo Vencedor: Regressão Logística (Apresentou a melhor estabilidade entre precisão e recall).

Insight: Ouro e Experiência acumulados nos primeiros 10 minutos possuem o maior peso estatístico, confirmando que a vantagem inicial constrói o caminho, mas a estratégia final garante a vitória.

📂 Estrutura do Repositório
Projeto LoL.ipynb: Código completo com processamento, análise exploratória e treinamento dos modelos.

Base_M43_Pratique_LOL_RANKED_WIN (1).csv: Base de dados utilizada no projeto.

apresentacao lol.pdf: Slides do projeto com foco em resultados e inteligência de dados.


🚀 Como executar
Clone este repositório.

Instale as bibliotecas necessárias (scikit-learn, pandas, seaborn).

Execute o Jupyter Notebook para visualizar a análise completa.

Desenvolvido por Juliane Ferreira Alves | [LinkedIn](https://www.linkedin.com/in/juliane-alves-62457513a)
