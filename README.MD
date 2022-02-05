# Lenguaje y automatas I

En este repositorio serán incluidos ejercicios correspondientes a la materia de lenguaje y automatas I
siguiendo el plan de estudio del sexto semestre de Ingeniería en sistemas computacionales, considerando el plan de 
estudio de TECNM.

## Notacíon para construir expresiones regulares

>La notación utilizada para construir expresiones regulares difiere a la notación utilizada por algunos
autores, para evitar confusiones se procede a describir la notación utilizada en estos ejercicios.
>
>- ***L***: Representa el lenguaje que será formado según el enunciado del ejercicio.
<br><br>
>- ***{}***: Entre llaves debe expecificarse el patrón con el que sera contruida la expresión regular.
<br><br>
>- ***[]***: Se utiliza para representar una concatenación opcional.
<br><br>
> - ***()***: Se utiliza para representar una concatenación obligatoria.
<br><br>
>- ***|*** : Se utiliza como el Operador lógico 'OR' para poder elegir un patrón dentro de una agrupación de patrones en una expresión regular.
<br><br>
>- ***\****: Se utiliza para indicar que pueden existir cero o más repeticiones.
<br><br>
>- ***+***: Se utiliza para indicar que deben existir una o más repeticiones. **Cuidado:** Al utilizar este operador se fuerza a que exista al menos una repetición del patrón especificado.
<br><br><br><br>
# <span style="color:#008BD8;">Ejemplo:</span>
Para comprender la sintaxis antes descrita se definirán 2 ejemplos básicos, considerando el lenguaje L={a,b}

### **Ejemplo 1:** <br>Escriba una expresión regular que represente al conjunto de palabras que empiezan con *a* y terminan en *b*.
- Resolución: <span style="color:#AE5FD3; font-weight:bold;" >L1= { (a) [(a)|(b)]* [b] }</span>

<br>

### **Ejemplo 2:** <br>Escriba una expresión regular que represente al conjunto de palabras de longitud impar.
- Resolución:  <span style="color:#AE5FD3; font-weight:bold;" >L2= { (a|b) [ ( (a)|(b) ) ( (a)|(b) ) ]* } </span>


