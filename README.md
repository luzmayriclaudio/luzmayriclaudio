-
Algoritmo calculadora_luz
	Definir num1,odcion,num2,resultado como real
	Definir seguir Como entero 

		Limpiar Pantalla
		Escribir " Bienvenido a calculadora luz"
		Escribir "1. suma"
		Escribir"2. resta" 
		Escribir "3.multiplicacion"
		Escribir "4. divicion"
		Escribir "5. potencia"
		Escribir "6. raiz cuadrada"
		Escribir "7. seno"
		Escribir "8. coseno"
		Escribir "9. tangente"
	Escribir "Seleccionar una opcion"
		leer odicion 
		Segun odicion Hacer
			1:
				Escribir " ingrese el primer numero"
				leer num1
				Escribir "ingrese el segundo numero"
				Leer num2
				resultado= num1 + num2
				Escribir " el resultado de la suma  es  ", resultado
			2: 
				
		     Escribir " ingrese el primer numero"
		     Leer num1
		     Escribir "ingresa el segundo numero"
		     leer num2
		     resultado= num1 - num2
		     Escribir "el resultado de la rescta es", resultado
	      3:
			 Escribir "ingrese el primer numero"
			 Leer num1
			 Escribir "ingrese el segundo numero"
			 leer num2
			 resultado= num1* num2
			 Escribir "el resultado de la multiplicacion es", resultado
		  4:
			 Escribir " ingresa el primer numero"
			 Leer num1
			 Escribir " ingresa el segundo numero"
			 Leer num2
			 resultado= num1/num2
			 Escribir " el resultado de la divicion es", resultado
		  5:
			  Escribir "ingrese el primer numero"
			 Leer num1
			 Escribir "ingrese el segundo numero"
			 leer num2
			 resultado= num1 ^ num2
			 Escribir "el resultado de la potencia  es", resultado
		  6:
			 Escribir "ingrese el primer numero"
			 Leer num1
			 resultado=raiz(num1)
			 Escribir "el resultado de la raiz", resultado
		 7:
			 Escribir "ingrese el primer numero"
			 Leer num1
			 resultado=sen(num1)
			 Escribir "el resultado de seno es ", resultado
		  8:
			 Escribir "ingrese el primer numero"
			 Leer num1
			 resultado=cos(num1)
			 Escribir "el resultado de coseno es ", resultado
		  9:
			 Escribir "ingresa el primer numero"
			 Leer num2 
			 resultado=tan(num2)
			 Escribir "el resultado tangente", resultado
			 
			 
