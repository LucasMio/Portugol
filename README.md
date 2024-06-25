# Portugol
programa {
  funcao inicio() {
    inteiro idade, maior_idade, menor_idade

    para(inteiro cont = 1; cont <=6; cont++){
      escreva("digite a ", cont, "° idade: ")
      leia(idade)
      se(cont == 1){
        maior_idade = idade
        menor_idade = idade
      }senao{
        se (idade > maior_idade){
              maior_idade = idade
        }
        se (idade < menor_idade){
              menor_idade = idade
        }
      }
    }escreva("\n\n Maior idade ",  maior_idade)
     escreva("\n Menor idade ", menor_idade)
  } 
}
