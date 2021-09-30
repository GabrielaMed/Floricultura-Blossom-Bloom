# Floricultura-Blossom-Bloom

programa {
	funcao inicio() 
	{
	
		cadeia  nome, endereco, nomeProd, tipoProd
		inteiro rg, telefone, enderecoNum, estoqueProd, op
		real valorProd
		
		escreva ("----------------------------- Menu -----------------------------")
		escreva ("\n1.Cadastrar Produto   	2.Cadastrar Cliente\n")
		leia (op)
	    
	    limpa()
	    
	    escolha (op)
	    {
		    caso 1:
        escreva("Vamos começar o cadastro de seu produto.\nInsira o nome do prduto: ")
        leia(nomeProd)

         escreva("Digite o tipo do produto: ")
		     leia(tipoProd)
			
		    escreva("Digite o valor do produto: ")
		   	leia(valorProd)
			
		   	escreva("Insira a quantidade disponível em estoque do produto: ")
		    leia(estoqueProd)
			
		   	escreva("Cadastro concluído com sucesso. Obrigada pelas informações tenha uma ótima navegação pelo nosso site.")
    	    
        pare
    	    
	        caso 2:
          escreva ("\nBem vindo, vamos começar seu cadastro: \nDigite seu Nome Completo: ")
    	  	leia (nome)
		
		      escreva ("Nos informe o número de seu RG: ")
          leia(rg)
		  
          escreva ("Seu número de telefone: ")
          leia (telefone)
		
		      escreva ("Digite o nome da rua onde você reside: ")
		      leia(endereco)
		
		      escreva("número: ")
		    	leia (enderecoNum)
			
		      escreva("Cadastro concluído com sucesso. Obrigada pela informações, tenha uma ótima navegação pelo nosso site.")
	        pare
	    }
	    
	}
}
