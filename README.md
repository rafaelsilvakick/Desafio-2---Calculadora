# Desafio-2---Calculadora

programa {
  funcao inicio() {
    
  inteiro n1, n2, resp, op
    caracter repita
    enquanto (repita != "n"){

    escreva("Digite um número: ")
    leia (n1)

    escreva("Digite outro número: ")
    leia (n2)

    escreva ("--- Operadores --- \n")
    escreva ("1 - Soma \n")
    escreva ("2 - Subtração \n")
    escreva ("3 - Multiplicação \n")
    escreva ("4 - Divisão \n")

    escreva( "Digite o número do operador: ")
    leia (op)

    escolha (op){

     caso 1:
        resp = n1 + n2
        escreva(n1, " + ", n2, " = ", resp)
        pare

      caso 2:
        resp = n1 - n2
        escreva(n1, " - ", n2, " = ", resp)
        pare

      caso 3:
        resp = n1 - n2
        escreva(n1, " * ", n2, " = ", resp)
        pare

      caso 4:
        resp = n1 - n2
        escreva(n1, " / ", n2, " = ", resp)
        pare

      caso contrario
        escreva("Opção inválida!")
    }

    escreva ("\nDeseja fazer outra conta? (s/ n): ")
  
    leia (repita)
}
