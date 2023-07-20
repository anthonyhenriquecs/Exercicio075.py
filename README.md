# Exercicio075.py

num = (int(input('Digite um numero:')),
        int(input('Digite um numero:')),
        int(input('Digite um numero:')),
        int(input('Digite um numero:')))
print(f'voce digitou: `{num}')
print(f'O numero 7 apareceu: {num.count(7)} vezes')
if 3 in num:
        print(f'O valor 3 apareceu na {num.index(3)+1} posição')
else:
        print('O valor 3 nao foi digitado.')
print('Os valores pares digitados foram: ',end=' ')
for i in num:
        if i % 2 == 0:
                print(i,end=' ')
