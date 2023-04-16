# trabalho_python
Lógica 

Trabalho sobre Controle de decisão

Grupo: Lara e Mariel

Autor: Herbert Schildt
Nome do livro: Java para iniciantes 6° edição, Crie, compile, execute programas Java rapidamente
Capitulo 3: Intruções de controle de programa.
Página: 67

Reformulado de Java para Python.

Código em Python: 

resp = 5
contador = 0

while True:

    print("\n ********************************************* ")
  
    print("\n Adivinhe um número de 0 a 10: ")

    num = int(input("\n Digite o número que você acha que é: "))

    contador += 1

    if num == resp:
        print(f"\n Parabéns! Você acertou em {contador} tentativas.")
        break

    elif num >= 0 and num <=5:
      print(f"\n A quantidade foi de {contador} tentativas.")
      print("\n Você está longe, muito baixo, tente de novo.")

    elif(num >= 6 and num <=10):
      print(f"\n A quantidade foi de {contador} tentativas.")
      print("\n Você está longe, muito alto, tente de novo.")
      
    else:
      print(f"\n A quantidade foi de {contador} tentativas.")
      print("\n Você está digitando algo que não faz parte do conjunto de 0 a 10, tente de novo")