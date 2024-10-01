# uml-Iphone-
implemento em uml do iphone (estudo)

```mermaid
classDiagram
    class ReprodutorMusical {
        +tocar()
        +pausar()
        +selecionarMusica(musica: String)

    }
    
    class AparelhoTelefonico {
        +ligar(numero: String)
        +atender()
        +iniciarCorreioVoz()
    }
    
    class NavegadorInternet {
        +exibirPagina(url: String)
        +adicionarNovaPagina()
        +atualizarPagina()
    }
    
    class iPhone {
    }

    iPhone --> ReprodutorMusical
    iPhone --> AparelhoTelefonico
    iPhone --> NavegadorInternet
