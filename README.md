// # atividades-faculdade
// atividades da faculdade ponto com
// aaa
programa {
  funcao inicio() {
    cadeia nom, resposta
    escreva ("Adicione seu nome\n")
    leia (nom)
    escreva ("você se chama ", nom, ", correto?")
    leia (resposta)
    se (resposta == "sim"){
      escreva ("ok, iniciando o programa")
    pare} se (resposta == "não"){
      escreva ("então, adicione o seu nome novamente")
    } senao {
      escreva("comando incorreto, escreva com apenas 'sim' ou 'não'")
    } escreva ("o programa será aberto, carregando.\ncarregando..\ncarregando...")
  }
}

