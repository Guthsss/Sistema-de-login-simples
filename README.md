# Sistema-de-login-simples
Estúdio Portugol

    programa {
      funcao inicio() {
    
      	cadeia senha
      	cadeia email
    
      	escreva("Digite seu email: ")
      	leia(email)

      	escreva("Digite a sua senha: ")
      	leia(senha)
  
      	se(email == "guthsgregory@gmail.com") {
    	  	escreva("O seu email está correto")
      	} senao {
      		escreva("O seu email está incorreto")
      	}

        se(senha == "cachorroCaramelo") {
        	escreva(" e sua senha está correta")
      	} senao {
       	 escreva(" e sua senha está incorreta\n")
      	}
     	se(email == "guthsgregory@gmail.com" e senha == "cachorroCaramelo"){
     		escreva("\nSeja bem-vindo!")
     	} senao {
     		escreva("")
     }
    }
    }
