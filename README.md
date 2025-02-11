# Análise de Partidas do League of Legends  

Este projeto utiliza dados coletados da **Riot Games API** para analisar padrões em minhas partidas do **League of Legends**, com o objetivo de entender os principais fatores que influenciam as derrotas e identificar estratégias para melhorar minha performance no jogo.  

---

## Estrutura do Projeto  

📁 `dataset/` → Contém os dados coletados das partidas.  
📁 `notebook/` → Contém o notebook Jupyter com as análises exploratórias e insights extraídos.  
📁 `script/` → Scripts Python para coleta de dados da **Riot Games API**.  

---

## Tecnologias e Pré-requisitos  

Para rodar este projeto, você precisará do **Python 3.9+** e das seguintes bibliotecas:  

### Bibliotecas utilizadas  
- `pandas` → Manipulação e análise dos dados.  
- `requests` → Requisições para a Riot Games API.  
- `seaborn` e `matplotlib` → Visualização de dados.  

Instalação das dependências:  
```bash
%pip install pandas requests seaborn matplotlib
```

---

## Contexto da Análise  

O objetivo desta análise é entender os principais fatores que levam às minhas derrotas, ajudando a aprimorar minha performance no jogo.

A abordagem inclui:

### Análise Exploratória  
- Identificação dos modos de jogo, lanes e campeões com maior taxa de derrotas.  
- Análise da relação entre mortes, assistências e ouro ganho em partidas perdidas.  
- Avaliação do tempo de jogo e sua correlação com derrotas.  

### Identificação de Padrões  
- Impacto da posição jogada (lane) nas derrotas.  
- Comparação entre campeões para identificar quais tiveram menor taxa de vitória.  
- Eficiência no mid/late game, observando dificuldades na transição entre as fases da partida.  

---

## 📈 Principais Insights  

- A maioria das derrotas ocorreu entre **16 e 33 minutos**, sugerindo dificuldades na transição do **mid para o late game**.  
- **BOT** foi a lane em que tive o maior número de derrotas, indicando um ponto crítico a ser melhorado.  
- Campeões jogados na função de **suporte** apresentaram uma alta taxa de derrotas, sugerindo a necessidade de ajustes na estratégia, na escolha de campeões ou na tomada de decisões dentro do jogo.  
- Partidas em que tive um alto número de mortes no **early game** resultaram frequentemente em um **snowball adversário**, aumentando a probabilidade de derrota.

---

## Resultado
- Quando fiz essa análise, eu estava no Diamante III. Após finalizá-la e seguir os insights gerados, alcancei o Grão-Mestre (segundo maior elo do jogo).
