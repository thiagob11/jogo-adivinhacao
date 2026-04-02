# jogo-adivinhacao
Jogo simples de adivinhação em Python para praticar lógica de programação.
from random import randint
from time import sleep

print('_*'*30)
print('Vou pensar em um número entre 0 e 5, tente adivinhar!')
print('_*'*30)
n = int(input('digite o número entre 0 e 5:'))
print('PROCESSANDO...')
sleep(3)
nm = randint(1, 5)
print('Pensei no número: {}!'.format(nm))
if n == nm:
    print('você ganhou, PARABÉNS!')
else:
    print('Eu ganhei, tente mais uma vez!')
print('-='*30)