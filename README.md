## 📍 Introdução
Os dados disponibilizados são referentes aos estudantes PCDs da UFCG, tendo dados referentes até o ano de 2024.

## 🔗 Utilização 
Para acessar os dados na forma de URL e utilizar em plataformas como Google Colab é necessário utilizar: 
```python
import pandas as pd

url = "https://raw.githubusercontent.com/PaqTcPB-Inclui-UFCG/dados/refs/heads/main/dados.csv"
dados = pd.read_csv(url)
dados.head()
```
