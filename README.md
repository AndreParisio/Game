# Game

import pandas as pd

dados = [
    ["jogo", 1, 2, 3, 4],
    ["placar", 12, 24, 10, 24],
    ["mininmo temporada", 12, 12, 10, 10],
    ["máximo temporada", 12, 24, 24, 24],
    ["Quebra recorde mínimo", 0, 0, 1, 1],
    ["Quebra recorde máximo", 0, 1, 1, 1]
]

df = pd.DataFrame
N1 = int(input('insira o último placar:'))
N2 = int(input('insira o último recorde máximo:'))
N3 = int(input('insira o último recorde minimo:'))
print(dados)
