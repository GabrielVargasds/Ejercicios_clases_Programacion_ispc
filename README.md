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


#Ejercicio 2

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

