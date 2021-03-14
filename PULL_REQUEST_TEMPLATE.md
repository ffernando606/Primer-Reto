# Information

- Nombre: <ffernando606>
- Usuario Discord: <ffernando#0643>
- Grupo de Lectura: <Grupo de Lectura Nº 8>

# Solución

Una descripción clara y concisa sobre la solución al reto.
Si el reto consta de varios ejercicios agrega cada solución por separado por ejemplo:

1. Ejercicio 1: ¿Qué valor tendrá numero_1 al final del script?

La varible numero_1 será igual a 2 ya que la condición del condicional IF no se cumple.

2. Ejercicio 2: ¿Qué valor tendra numero_4 al final del script?

La variable numero_4 valdrá 7, siendo totalmente independiente a la variable del mismo nombre declarada en forma local dentro del condicional IF.

3. Ejercicio 3: Solución
El problema radica en que "value" está definido como una variable local y después es invocada como si fuera global. 

Otro problema notable es que la condición (key==22) nunca se cumple por lo tanto por lo tanto todos lo que está dentro nunca se ejecuta.

A su vez existe otro problema, es el caso de la asignación de value que se la incrementa en 1, se muestra en consola para luego hacer un decremento de 1 y volver a mostrar en consola sin motivo aparente.
