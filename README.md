# Ice Games — Análise de Vendas e Identificação de Padrões de Sucesso no Mercado de Videogames

## Descrição do Projeto
Projeto de análise de dados aplicado à loja online Ice, que vende videogames no mundo todo. O objetivo principal foi identificar padrões que determinam se um jogo tem sucesso ou não, a partir de dados históricos de vendas, avaliações de usuários e especialistas, gêneros e plataformas — permitindo identificar possíveis sucessos e apoiar o planejamento de campanhas publicitárias.

---

## Metodologia
1. **Pré-processamento dos dados**
   - Limpeza e padronização de colunas, conversão de tipos de dados (`year_of_release` para inteiro, `user_score` para numérico) e tratamento de valores ausentes e entradas inválidas como `"TBD"`.
2. **Análise Exploratória de Dados (EDA)**
   - Análise de lançamentos por ano, distribuição de vendas por plataforma, correlação entre avaliações (profissionais e usuários) e vendas, e desempenho por gênero.
3. **Perfil regional de usuários**
   - Análise das top 5 plataformas e gêneros por região (América do Norte, Europa e Japão), além do impacto das classificações ESRB nas vendas regionais.
4. **Testes de hipóteses**
   - Aplicação do teste t de Welch para comparar classificações médias de usuários entre plataformas (Xbox One vs. PC) e entre gêneros (Action vs. Sports), com nível de significância de 5%.

---

## Principais Insights

- **Evolução das plataformas**
  Os lançamentos cresceram significativamente a partir de 1994, com pico no final da década de 2000. Novas plataformas levam em média 6 anos para surgir, enquanto as antigas levam em média 10 anos para desaparecer. No período recente (a partir de 2013), PS4 lidera em vendas, seguido por Xbox One.

- **Impacto das avaliações nas vendas**
  Avaliações de profissionais têm correlação maior com as vendas do que avaliações de usuários, com base na análise focada no PS4.

- **Gêneros mais rentáveis**
  Jogos de Ação, Shooter, Esportes e Role-Playing são os mais rentáveis globalmente. Simulação, Estratégia e Puzzle apresentam as menores vendas.

- **Perfis regionais distintos**
  - **América do Norte:** mercado equilibrado entre Xbox, PlayStation e Nintendo; gêneros Ação, Shooter e Esportes dominam.
  - **Europa:** PlayStation é predominante; Role-Playing e Corrida ganham mais relevância do que na América do Norte.
  - **Japão:** Nintendo 3DS lidera; Role-Playing é o gênero favorito com folga.

- **Classificação ESRB**
  Jogos com classificação M (Mature) lideram vendas na América do Norte e Europa. No Japão, jogos com classificação T (Teen) são os mais vendidos.

- **Testes de hipóteses**
  - As classificações médias de usuários entre Xbox One e PC **não apresentam diferença estatisticamente significativa** (hipótese nula não rejeitada).
  - As classificações médias de usuários entre os gêneros Action e Sports **são estatisticamente diferentes** (hipótese nula rejeitada).

---

## 📂 Conteúdo do Repositório

- **ice_games (.ipynb):** análise completa, incluindo pré-processamento, EDA, análise regional, testes de hipóteses e conclusões
- **README (.md):** este arquivo

---

## Tecnologias e Bibliotecas

- Linguagem: **Python**
- Bibliotecas: **pandas**, **numpy**, **matplotlib**, **seaborn**, **scipy**
- Notebook: **Jupyter Notebook**

---

## Contato

Willian De Souza Pereira — ws13292@gmail.com

LinkedIn: https://linkedin.com/in/willian-de-souza-pereira-b69109202

GitHub: https://github.com/willtrash

## Licença

Este repositório está disponível para estudo e demonstração. Sinta-se à vontade para clonar, adaptar e abrir *issues* com dúvidas ou sugestões.
