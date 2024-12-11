# LOL games : 4 years of esport and Prediction from 30min (84%Acc, RNN) 🧙‍♂️🧙‍♂️

<p align="center">
  <a href="https://github.com/Edu-png">
    <img src="https://img.shields.io/badge/Autor-Eduardo%20Coqueiro-purple?style=flat&logo=github" alt="Autor">
  </a>
  <a href="mailto:eduardocoqueiro@gmail.com">
    <img src="https://img.shields.io/badge/Email-eduardocoqueiro%40gmail.com-purple?style=flat&logo=gmail" alt="Email">
  </a>
  <a href="https://linkedin.com/in/eduardocoqueiro/">
    <img src="https://img.shields.io/badge/LinkedIn-Eduardo%20Coqueiro-purple?style=flat&logo=linkedin" alt="LinkedIn">
  </a>
  <a href="https://kaggle.com/EduardoCoqueiro">
    <img src="https://img.shields.io/badge/Kaggle-Eduardo%20Coqueiro-blue?style=flat&logo=kaggle" alt="Kaggle">
  </a>
</p>

![CAPAS - PROJETOS (1)](https://github.com/user-attachments/assets/952d9056-b408-4339-8cc3-509414f965bd)

## 📋 Sumário

1. [📜 Resumo do Projeto](#-resumo-do-projeto)
2. [🗂️ Estrutura dos Dados](#️-estrutura-dos-dados)
3. [🎯 Objetivos Principais](#-objetivos-principais)
4. [🛠️ Técnicas e Ferramentas](#️-técnicas-e-ferramentas)
5. [🔗 Origem dos Dados](#-origem-dos-dados)
6. [🖥️ Introdução ao Projeto](#-introdução-ao-projeto)
7. [🛠️ Pipeline do Projeto](#-pipeline-do-projeto)
   - [📋 Coleta e Exploração dos Dados](#-1-coleta-e-exploração-dos-dados)
   - [🧹 Pré-processamento dos Dados](#-2-pré-processamento-dos-dados)
   - [📊 Visualização de Dados](#-3-visualização-de-dados)
   - [🤖 Modelagem com Machine Learning](#-4-modelagem-com-machine-learning)
   - [🔮 Predições](#-5-predições)
8. [🔍 Métodos Utilizados no Projeto](#-métodos-utilizados-no-projeto)
   - [📂 Coleta de Dados](#-coleta-de-dados)
   - [🧹 Pré-processamento](#-pré-processamento)
   - [📊 Visualização de Dados](#-visualização-de-dados)
   - [🤖 Modelagem com Machine Learning](#-modelagem-com-machine-learning)
9. [📊 Resultados e Conclusões](#-resultados-e-conclusões)
   - [Distribuição de Partidas por Ano](#-1-distribuição-de-partidas-por-ano)
   - [Distribuição de Partidas por Temporada](#-2-distribuição-de-partidas-por-temporada)
   - [Duração Média das Partidas (2014–2016)](#-3-duração-média-das-partidas-2014-2016)
   - [Duração Média por Ano](#-4-duração-média-por-ano)
   - [Desempenho por Liga](#-5-desempenho-por-liga)
   - [Número de Jogos por Liga por Ano](#-6-número-de-jogos-por-liga-por-ano)
   - [Taxas de Vitória e Derrota - Time Azul](#-7-taxas-de-vitória-e-derrota---time-azul)
   - [Taxas de Vitória e Derrota - Time Vermelho](#-8-taxas-de-vitória-e-derrota---time-vermelho)
   - [Duração dos Jogos por Liga](#-9-duração-dos-jogos-por-liga)
   - [Distribuição de Partidas por Liga e Temporada](#-10-distribuição-de-partidas-por-liga-e-temporada)
   - [Diferença de Ouro ao Longo do Tempo](#-11-diferença-de-ouro-ao-longo-do-tempo)
   - [Conclusões Gerais](#-conclusões-gerais)
10. [🚀 Considerações Finais](#-considerações-finais)
11. [🙏 Agradecimentos](#-agradecimentos)
12. [📪 Contato](#-contato)

# 📜 Resumo do Projeto - League of Legends

Este projeto tem como foco a análise de dados de partidas competitivas de **League of Legends**, coletados entre os anos de 2015 e 2017. O objetivo principal é explorar as tendências e características das partidas, além de construir modelos preditivos baseados em dados temporais.

## 🗂️ Estrutura dos Dados

O conjunto de dados contempla informações de ligas profissionais e torneios internacionais, como:
- **NALCS** (North America League Championship Series),
- **EULCS** (Europe League Championship Series),
- **LCK** (League of Legends Champions Korea),
- **LMS** (League of Legends Masters Series),
- **CBLoL** (Circuito Brasileiro de League of Legends),
- **World Championship** e **Mid-Season Invitational**.

Cada partida possui informações sobre:
- **Tempo de jogo**, **resultados** e **estatísticas de desempenho**;
- Detalhes de **torres destruídas**, **dragões e barões abatidos**, **inibidores destruídos** e **número de abates**;
- Histórico de bans e picks.

## 🎯 Objetivos Principais

1. **Analisar o conjunto de dados e identificar padrões**:
   - Comparar o desempenho entre ligas e temporadas;
   - Avaliar a duração média das partidas e as taxas de vitória/derrota por lado (*blue* ou *red*).

2. **Realizar visualizações gráficas**:
   - Gráficos para explorar variações temporais em ligas, temporadas e anos;
   - Análise visual da evolução de estatísticas, como **diferença de ouro** e **abates**.

3. **Desenvolver um modelo preditivo**:
   - Utilizar **Redes Neurais Recorrentes (RNN)** para prever o vencedor de partidas com base nos primeiros 30 minutos de dados coletados.

4. **Explorar o impacto de eventos-chave no jogo**:
   - Avaliar como abates de barões, dragões e destruição de torres influenciam o resultado final.

## 🛠️ Técnicas e Ferramentas

- **Exploração de Dados**: Pandas, NumPy.
- **Visualizações**: Matplotlib, Seaborn, Plotly.
- **Machine Learning**: PyTorch, Redes Neurais Recorrentes (RNN).
- **Análise Estatística**: Transformação de dados temporais, normalização e modelagem.

## 🔗 Origem dos Dados

Os dados utilizados neste projeto foram obtidos no Kaggle e contêm informações detalhadas sobre milhares de partidas competitivas, permitindo análises robustas e insights relevantes.

# 🖥️ Introdução ao Projeto - League of Legends

Este projeto é uma análise abrangente de dados competitivos de **League of Legends**, um dos jogos mais populares do mundo no cenário de eSports. Ele abrange partidas realizadas entre 2015 e 2017 em diversas ligas profissionais e torneios internacionais.

O principal objetivo é explorar tendências, identificar padrões e construir modelos preditivos que possam prever o vencedor de uma partida com base em dados coletados nos primeiros 30 minutos. Além disso, este projeto utiliza visualizações gráficas detalhadas para entender como eventos-chave, como destruição de torres e abates de dragões, impactam o resultado final de um jogo.

Combinando ferramentas de análise de dados e aprendizado de máquina, este projeto é uma oportunidade para mergulhar nas complexidades do mundo competitivo de **League of Legends** e aplicar técnicas de ciência de dados em um contexto real e dinâmico.

# 🛠️ Pipeline do Projeto - League of Legends

## 📋 1. Coleta e Exploração dos Dados
### 1.1 Importação dos Dados
- **Fonte:** Dataset público obtido do Kaggle contendo estatísticas detalhadas de partidas profissionais.
- **Arquivos utilizados:**
  - `LeagueofLegends.csv`: Contém estatísticas gerais das partidas.
  - `gold.csv`, `deathValues.csv`, `objValues.csv`, `bans.csv`: Dados complementares sobre ouro, mortes, objetivos e proibições.

### 1.2 Análise Exploratória de Dados (EDA)
- **Etapas realizadas:**
  - Exibição inicial do dataset (`head`, `info`, `describe`).
  - Identificação de valores ausentes e inconsistências.
  - Visualizações gráficas:
    - Distribuição de partidas por ano, temporada e duração.
    - Comparação de métricas de jogo (ouro, torres, abates, dragões) ao longo do tempo.
  - Estatísticas descritivas de ligas e temporadas.

---

## 🧹 2. Pré-processamento dos Dados
### 2.1 Limpeza dos Dados
- Remoção de valores ausentes (se necessário).
- Conversão de tipos de dados para garantir consistência (e.g., datas e listas).

### 2.2 Transformação dos Dados
- Normalização dos valores numéricos usando `StandardScaler`.
- Criação de métricas derivadas:
  - **Diferença de ouro (golddiff):** Ouro acumulado do time azul menos o ouro do time vermelho.
  - **Diferença de abates (killdiff):** Mortes acumuladas pelo time azul menos as mortes do time vermelho.
  - **Diferença de objetivos (torres, dragões, barões, inibidores):** Total do time azul menos o total do time vermelho.

---

## 📊 3. Visualização de Dados
### 3.1 Análise Temporal
- Gráficos de linha, barras e dispersão para:
  - Ouro e objetivos acumulados ao longo do tempo.
  - Taxas de vitória e derrota por lado (azul/vermelho).
  - Impacto de bans e picks nas partidas.

### 3.2 Comparação por Liga e Temporada
- Gráficos empilhados para partidas por liga/ano.
- Mapas de calor para visualizar padrões sazonais.

---

## 🤖 4. Modelagem com Machine Learning
### 4.1 Preparação para Treinamento
- Definição do problema: Prever o vencedor da partida com base nos primeiros 30 minutos.
- Construção do dataset:
  - Variáveis independentes: `golddiff`, `dragondiff`, `barondiff`, `heralddiff`, `towerdiff`, `inhibitordiff`, `killdiff`.
  - Variável dependente: `bResult` (vitória do time azul).

### 4.2 Modelo de Rede Neural Recorrente (RNN)
- **Estrutura:**
  - Camada RNN com ativação ReLU.
  - Camada totalmente conectada (linear) para saída (classificação binária: vitória/derrota).
- **Configurações:**
  - Número de épocas: 100.
  - Taxa de aprendizado: 0.0001.
  - Tamanho do lote: 32.
  - Função de perda: CrossEntropyLoss.
  - Otimizador: Adam.

### 4.3 Avaliação do Modelo
- Divisão do dataset em **treinamento (60%)**, **validação (20%)** e **teste (20%)**.
- Métricas de desempenho:
  - Acurácia (baseline e modelo treinado).
  - Perda média no conjunto de validação e teste.

---

## 🔮 5. Aplicação e Predições
### 5.1 Predição de Partidas Reais
- Teste do modelo com dados de partidas reais, incluindo jogos históricos de torneios (e.g., CBLOL, Worlds).
- Simulação de cenários com estatísticas fictícias para validar a robustez do modelo.

### 5.2 Insights e Conclusões
- Identificação de padrões significativos:
  - Impacto de eventos críticos (dragões, barões, torres) no resultado das partidas.
  - Vantagem acumulativa de ouro como preditor de vitória.
- Discussão sobre limitações do modelo e possíveis melhorias.

---

## 🚀 6. Próximos Passos
- Integração de novos datasets para abranger partidas de anos recentes.
- Aplicação de outras técnicas de Machine Learning, como árvores de decisão e ensembles.
- Exploração de redes neurais LSTM para maior compreensão temporal.
- Refinamento do modelo para considerar estratégias avançadas (e.g., composições de campeões e macroplay).

# 🔍 Métodos Utilizados no Projeto

## 📂 Coleta de Dados
1. **Fontes de Dados:**
   - Dataset público do Kaggle contendo informações detalhadas de partidas profissionais de League of Legends.
   - Arquivos complementares fornecidos pelo dataset:
     - `LeagueofLegends.csv`: Estatísticas gerais das partidas.
     - `gold.csv`: Acúmulo de ouro por minuto.
     - `deathValues.csv`: Dados sobre mortes por minuto.
     - `objValues.csv`: Estatísticas de objetivos (dragões, barões, torres, inibidores).
     - `bans.csv`: Informações sobre bans e picks.
2. **Importação de Dados:**
   - Utilização de bibliotecas como `pandas` para carregar e manipular os arquivos CSV.

---

## 🧹 Pré-processamento
1. **Limpeza:**
   - Identificação e tratamento de valores ausentes.
   - Conversão de colunas de strings para listas reais usando `literal_eval`.

2. **Transformação:**
   - Criação de métricas derivadas, como:
     - **Diferença de ouro:** (`golddiff = gold_blue - gold_red`).
     - **Diferença de dragões, barões, inibidores e torres.**
   - Normalização dos dados usando `StandardScaler` para ajustar todas as variáveis a uma escala comum.

---

## 📊 Visualização de Dados
1. **Análise Exploratória:**
   - Criação de gráficos com `matplotlib` e `seaborn` para explorar distribuições e padrões:
     - Ouro acumulado ao longo do tempo.
     - Taxas de vitória por lado (azul/vermelho).
     - Impacto de bans e objetivos nos resultados das partidas.

2. **Comparação entre Ligas e Temporadas:**
   - Uso de gráficos empilhados e mapas de calor para visualizar diferenças entre ligas e temporadas.

---

## 🤖 Modelagem com Machine Learning
1. **Definição do Problema:**
   - Prever o vencedor da partida com base nos eventos ocorridos até os primeiros 30 minutos.

2. **Modelo Utilizado:**
   - **Rede Neural Recorrente (RNN):**
     - Entrada: Sequências temporais de características derivadas (`golddiff`, `killdiff`, etc.).
     - Arquitetura:
       - Camada RNN com ativação ReLU.
       - Camada linear para saída (classificação binária).
     - Parâmetros:
       - Tamanho do lote: 32.
       - Taxa de aprendizado: 0.0001.
       - Função de perda: CrossEntropyLoss.
       - Otimizador: Adam e CrossEntropyLoss.
       - 7 entradas temporais (input)
       -  Estrutura com camada oculta de 256 neurônios.

3. **Divisão de Dados:**
   - **Treinamento (60%)**: Ajuste dos pesos do modelo.
   - **Validação (20%)**: Avaliação do desempenho durante o treinamento.
   - **Teste (20%)**: Avaliação final da performance.

4. **Treinamento:**
   - Implementação de `early stopping` para evitar sobreajuste.
   - Armazenamento do melhor modelo com base na acurácia de validação.

5. **Avaliação:**
   - Métricas de desempenho:
     - Acurácia do modelo.
     - Perda média no conjunto de validação/teste.

---

## 🔮 Predições
1. **Predição de Partidas Reais:**
   - Aplicação do modelo a partidas históricas e simulações com estatísticas fictícias.
   - Interpretação das probabilidades calculadas para cada time.

2. **Geração de Insights:**
   - Identificação de fatores-chave para a vitória:
     - Acúmulo de ouro e objetivos.
     - Taxa de crescimento do diferencial de ouro ao longo do tempo.
   - Discussão das limitações do modelo e melhorias possíveis.

---

## 📚 Ferramentas e Bibliotecas
- **Manipulação e Análise de Dados:**
  - `pandas`, `numpy`
- **Visualização:**
  - `matplotlib`, `seaborn`, `plotly`
- **Machine Learning e Deep Learning:**
  - `PyTorch`, `torch.utils.data`, `scikit-learn`
- **Otimização:**
  - `Adam Optimizer`
- **Tratamento de Erros e Eficiência:**
  - Uso de `warnings.filterwarnings` para suprimir mensagens irrelevantes.


## 📊 Resultados e Conclusões

### 1. Distribuição de Partidas por Ano
- Observação: O ano de 2016 teve o maior número de partidas registradas, seguido de 2015 e 2017, indicando um crescimento significativo na popularidade das competições durante este período.

![1](https://github.com/user-attachments/assets/39c2f8da-c810-4e36-972a-fae4fa3844ae)

---

### 2. Distribuição de Partidas por Temporada
- Observação: As temporadas de primavera e verão concentram a maioria das partidas, enquanto playoffs e competições internacionais possuem volumes menores.

![2](https://github.com/user-attachments/assets/6a7fead7-42ea-4685-8316-3cf0c9576976)

---

### 3. Duração Média das Partidas (2014–2016)
- Observação: A maioria das partidas dura entre 30 a 40 minutos, com poucos jogos excedendo 70 minutos.

![3](https://github.com/user-attachments/assets/1eb481cc-8dfa-48fb-9786-84b9f868cad4)

---

### 4. Duração Média por Ano
- Observação: Apesar de pequenas variações, a duração média das partidas permaneceu consistente entre os anos analisados.

![4](https://github.com/user-attachments/assets/0aa0eabf-8fd2-489d-b635-bf6278a89638)

---

### 5. Desempenho por Liga
- Observação: As ligas LCK, Europa e América do Norte apresentaram os maiores volumes de jogos, com destaque para o domínio da LCK em termos de número total de partidas.

![5](https://github.com/user-attachments/assets/bed2a7a6-409f-4315-8b92-4a5db7aff504)

---


### 6. Número de Jogos por Liga por Ano
- Observação: O número de jogos varia significativamente entre as ligas ao longo dos anos, com destaque para LCK e América do Norte, que consistentemente apresentam altos volumes de partidas.

![6](https://github.com/user-attachments/assets/6be67f82-a157-49a7-be68-1b3a7b17abbc)

---

### 7. Taxas de Vitória e Derrota - Time Azul
- Observação: O time azul apresenta uma taxa de vitórias maior na maioria dos anos analisados, indicando possível vantagem no lado azul do mapa.

![7](https://github.com/user-attachments/assets/efcf9a0e-a674-48ae-9e7a-15b079a1348f)

---

### 8. Taxas de Vitória e Derrota - Time Vermelho
- Observação: Embora o time vermelho tenha consistentemente menos vitórias que o azul, há indícios de equilíbrio crescente ao longo dos anos.

![8](https://github.com/user-attachments/assets/ce3b9aee-b3b5-4060-9775-ae179f73aceb)


---

### 9. Duração dos Jogos por Liga
- Observação: Cada liga apresenta uma distribuição distinta de duração de jogos, com ligas como LCK tendendo a partidas mais longas em comparação a outras como CBLOL.

![9](https://github.com/user-attachments/assets/90287979-5f3b-4a80-b867-8cb18d5f2027)

---

### 10. Distribuição de Partidas por Liga e Temporada
- Observação: As ligas mais estabelecidas apresentam maior distribuição de jogos durante temporadas principais, como primavera e verão, reforçando sua estabilidade competitiva.

![10](https://github.com/user-attachments/assets/f3ffeb13-abb5-4f82-964c-cdee2232443f)


### 11. Diferença de Ouro ao Longo do Tempo
- Observação: A diferença de ouro acumulada entre as equipes azul (vitória) e vermelha (derrota) cresce de forma significativa após os primeiros 15 minutos, indicando que o controle inicial do jogo é crucial para a vitória.

![11](https://github.com/user-attachments/assets/81081dbd-0073-476f-a565-9e1b0e679f95)

### 12. Modelagem com RNN
   - Entrada sequencial de características temporais.
   - Avaliação com baseline accuracy (83.24%).
     
![output](https://github.com/user-attachments/assets/56789c8a-8381-467e-89ae-b3d007f29bac)

---

### Conclusões Gerais
- **Evolução do Esporte**: O aumento no número de partidas por ano demonstra a crescente relevância de League of Legends como um esporte eletrônico competitivo.
- **Importância do Early Game**: A análise da diferença de ouro reforça a relevância de um bom desempenho nos minutos iniciais para determinar o resultado final.
- **Padronização de Duração**: A consistência na duração média das partidas sugere que as regras e dinâmicas do jogo promovem partidas balanceadas e previsíveis.

### Próximos Passos
- Expandir a análise para incluir dados mais recentes, explorando como as mudanças no meta do jogo e nas regras impactaram as estatísticas das partidas.
- Utilizar aprendizado de máquina para prever resultados com base em métricas iniciais, como diferença de ouro, kills e controle de objetivos.

---

## Considerações Finais

Este estudo revelou informações valiosas sobre os dados de partidas do League of Legends, permitindo uma análise aprofundada de diferentes aspectos do jogo competitivo, incluindo duração de partidas, taxas de vitória e derrota, e variações entre ligas e temporadas. 

### Principais Conclusões:
1. **Crescimento ao longo dos anos:** O número de partidas aumentou substancialmente entre 2014 e 2016, refletindo o crescimento do cenário competitivo. No entanto, houve uma leve diminuição em 2017, possivelmente devido a mudanças no formato competitivo.
2. **Diferenças entre ligas:** Ligas como LCK e América do Norte se destacaram em termos de volume e duração de jogos, enquanto ligas menores apresentaram maior variabilidade em suas métricas.
3. **Taxas de vitória por lado:** O time azul apresentou uma vantagem consistente sobre o time vermelho na maioria dos anos, destacando um possível desequilíbrio de mapa que pode influenciar estratégias competitivas.
4. **Duração de partidas:** Observou-se que a duração média das partidas permaneceu estável ao longo dos anos, variando entre 35 e 40 minutos, com algumas variações notáveis entre as ligas.
5. **O controle de recursos (ouro, torres, dragões) é fundamental para vitória.**
6. **A RNN alcançou alta acurácia ao prever vencedores com base nos primeiros 30 minutos.**

### Impacto e Aplicações:
Os resultados podem ser utilizados para:
- **Melhorias competitivas:** Equipes e analistas podem usar esses insights para desenvolver estratégias mais eficazes baseadas em dados históricos.
- **Ajustes no balanceamento do jogo:** Identificar desequilíbrios, como a vantagem do lado azul, pode orientar mudanças no design do jogo.
- **Planejamento de eventos:** Organizadores podem otimizar a estrutura de campeonatos com base nas dinâmicas das diferentes ligas e temporadas.

### Trabalhos Futuros:
- Expansão da análise para incluir dados de partidas pós-2017, avaliando tendências mais recentes.
- Uso de modelos de machine learning para prever resultados de jogos e identificar padrões ocultos nos dados.
- Investigação de fatores externos, como mudanças de patches e meta do jogo, para analisar como influenciam os resultados e métricas de desempenho.

Os resultados obtidos refletem a riqueza do dataset analisado e demonstram como análises detalhadas podem gerar insights significativos para diversas partes interessadas no cenário competitivo do League of Legends.

---

## Agradecimentos

Gostaríamos de expressar nossa gratidão a todos que contribuíram direta ou indiretamente para a realização deste projeto:

1. **Comunidade de League of Legends** - Por disponibilizar dados ricos e detalhados que possibilitaram uma análise aprofundada do cenário competitivo.
2. **Plataformas de Dados** - Agradecemos especialmente às plataformas de compartilhamento de datasets, como o Kaggle, por disponibilizarem os dados necessários para este estudo.
3. **Colaboradores e Mentores** - Àqueles que forneceram feedback, orientações e insights durante as etapas de análise e desenvolvimento do projeto.
4. **Recursos Educacionais** - A instituições e cursos que disponibilizam materiais e ferramentas acessíveis para o aprendizado de ciência de dados e análise estatística.

Este projeto não teria sido possível sem o apoio de uma comunidade vibrante e colaborativa, que compartilha conhecimentos e inspira avanços contínuos. A todos, nosso muito obrigado!

---

<div align="center">
  <img src="https://github.com/user-attachments/assets/54afb33c-97be-40b6-8c96-0f12852e946f" alt="thank-you" width="500">
</div>


## Contato 📪
- **LinkedIn:** [Eduardo Coqueiro](https://www.linkedin.com/in/eduardocoqueiro/)
- **Site:** [Eduardo Coqueiro](https://dataguy.my.canva.site/eduardo-coqueiro)
- **Kaggle:** [Eduardo Coqueiro](https://www.kaggle.com/eduardocoqueiro)

