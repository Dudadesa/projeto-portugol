# projeto-portugol
Este projeto tem como objetivo a criação de uma aldeia interativa dentro do Minecraft education ,planejada para que os usuarios possan explorar e interagir
programa {
  funcao inicio() {
     cadeia presenca, periodo, planta

        escreva("Alguém na porta? (sim/nao): ")
        leia(presenca)
        se (presenca == "sim") escreva("Tocando a campainha.\n")
        senao escreva("Nenhuma ação.\n")

        escreva("É noite? (sim/nao): ")
        leia(periodo)
        se (periodo == "sim") escreva("Luzes acesas.\n")
        senao escreva("Luzes apagadas.\n")

        escreva("Planta pronta? (sim/nao): ")
        leia(planta)
        se (planta == "sim") escreva("Plantações colhidas.\n")
        senao escreva("Aguardando crescimento.\n")
    }
