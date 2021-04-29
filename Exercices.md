# Affecter, écrire et lire dans un algorithme////


### Exercice 1 :

	## Algorithme HelloWorld

	Variables

	 firstWord : string

	 secondWord : string

	**Instructions**

	 firstWord <- "Hello"

	 secondWord <- "World"


### Exercice 2 :

	## Algorithme Bonjour

	Variables

 	 name : string 
	
	**Instructions**

 	 Write("Quel est votre nom ?")
 
 	 Read(name)
 
 	 Write("Bonjour" name "!")


### Exercice 3 :

	168


# Les Conditions


### Exercice 1 :

	## Algorithme Users

	Variables 

	 age : integer
 
	 gender : string

	**Instructions** 

 	   Write("Quel est votre age ?")
 
 	   Read(age)
 
 	   Write("Quel est votre genre ?")
 
 	   Read(gender)

 	  if age >= 18 and gender == "homme" then 

 	  	Write("Vous êtes un homme et vous êtes majeur")

   	  Else 

  	  	Write("Vous êtes un homme et vous êtes mineur

 	  ElseIf age >= 18 and gender == "femme" then 

  	 	 Write("Vous êtes une femme et vous êtes majeure")

 	  Else 

  	  	Write("Vous êtes une femme et vous êtes mineure")

	  EndIf



### Exercice 2 :

	## Algorithme MultipleOfFour

	Variables
 
	 number1 : integer
 
 	 number2 : integer
 
 	 result : float

	**Instructions**

	   Write("Premier chiffre :")
 
 	   Read(number1)
 
 	   Write("Deuxieme chiffre :")
 
 	   Read(number2)
 
 	   result <- number1 / number2

	  if result % 4 == 0

  	  	Write("Oui")
 
 	  Else 

		Write("Non") 

	  EndIf


### Exercice 3 :

	Surveillez votre poids, votre IMC est de : 27.94645772118838


# Les boucles


### Exercice 1 :

	## Algorithme Count
	
	Variables
	
	  count : integer
	  
	**Instructions**
	
	  count <- 0
	  
	  For count from 0 to 30 with a step of 5
	  
	  	if count % 2 == 0 then 
			
			Write(count)
		Else 
			Write("Oops")
			
		EndIf
	  EndFor
		

### Exercice 2 :

	## Algorithme BankAccount
	
	Variables
	
	  bankAccount : float
	
	**Instructions**
	
	  bankAccount <- 526
	  
	  While bankAccount > 0 do 
	  
	  	bankAccount <- bankAccount - 50
		
		Write("Il vous reste" bankAccount "sur votre compte")
	
	  EndWhile
	  
	  
### Exercice 3 :

	calc = 55
	  
	  
# Les structures de données (tableaux)


### Exercice 1 :

	##Algorithme Multiply
	  
	Variables
	
	  numbers[10] : integer array
	  
	  resultCalc : integer
	  
	  count : integer
	  
	**Instructions**
	
	  resultCalc <- 1
		  
	  numbers[] <- numbers[5, 56, 250, 12, 2, 99, 78, 465, 123, 195]
	  
	  For count from 0 to 9
	  
	  	resultCalc <- resultCalc * numbers[count]
		
	  EndFor
	  	  

### Exercice 2 :


	##Algorithme Multiply
	  
	Variables
	
	  clients[5] : array of date arrays
	
	  count : integer
	  
	  secondCount : integer	  
	
	**Instructions**
	
	  clients[0] <- client[prenom0, nom0, email]
	  
	  clients[1] <- client[prenom1, nom1, email]
	  
	  clients[2] <- client[prenom2, nom2, email]
	  
	  clients[3] <- client[prenom3, nom3, email]
	  
	  clients[4] <- client[prenom4, nom4, email]
	  

	  For count from 0 to 4
	  	
		For secondCount from 0 to 2
		
			Write(clients[count][secondCount])
			
	  	EndFor
	  
	  secondCount <- 0
	  
	  EndFor

## Exercice 3 : 

	une erreur
	  
	
	  
