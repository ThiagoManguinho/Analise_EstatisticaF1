<h1>🏎️ Análise de Pit Stops de Fórmula 1</h1>

Este projeto analisa dados de pitstops na Fórmula 1, explorando estatísticas e probabilidades relacionadas a equipes e pilotos.
O foco está nos dados dos anos 2000 - 2021, avaliando médias de tempo de pitstop e probabilidades de determinados eventos (ex.: uma equipe estar abaixo da média geral, ou um piloto específico realizar pitstops em determinada temporada).

<h2>📱 Tecnologias Utilizadas</h2>
Python 3<br>
Google Colab<br>
Bibliotecas:<br>
pandas<br>
numpy (opcional para estatísticas)<br>
matplotlib / seaborn (para gráficos, se adicionados)<br>

<h2>🚀 Como Executar</h2>
Recomendado no google colab<br>
Faça o download do arquivo csv: https://www.kaggle.com/datasets/alexandrucaian/f1-pitstop-data-2000-2021<br>
Passe esse arquivo para o colab<br>
Rode a célula com<br>

import pandas as pd
from google.colab import files
uploaded = files.upload()
