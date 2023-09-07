# Padroes_Projeto_Singleton

Garante que uma classe tenha somente uma instância, que é facilmente acessível. 


 Exemplo do War:
 No main está sendo instanciado vários objetos do tipo jogador que utiliza uma única instância da classe tabuleiro.
 Então, os jogadores usam apenas um tabuleiro. Para garantir que seja criado apenas uma única instância de tabuleiro, 
 a classe tabuleiro é escrita da seguinte forma:
 Possui um único atributo privado e estático da classe Tabuleiro chamado tabuleiro Único que está nulo; um construtor privado e um método público e estático ( getInstanciaTabuleiro )
 que tem uma condição ( if )que só cria uma instância se o atributo estático tabuleiro Único está nulo.
 

 
