import math
print("-"*36)
print("Escreva as notas do aluno em formato FLOAT ou INT (ex: 0.0 ,3.4 ,4 ,etc...)\n"
      "Caso sejam notas com decimais.")
print("-" * 36)

aluno = 1

while aluno <= 100:

    print("Aluno", aluno)
    user = input("Digíte o nome do aluno: ")
    AOP1 = float(input('Digíte a nota da AOP1 [0 a 2 pontos]: '))
    while AOP1 < 0 or AOP1 > 2:
        AOP1 = float(input('Nota inválida! \n'
                           'Digíte novamente a nota da AOP1 [0 a 2 pontos]: '))

    AOP2 = float(input('Digíte a nota da AOP2 [0 a 1 ponto]: '))
    while AOP2 < 0 or AOP2 > 1:
        AOP2 = float(input('Nota inválida! \n'
                           'Digíte novamente a nota da AOP2 [0 a 1 ponto]: '))

    AOP3 = float(input('Digíte a nota da AOP3 [0 a 2 ponto]: '))
    while AOP3 < 0 or AOP3 > 2:
        AOP3 = float(input('Nota inválida! \n'
                           'Digíte novamente a nota da AOP3 [0 a 2 ponto]: '))

    Regular = float(input('Nota prova regular [0 a 5 pontos]: '))
    while Regular < 0 or Regular > 5:
        Regular = float(input('Nota inválida! \n'
                              'Digíte novamente a nota prova regular [0 a 5 pontos]: '))

    SM = AOP1 + AOP2 + AOP3 + Regular

    print("A nota final do aluno é: ", SM)
    print("-"*36)

    if SM == 7:
        media =+ 1
        print("Na Média")
        print("-" * 36)

    elif SM >= 7:
        print("Aprovado")
        print("-" * 36)

    else:
        print("O aluno está de recuperação.")
        print("-" * 36)

        Prova = float(input("Qual o resultado da prova de recuperação [0 a 10 pontos]? "))
        while Prova < 0 or Prova > 10:
            Prova = float(input("Valor incorreto! \n"
                                " Digíte novamente qual o resultado da prova de recuperação[0 a 10 pontos]?  "))

        res = (Prova + SM) / 2

        print("Valor da média da prova de recuperação: ", res)

        if res == 5:
            print("-" * 36)
            print("Na média")

        elif res >= 5:
            print("-" * 36)
            print("Aprovado")

        else:
            print("-" * 36)
            print("O aluno foi reprovado!")

print("-" * 36)

aluno =+ 1
