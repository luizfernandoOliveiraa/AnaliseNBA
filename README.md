# 📊 Análise de Dados da NBA: Foco em LeBron James 📊 

## 📌 Introdução
O objetivo deste projeto foi realizar uma análise detalhada dos dados de desempenho do jogador LeBron James, utilizando um dataset da NBA disponível no Kaggle. A partir dessa análise, buscamos identificar jogadores cujas estatísticas se aproximam das de LeBron ao longo dos anos, especialmente enquanto ele jogava em diferentes equipes.

## 💡 Motivação
LeBron James é amplamente reconhecido como um dos maiores jogadores da história da NBA. Este projeto visa explorar seu desempenho ao longo dos anos e compará-lo com outros jogadores que, em momentos específicos, chegaram perto de suas estatísticas. Além disso, foram realizadas análises para entender melhor seu impacto em cada equipe pela qual passou.

## 🛠 Ferramentas Utilizadas
- **Pandas**: Para manipulação de dados e análise exploratória.
- **NumPy**: Para cálculos matemáticos e operações em arrays.
- **Matplotlib**: Para visualizações de gráficos.
- **Seaborn**: Para aprimorar a visualização dos dados com gráficos mais estilizados.
- **Scikit-learn**: Para realizar testes A/B e testes de hipótese.

## 📝 Metodologia
A análise foi dividida em diferentes etapas, conforme detalhado a seguir:

### 📊 Coleta e Limpeza de Dados
O dataset da NBA foi extraído do Kaggle, contendo informações como pontos, rebotes, assistências, entre outros, de jogadores ao longo das temporadas de 1996 até 2022. Após a coleta, realizamos:
- **Classificação e separação dos dados**: Separados as variaveis quantitativas e qualitativas que usamos para realizar as análises.
- **Transformação de variáveis**: Conversão de colunas de datas, normalização de dados e categorização dos times e temporadas.
  
### 🔎 Análise Exploratório de Dados (EDA)
Com os dados limpos, utilizamos **Pandas** e **NumPy** para:
- Identificar as estatísticas principais de LeBron James, como pontos por jogo, assistências, rebotes, entre outros.
- Comparar essas métricas com outros jogadores, aplicando filtros específicos para identificar aqueles que tiveram números semelhantes em determinadas temporadas.

### 🧮 Visualizações
Foram criadas visualizações utilizando **Matplotlib** e **Seaborn**:
- Gráficos de linha para mostrar a evolução do desempenho de LeBron ao longo dos anos.
- Gráficos de barras comparando LeBron com outros jogadores em métricas específicas (pontos, rebotes, assistências).
- Gráficos de dispersão para mostrar a correlação entre os times que LeBron jogou e seu impacto nos resultados das partidas.

### 🏀 Análise por Equipe
A análise foi segmentada por equipe, passando por:
- **Cleveland Cavaliers**, **Miami Heat** e **Los Angeles Lakers**: Analisamos o desempenho de LeBron em cada time e como suas contribuições mudaram ao longo das temporadas.

### 📚 Testes A/B e Testes de Hipótese
Para validar as hipóteses levantadas durante a análise, foram realizados:
- **Testes A/B**: Comparando o impacto de LeBron em diferentes times e momentos da carreira, buscando entender se a presença dele realmente resultou em um desempenho significativamente melhor.
- **Testes de Hipótese**: Utilizamos o **Scikit-learn** para testar a hipótese de que LeBron impacta de forma única o desempenho de seus times comparado a outros jogadores de elite.

## 🗒 Resultados
Os resultados mostraram:
- LeBron James tem uma consistência impressionante em suas estatísticas, especialmente em pontos e assistências, mesmo em diferentes times.
- Alguns jogadores, como **Luka Doncic** e **Kobe Bryant**, tiveram temporadas com números próximos aos de LeBron, mas sua regularidade ao longo dos anos é incomparável.
- Os testes A/B mostraram que as equipes com LeBron tiveram uma melhoria significativa no desempenho, confirmando sua influência direta nos resultados.

## 📍 Conclusão
A análise confirmou a supremacia de LeBron James como um dos melhores jogadores da história, tanto em termos de desempenho individual quanto no impacto sobre suas equipes. Jogadores com números semelhantes existiram, mas sua longevidade e consistência são únicos. Os testes A/B e de hipótese reforçaram a importância de LeBron para o sucesso de suas equipes.
