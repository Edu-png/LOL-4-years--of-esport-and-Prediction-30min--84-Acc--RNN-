# LOL games : 4 years of esport and Prediction from 30min (84%Acc, RNN)

## Sumário:
- [Resumo](#resumo)
- [Introdução](#introdução)
- [Objetivo](#objetivo)
- [Métodos](#métodos)
- [Conclusões](#conclusões)
- [Considerações finais](#considerações-finais)
- [Referências](#referências)
- [Documentação](#documentação)
- [Agradecimentos](#agradecimentos)
- [Contato](#contato)

## Resumo 🏃‍♀️
Este projeto tem como objetivo analisar partidas competitivas de League of Legends utilizando diversas técnicas de análise de dados e machine learning. A análise é realizada a partir de dados históricos de partidas, buscando identificar padrões, estatísticas importantes e desenvolver modelos preditivos para determinar o vencedor de uma partida baseado em dados coletados até os 30 minutos de jogo.

## Introdução
O cenário competitivo de League of Legends (LoL) é vasto e complexo, com equipes profissionais competindo em diversas ligas ao redor do mundo. Compreender os fatores que levam uma equipe à vitória é crucial para equipes, treinadores e analistas. Este projeto utiliza dados históricos de partidas competitivas de LoL para analisar padrões e prever resultados de partidas.

### Objetivo
Desenvolver um modelo preditivo para determinar o vencedor de uma partida de League of Legends aos 30 minutos de jogo, utilizando Redes Neurais Recorrentes (RNN) e outras técnicas de análise de dados.

## Métodos
### Coleta dos dados 🎲
Os dados foram obtidos a partir de um dataset público disponibilizado no Kaggle. A base de dados contém informações detalhadas sobre partidas competitivas de LoL, incluindo variáveis como tempo de jogo, diferença de ouro, abates de dragões, barões, torres, entre outros.

### Limpeza dos dados 🧹
Os dados foram pré-processados para remover valores ausentes e outliers. Além disso, foram criadas novas variáveis a partir das existentes para enriquecer a análise, como diferenças acumuladas de ouro, dragões, barões, torres, inibidores e abates ao longo do tempo.

### Análise exploratória 🤿
Realizou-se uma análise exploratória dos dados (EDA) para identificar padrões sazonais e tendências nas partidas de LoL. Visualizações gráficas foram utilizadas para facilitar a compreensão dos dados.

### Modelos de Machine Learning 🔮
Foram testados diversos modelos de machine learning, incluindo Redes Neurais Recorrentes (RNN). O desempenho dos modelos foi avaliado utilizando métricas como acurácia, precisão, recall e F1-score.

### Bibliotecas utilizadas e suas respectivas funções 🐍
- **Pandas:** Manipulação de dados
- **NumPy:** Operações numéricas
- **Matplotlib:** Visualização de dados
- **Seaborn:** Visualização de dados
- **scikit-learn:** Ferramentas de machine learning
- **torch (PyTorch):** Implementação de Redes Neurais Recorrentes (RNN)

## Conclusões 💡
A análise mostrou que a diferença acumulada de ouro e outros eventos-chave, como abates de dragões e torres, são bons indicadores do resultado de uma partida. O modelo de RNN desenvolvido apresentou uma acurácia significativa na previsão do vencedor aos 30 minutos de jogo.

## Considerações finais 🚀
Ferramentas de previsão como as utilizadas neste projeto são essenciais para equipes e analistas de eSports que buscam otimizar suas estratégias e melhorar o desempenho. Continuar refinando esses modelos com mais dados e variáveis adicionais pode aumentar ainda mais sua precisão.

## Referências 📄
- [League of Legends Dataset on Kaggle](https://www.kaggle.com/datasets/jonathanbouchet/lol-games-4-years-of-esport)
- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
- [Pandas Documentation](https://pandas.pydata.org/pandas-docs/stable/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [scikit-learn Documentation](https://scikit-learn.org/stable/)

## Documentação 📚
- **[Notebook da Limpeza dos Dados](link_do_notebook_limpeza)**
- **[Notebook da Análise Exploratória dos Dados](link_do_notebook_eda)**
- **[Notebook das Previsões com Machine Learning](link_do_notebook_ml)**

Para uma experiência melhor, eu recomendo que esses notebooks sejam abertos pelo Google Colaboratory 😉

## Agradecimentos 👏
Gostaria de agradecer a todos os instrutores e colegas que contribuíram para a realização deste projeto.

## Contato 📪
- **LinkedIn:** [Eduardo Coqueiro](https://www.linkedin.com/in/eduardocoqueiro/)
- **Site:** [Eduardo Coqueiro](https://dataguy.my.canva.site/eduardo-coqueiro)
- **Kaggle:** [Eduardo Coqueiro](https://www.kaggle.com/eduardocoqueiro)

