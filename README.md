Tarea 1
Clase de programación 
1. Como podemos concatenar un numero a un string? (.5 punto) 
texto

juliette="aqui hay un numero "
resultado=juliette+str(21)
print(resultado)

 salida: aqui hay un numero 21


2. De que tipo son las variables justifica la respuesta (1.5 puntos)
 a = "1"  int
 b = 1.0 float
 c = 1.5 + True float
 d = 1.5 + 2.5 float
 e = 1 + True int
 f = False + True int
 g = True * 0  int


3. Manipulando la variable palabra (concatenando y con los metodos de strings), convertirla (2 puntos)


 a. cambiar algunas letras por numeros
	palabra = "hola" 
	en "Ho14"
"Hola".replace("a","4")
Salida: 'Hol4'

 b. remover espacios
	palabra = "  hola"
	en "hola"
•. "  hola".split()
     Salida: ['hola']
•. "  hola".strip()
     Salida:  'hola'


 c. cambiar mayusculas y minusculas
    palabra = "HoLa"
	en "hOlA"
"HoLa".swapcase()
Salida: 'hOlA'


 d. poner la primera en mayuscula
	palabra = "hola"
	en "Hola"
"hola".capitalize()
Salida: 'Hola'


4. Explica que hacen los metodos y da un ejemplo: (2 puntos)

 a. count() cuantas veces aparece una plabra en una cadena
 "hola esta es una oracion que hice hoy. hola profe".count("hola")
              salida: 2

 b. find() cuenta cuentos caracteres hay desde el inicio hasta la palabra 
"hola, esta es una oración que hice hoy".find("esta")
Salida: 6


 c. isdigit()Devuelve True si todos los caracteres de la cadena son dígitos.
Devuelve False si al menos uno de los caracteres de la cadena no es un dígito.

  •  Juliette="123456789"
      Juliette.isdigit()
        Salida: True
  • Viali="Julie"
     Viali.isdigit()
         Salida: False
       

 d. replace() remplaza caracteres por otros caracteres 
"Juliette".replace("t","7")
Salida:'Julie77e'



5. Que problema tiene declarar estas variables? (1.5 puntos)

• oracion larga = 'hola mundo' que el espacio hace que lo tome como dos variables
•  •palabra = 'hola' 'mundo' que falta el espacio cuando da salida 




6. Investigar "fstring": que son, como se usan y un ejemplo. (2.5 puntos
son cadenas formadas en las que puedes incluir variables y expresiones dentro de una cadena

nombre="Juliette"
edad=21
print(f"Hola, mi nombre es {nombre} y tengo {edad}")
    Salida: Hola, mi nombre es Juliette y tengo 21
