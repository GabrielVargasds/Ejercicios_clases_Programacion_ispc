# Ejercicios_clases_Programacion_ispc

###  BEJERCICIO 1:
* Un estudiante está cursando 5 materias, tiene la nota de cada materia y quiere saber cuál es su promedio

**Inicio**
Materia 1 = ingreso la nota con datos  int // variable

Materia 2 = ingreso la nota con datos  int// variable

Materia 3 = ingreso la nota con datos  int // variable

Materia 4 = ingreso la nota con datos  int // variable

Materia 5 = ingreso la nota con datos  int// variable 

Total de materias = 5 dato int // Constante definida por el problema

Calculo:  (Materia 1+Materia 2 + Materia 3 +Materia 4 + Materia 5)/Total de materias

**Fin**

Algoritmo Promedio_5_materias

	Definir nota_1, nota_2, nota_3, nota_4, nota_5, materias Como Entero
 
	Escribir 'Ingrese nota 1'
 
	Leer nota_1
 
	Escribir 'Ingrese nota 2'
 
	Leer nota_2
 
	Escribir 'Ingrese nota 3'
 
	Leer nota_3
 
	Escribir 'Ingrese nota 4'
 
	Leer nota_4
 
	Escribir 'Ingrese nota 5'
 
	Leer nota_5
 
	materias <- 5
 
	Promedio <- ((nota_1+nota_2+nota_3+nota_4+nota_5)/materias)
 
	Escribir 'El promedio es ', Promedio
 
Fin del Algoritmo


![Diagrama de Flujo](IMAGENES/pseint%201.png)

# Ejercicio 2
 
### 1)- **Analisis del problema**:

Un pintor de casas debe hacer un presupuesto para un cliente. Lo que cobra se calcula de acuerdo a los metros cuadrados que debe pintar. El cliente le indica que necesita conocer el costo de mano de obra para pintar una pared rectangular de un galpón. El pintor cobra un monto fijo por cada metro cuadrado.

**Datos a ingresar:** 
•	Alto y ancho de a pared
•	Precio que cobra por metro cuadrado

**Proceso:** 
Debo calcular la superficie de la pared y multiplicarlo por el precio de la mano de obra por metro cuadrado

**Datos de salida:** el precio de la mano de obra.



### 2) – PSeudocódigo 

1)	**Declarar variables:**
Alto = valor int

Ancho = valor int

Precio_metro_cuadrado = valor int (para redondear usamos valores enteros)

3)	**Ingreso Alto**
4)	**Ingreso Ancho**
5)	**Ingreso Precio_metro_cuadrado**
6)	**Calculo:**  Alto *Ancho * Precio_metro_cuadrado
7)	**Mostrar Calculo**

### 3)	Diagrama de flujo


![Diagrama de flujo](IMAGENES/Ejercicio2.png)



# Ejercicio 3

**Analisis:**
Un hincha de fútbol desea conocer la cantidad de puntos que su equipo lleva acumulados en el campeonato, para ello recibe cada semana la información de la cantidad total de partidos, desde el inicio del campeonato, que el equipo ha perdido, ha empatado y ha ganado. Por cada partido empatado recibe un punto, por cada partido ganado tres puntos y por los perdidos cero puntos.
Datos de entrada:

•	Partidos ganados, empatados y perdidos // datos enteros variables
•	Nombre del equipo de futbol // dato string
•	Constantes:
 * puntos de partidos ganados = 3 // dato entero
   
* puntos partidos empatados = 1 // dato entero
  
* puntos partidos perdidos = 0 // dato entero
  
**Proceso:** 
Debo elegir un equipo y sumar el total de partidos ganados multiplicado por la cantidad de puntos correspondientes y del mismo modo sumarle los partidos empatados y perdidos.

**Salida:**
El total de puntos por equipo elegido. 


### Pseudocódigo
1)	Declarar variables:
* Pganados = int 
* Pempatados = int
* Pperdidos = int

2)	Declaro constantes
* Gana = 3
* Empata = 1
* Pierde = 0

3)	Realizo calculo de puntos
* Resultado = (Pganados*gana + Pempatados*empata + Pperdidos*pierde)
  
4)	Muestro resultados


![Diagrama de flujo](IMAGENES/Ejercicio3.png)


# Desafio Casa de Cambio

**Analisis:**
se necesita un programa que convierta un monto en pesos argentinos a dólares. El tipo de cambio utilizado es $890 pesos argentinos por 1 dólar.

**Datos de entrada:**

Variables:

•	Monto en pesos = dato tipo float

* Constantes: valor del dólar en pesos = dato tipo float
  
**Proceso:** 
* Ingresar monto en pesos 
* Calcular cambio: Monto en pesos / valor dólar
* Presentar resultados
**Datos de salida:**
   monto equivalente en dólares, dato float

**Pseudocodigo**
1)	Declarar variables, monto en pesos
2)	Declara constantes
3)Ingresar monto en pesos
4)Calcular cambio



