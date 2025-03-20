# EEAE-Python2025
Repositorio de código de los ejercicios de python de la E2T 2025

> [!NOTE]
> **Guía rápida Git y GitHub**
> Esta breve guía está sacada de [AQUÍ](https://github.com/mouredev/roadmap-retos-programacion/tree/main?tab=readme-ov-file#gu%C3%ADa-r%C3%A1pida-git-y-github).
>
> Sigue estos pasos para realizar las entregas de los ejercicios:
> 1. Realiza un FORK[^1] del repositorio de trabajos desde GitHub.
> 2. CLONA ese repositorio a tu máquina local `git clone [TU-REPOSITORIO]`.
> 3. (Opcional) Crea una RAMA para la solución y desplázate a ella `git checkout -b [EL-NOMBRE-DE-TU-RAMA]`.
> 4. Añade el fichero de tu solución al STAGE `git add [FICHERO-DE-TU-RETO]`.
> 5. Haz COMMIT con el mensaje de la solución `git commit -m "#[NÚMERO-EJERCICIO] - [APELLIDO]"`.
> 6. Haz PUSH `git push [EL-NOMBRE-DE-TU-RAMA]` (puede ser la "main" o la que creaste en el paso 3)
> 7. En el repositorio principal debes ir a la rama y hacer [PULL REQUEST](https://docs.github.com/es/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).
> 8. CONTRIBUTE.
> 9. CREATE PULL REQUEST (cubre la plantilla que te aparecerá).
> 10. Si el proceso de entrega se ha realizado de forma correcta, se añadirá tu corrección al repositorio. En caso contrario, se te notificarán los cambios a realizar o los motivos del rechazo.

[^1]: Puedes consultar la [documentación oficial de GIT](https://git-scm.com/book/es/v2/GitHub-Participando-en-Proyectos) para saber más sobre el *fork*

# Ejercicios de Repaso de Programación en Python

## Ejercicio 1: Calculadora básica con clases
Crea una clase `Calculadora` que tenga métodos para sumar, restar, multiplicar y dividir dos números.  
Incluye un constructor que inicialice los dos números como atributos.

## Ejercicio 2: Contador de palabras
Escribe una función que reciba una cadena de texto y devuelva cuántas palabras contiene.  
Luego, crea una clase `Texto` que use esa función como método y almacene el texto como atributo.

## Ejercicio 3: Lista de números pares
Crea una clase `Numeros` con un atributo que sea una lista de enteros.  
Incluye un método que devuelva solo los números pares de esa lista.

## Ejercicio 4: Conversor de temperaturas
Diseña una clase `ConversorTemperatura` con métodos para convertir de Celsius a Fahrenheit y viceversa.  
Usa un constructor para inicializar una temperatura base.

## Ejercicio 5: Gestión de estudiantes
Crea una clase `Estudiante` con atributos para nombre, edad y calificación.  
Implementa métodos *getter* y *setter*, y un método que determine si el estudiante aprobó (calificación mayor o igual a 6).

## Ejercicio 6: Ordenar una lista
Escribe una función que reciba una lista de números y la ordene de menor a mayor sin usar `sort()`.  
Luego, intégrala como método en una clase `Ordenador`.

## Ejercicio 7: Registro de productos
Crea una clase `Producto` con atributos para nombre, precio y cantidad en stock.  
Añade un método que calcule el valor total del inventario (`precio × cantidad`).

## Ejercicio 8: Validación de contraseña
Diseña una clase `Validador` con un atributo para una contraseña.  
Incluye un método que verifique si la contraseña tiene al menos 8 caracteres, una mayúscula y un número.

## Ejercicio 9: Promedio de notas
Crea una clase `Notas` con una lista de calificaciones como atributo.  
Implementa un método que calcule el promedio y otro que devuelva la nota más alta.

## Ejercicio 10: Simulador de dado
Escribe una clase `Dado` que simule tirar un dado de 6 caras (usando `random`).  
Incluye un método para tirar el dado y otro para mostrar el resultado.

## Ejercicio 11: Gestión de cuentas bancarias
Crea una clase `CuentaBancaria` con atributos para titular y saldo.  
Añade métodos para depositar, retirar y consultar el saldo (usa *getter* y *setter* para el saldo).

## Ejercicio 12: Contador de vocales
Diseña una clase `AnalizadorTexto` con un atributo para una cadena de texto.  
Implementa un método que cuente cuántas vocales (a, e, i, o, u) hay en el texto.

## Ejercicio 13: Rectángulo
Crea una clase `Rectangulo` con atributos para ancho y alto.  
Incluye métodos para calcular el área y el perímetro, usando un constructor para inicializar los valores.

## Ejercicio 14: Registro de tareas
Escribe una clase `Tarea` con atributos para descripción y estado (*pendiente* o *completada*).  
Añade un método para cambiar el estado y otro para mostrar la información de la tarea.

## Ejercicio 15: Juego de adivinanza
Crea una clase `Adivinanza` que genere un número aleatorio entre 1 y 100 (usa `random`).  
Incluye un método que permita al usuario adivinar y devuelva pistas (*"más alto"* o *"más bajo"*) hasta que acierte.

## Ejercicio 16: Programa de gestión de tareas
1. Define una clase `Tarea` con atributos `titulo`, `descripcion` y `completada`.
2. Implementa métodos para añadir, eliminar, marcar como completada y listar todas las tareas.
3. Guarda la lista de tareas en un archivo JSON y permite cargarla al iniciar el programa.
4. Usa la librería `os` para gestionar los archivos y directorios necesarios.
