programa {
	
  funcao inicio() 
  
  {
		
		cadeia nomes[5]
		caracter sexo[5]
		inteiro cont = 0
		
		enquanto(cont < 5){
		    
		    para(inteiro i = 0; i < 5; i++){
		        
		        escreva("Informe um nome: \n")
		        leia(nomes[i])
		        
		        escreva("Informe o sexo: (F/M)\n")
		        leia(sexo[i])
		        
		        enquanto(sexo[i] != 'F' e sexo[i] != 'M'){
		            
		            escreva("Informe um sexo válido: (F/M)\n")
		            leia(sexo[i])
		            
		        }
		        
		        cont++
		        
		    }
		    
		    limpa()
		    
		    para(inteiro i = 0; i < 5; i++){
		        
		        se(sexo[i] == 'F'){
		            escreva(nomes[i], "\n")
		        }
		        
		    }
		    
		    
		    para(inteiro i = 0; i < 5; i++){
		        
		        se(sexo[i] == 'M'){
		            escreva(nomes[i], "\n")
		        }
		        
		    }
		    
		}
		
	}
}
