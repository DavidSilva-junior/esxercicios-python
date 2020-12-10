#Faça um programa que leia se um  ano é bissexxto

ano = int(input('digite o ano: '))

if ano % 4 == 0 and ano % 100 != 0:
    print('ano  bissexto')
else:
    print('ano não bissexto')
