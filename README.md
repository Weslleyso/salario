salario = float(input('digite seu salário: '))

if salario >= 1250:
    print('salario aumentado em 10%')
    porcentagem = (salario)*10/100
    aumento = salario + porcentagem 
    print(f'seu salario agora é de {aumento:7.2f} reais')  

else:
    print('salário aumentado em 15%')
    porcentagem = (salario)*15/100
    aumento = salario + porcentagem 
    print(f'seu salario agora é de {aumento:7.2f} reais')    
