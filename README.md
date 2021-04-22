# Programação-em-Python

**Estudos de programas simples em python de alguns cursos que realizo.**


# Exercício 1  

**Era necessário neste exercício proposto criar um input para receber o valor através do usuário.**


quadrado_lado = input("Digite o valor do lado de um quadrado:")

lado = int(quadrado_lado)

perimetro =(lado+lado)

area = (lado*lado)

print("perimetro:",perimetro,"- área:",area)


# Exercício 2

**Neste exercício foi solicitado a entrada de valores pelo usuário sobre o vencimento e mês de fatura a fim de que possa imprimir elas.**

Nome_Cliente = input("Digite o nome do cliente:")

Dia_Vencimento = input("Digite o dia de vencimento:")

Mes_Vencimento = input("Digite o mês de vencimento:")

Valor_Fatura = input("Digite o valor da fatura:")

print("Olá, ", Nome_Cliente,

      "\n A sua fatura com vencimento em ",

      Dia_Vencimento, Mes_Vencimento,"no valor de R$",Valor_Fatura,"está fechada.")
      
  # Exercício 3 
  
**Na realização deste programa era necessário fazer a entrada das 4 notas e eu utilizei o input para fazer, depois transformá-las em números inteiros e realizar o cálculo com suas variáveis atribuídas a media.**

      primeira_nota = input("Digite a primeira nota:" )

      segunda_nota = input("Digite a segunda nota: ")

      terceira_nota = input("Digite a terceira nota: ")

      quarta_nota = input("Digite a quarta nota: ")


      nota1 = int(primeira_nota)

      nota2 = int(segunda_nota)

      nota3 = int(terceira_nota)

      nota4 = int(quarta_nota)

      media = (nota1 + nota2 + nota3 + nota4)/4
      print("A média aritmética é", media)
