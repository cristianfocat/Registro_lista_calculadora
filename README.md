def som():
    soma=[]
    while True:
        print()
        n1=int(input('\033[32mdigite primeiro numero: \033[0m'))
        n2 = int(input('\033[33mdigite segundo numero: \033[0m'))
        n3=n1+n2
        soma.append(n3)
        print()
        print('Historico De Resultado: ',(soma))
        print()
        print('[s]-Sim\n[n]-Não\nAperte qualquer Tecla Para Voltar Ao Menu')
        con=input('Deseja continuar?: ').strip().lower()
        match con:
            case 's':
                continue
            case 'n':
                print('\033[35mAté A Próxima😁😁😁\033[0m')
                exit()
            case _:
                escolha()


def subtracao():
    sub=[]
    while True:
        print()
        n1=int(input('digite primeiro numero: '))
        n2 = int(input('digite segundo numero: '))
        n3=n1-n2
        sub.append(n3)
        print()
        print('Historico De Resultado: ',sub)
        print()
        print('[s]-Sim\n[n]-Não\nAperte qualquer Tecla Para Voltar Ao Menu')
        con=input('Deseja continuar?: ').strip().lower()
        match con:
            case 's':
                continue
            case 'n':
                print('\033[35mAté A Próxima😁😁😁\033[0m')
                exit()
            case _:
                escolha()

def divisao():
    div=[]
    while True:
        print()
        n1=int(input('digite primeiro numero: '))
        n2 = int(input('digite segundo numero: '))
        n3=n1/n2
        div.append(n3)
        print()
        print('Historico De Resultado: ',div)
        print()
        print('[s]-Sim\n[n]-Não\nAperte qualquer Tecla Para Voltar Ao Menu')
        con=input('Deseja continuar?: ').strip().lower()
        match con:
            case 's':
                continue
            case 'n':
                print('\033[35mAté A Próxima😁😁😁\033[0m')
                exit()
            case _:
                escolha()

def multiplicacao():
    mult=[]
    while True:
        print()
        n1=int(input('digite primeiro numero: '))
        n2 = int(input('digite segundo numero: '))
        n3=n1+n2
        mult.append(n3)
        print()
        print('Historico De Resultado: ',mult)
        print()
        print('[s]-Sim\n[n]-Não\nAperte qualquer Tecla Para Voltar Ao Menu')
        con=input('Deseja continuar?: ').strip().lower()
        match con:
            case 's':
                continue
            case 'n':
                print('\033[35mAté A Próxima😁😁😁\033[0m')
                exit()
            case _:
                escolha()

def potencia():
    pot=[]
    while True:
        print()
        n1=int(input('digite primeiro numero: '))
        n2 = int(input('digite segundo numero: '))
        n3=n1**n2
        pot.append(n3)
        print()
        print('Historico De Resultado: ',pot)
        print()
        print('[s]-Sim\n[n]-Não\nAperte qualquer Tecla Para Voltar Ao Menu')
        con=input('Deseja continuar?: ').strip().lower()
        match con:
            case 1:
                continue
            case 2:
                print('\033[35mAté A Próxima😁😁😁\033[0m')
                exit()
            case _:
                escolha()



def escolha():
    print()
    print('\033[35m==========Escolha Uma Operação==========\033[0m')
    print('[1]-\033[33mSoma\033[0m\n[2]-\033[33msubtração\033[0m\n'
          '[3]-\033[33mDisisão\033[0m\n[4]-\033[33mMultiplicação\033[0m\n'
          '[5]-\033[33mPotência\033[0m\n[6]-\033[33mSair\033[0m')
    print()
    escolha1=int(input("Escolha Uma Alternativa!: "))
    print()
    match escolha1:
        case 1:
            som()
        case 2:
            subtracao()
        case 3:
            divisao()
        case 4:
            multiplicacao()
        case 5:
            potencia()
        case 6:
            print('\033[35mAté A Próxima😁😁😁\033[0m')
            exit()
        case _:
            print('\033[31m===== Operação Não Encontrada! =====\033[0m')
            print()
            escolha()

escolha()
