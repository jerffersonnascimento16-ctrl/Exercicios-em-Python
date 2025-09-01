Exercícios em Python 🐍
Repositório criado para guardar exercícios e pequenos programas desenvolvidos durante meus estudos de Python.

from random import randint
from time import sleep
computador = randint(0,5)
print("Tente advinha um número de 0,5")
numero = int(input("Qual o número que estou pensando? "))
print("PROCESSANDO...")
sleep(2)
if numero == computador:
    print("Acertou, Parabéns voçê ganhou")
else:
    print(f"Errou, Eu pensei no {numero} dessa vez eu ganhei")
