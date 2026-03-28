# projeto-em-python
projeto realizando na faculdade como projeto de aprimoramento 
import matplotlib.pyplot as plt
import numpy as np

def gerar_dados_normal():
    return np.random.normal(loc=50, scale=100, size=1000)

# Chama a função para gerar os dados
dados = gerar_dados_normal()

# Plota o histograma dos dados
plt.hist(dados, bins=30)
plt.title("Distribuição Normal")
plt.xlabel("Valores")
plt.ylabel("Frequência")
plt.show()
