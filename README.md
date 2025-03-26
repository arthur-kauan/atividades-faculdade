// # atividades-faculdade
// atividades da faculdade ponto com
// aaa
programa {
  funcao inicio() {
    cadeia nomi, resposta
    escreva ("Adicione seu nome\n")
    leia (nomi)
    escreva ("você se chama ", nomi, ", correto?")
    leia (resposta)
    se (resposta == "sim"){
      escreva ("ok, iniciando o programa")
    pare} se (resposta == "não"){
      escreva ("então, adicione o seu nome novamente")
    } senao {
      escreva("comando incorreto, escreva com apenas 'sim' ou 'não'")
    }
  }
}

