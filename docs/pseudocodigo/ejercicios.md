# Ejercicios
  

## Crear un algoritmo que pida un nombre por consola y retorne el saludo “Estimado {{nombre ingresado}}"
  

Solución  

```java
Proceso ejercicio1
	
	Definir nombre Como Caracter;
	Escribir "Ingresar el nombre";
	Leer nombre;
	
	Escribir "Estimad@" + " " + nombre;

FinProceso
```

## Crear un algoritmo que sume tres números ingresados por consola e imprima su resultado.
  
  
Solución
```java
Proceso ejercicio2
	
	Definir num1, num2, num3, resultado Como Entero;

	Escribir "ingresar el primer nUmero";
	Leer num1;
	
	Escribir "ingresar el primer nUmero";
	Leer num2;
	
	Escribir "ingresar el primer nUmero";
	Leer num3;
	
	resultado = num1 + num2 + num3;
	
	Escribir "El resultado es: " + ConvertirATexto(resultado);
	
FinProceso
```

## Crear un algoritmo que reste dos números ingresados por consola e imprima sus resultados.
  
  
Solución
```java
Proceso ejercicio2
	Definir num1, num2, resultado Como Entero;
	
	Escribir "Ingresar el primer nUmero";
	leer num1;
	
	Escribir "Ingresar el segundo nUmero";
	leer num2;
	
	resultado = num1 - num2;
	
	escribir "El resultado es: " + ConvertirATexto(resultado);
	
FinProceso
```

## Crear un algoritmo que divida dos números y entregue su resultado en decimales.
> hint: trabajar con números reales y no enteros.
  
  
Solución
```java
Proceso ejercicio4
	Definir num1, num2, resultado Como Real;
	
	Escribir "ingrese el primer nUmero";
	Leer num1;
	
	Escribir "ingrese el segundo nUmero";
	Leer num2;
	
	resultado = num1 / num2;
	
	Escribir "El resultado es: " + ConvertirATexto(resultado);
	
FinProceso
```
## Crear un algoritmo que  pida un número por consola e imprima si el número ingresado es par o impar.
hint: La función módulo, indica el resto de la divición (entera) entre dós números:

4 dividido 2, el resultado es 2 y el resto es cero. 

3 dividido 4, no hay resultado entero y el resto es 3, es decir, el mismo número que estamos dividiendo.

// Usando la función mod:

4 mod 2 = 0
3 mod 4 = 3
  
  
Solución
```java
Proceso ejercicio4
	Definir num1 Como Real;
	Definir esPar Como Logico;
	
	Escribir "ingrese el primer nUmero";
	leer num1;
	
	esPar = (num1 mod 2) == 0;
	
	si(esPar) entonces
		Escribir "El nUmero : " + ConvertirATexto(num1) + " es par";
	SiNo
		Escribir "El nUmero : " + ConvertirATexto(num1) + " no es par";
	FinSi

FinProceso
```
  
## Crear un algoritmo que  pida dos números por consola e imprima el mayor.
  
  
Solución
```java
Proceso ejercicio5
	Definir num1, num2 Como Entero;
	
	Escribir "ingrese el primer nUmero";
	Leer num1;
	
	Escribir "ingrese el segundo nUmero";
	Leer num2;
	
	si(num1 > num2) entonces
		Escribir convertirATexto(num1) + " es mayor al " + convertirATexto(num2);
	siNo
		si(num1 < num2) Entonces
			Escribir convertirATexto(num2) + " es mayor al " + convertirATexto(num1);
		SiNo
			Escribir "Los nUmeros son iguales";
		FinSi
	FinSi
FinProceso
```
  
## Crear un algoritmo que  realice la tarea anterior pero esta vez con tres números.
  
  
Solución
```java
Proceso ejercicio5
	Definir num1 Como Entero;
    Definir num2 Como Entero;
	Definir num3 Como Entero;
	Definir mayor Como Entero;
	
	Escribir "ingrese el primer nUmero";
	Leer num1;
	
	Escribir "ingrese el segundo nUmero";
	Leer num2;
	
	Escribir "ingrese el tercer nUmero";
	Leer num3;
	
	si(num1 > num2 y num1 > num3) entonces
		mayor = num1;
	FinSi
	
	si(num2 > num1 y num2 > num3) entonces
		mayor = num2;
	FinSi
	
	si(num3 > num1 y num3 > num2) entonces
		mayor = num3;
	FinSi
	
	si(num3 == num1 y num3 == num2) entonces
		Escribir "los nUmeros son iguales";
	SiNo
		Escribir " el mayor es: " + convertirATexto(mayor);
	FinSi
	
FinProceso
```
 