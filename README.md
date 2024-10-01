# uml-Iphone-
implemento em uml do iphone (estudo)
[Iphone UML](java\estudo\estudo\uml-Iphone-\ClasseUML.png)
classDiagram class ReprodutorMusical { +tocar() +selecionarMusica(musica: Sting) } class AparelhoTelefonico { +ligar(numero: String) +atender() +iniciarCorreioVoz() } class NavegadorInternet { +exibirPagina(url: String) +adicionarNovaPagina() +atualizarPagina() } class iPhone { } iPhone --> ReprodutorMusical iPhone --> AparelhoTelefonico iPhone --> NavegadorInternet