print("Este código te auxilia a saber sobre o alistamento militar no Brasil!")

i = float(input('digite sua idade'))
if i==18:
    print('A hora de se alistar é agora!')
elif 35>i>18:
    print('voce ainda pode se alistar')
    print('ainda tem:',35-i,'anos para se alistar')
elif i==35:
    print('Prazo maximo para se alistar')
elif i>35:
    print('O prazo para se alistar expirou')
    print('o prazo expirou a:',i-35,"ano(s)")
elif i<18:
    print('voce ainda nao tem idade minima para se alistar')
