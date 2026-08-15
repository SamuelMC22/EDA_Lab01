<div align="center">

<img src="Membrete.png" alt="membrete" width="600" style="border-radius: 0%;">

# EDA_Lab01: Taller de Fundamentos de Python
### Autor: Samuel Monsalve Canizales

**ID:** 20572022 | **Asignatura:** Procesamiento de Datos a Gran Escala | **Fecha:** Agosto 2026  |  **Pontificia Universidad Javeriana**

</div>

---

## Descripción del Repositorio

Este repositorio contiene la entrega del **Laboratorio 01 (EDA_Lab01)** para la asignatura *Procesamiento de Datos a Gran Escala*. 

El objetivo del taller es explorar, aplicar y documentar de manera personal y práctica las estructuras de datos fundamentales, el control de flujo, la modularidad con funciones y la Programación Orientada a Objetos (POO) en Python, sentando las bases para el procesamiento y análisis de datos.

Cada cuaderno incluye:
* Membrete de identificación institucional y objetivo del tema.
* Desarrollo conceptual con ejemplos prácticos ejecutados.
* Notas explicativas breves con observaciones personales (`> **Nota:** ...`).
* Resolución documentada de los quizzes oficiales del curso.
* Casos prácticos aplicados a problemas de Ciencia de Datos.
* Conclusiones técnicas de aprendizaje al final de cada cuaderno.

---

## Contenido de los Cuadernos y Rúbrica de Entrega

Los cuadernos se encuentran organizados dentro de la carpeta [`Ejercicios_Python/`](Ejercicios_Python/):

| # | Cuaderno | Temas Principales y Actividades | Ponderación |
|---|---|---|:---:|
| **01** | [01_Cadenas.ipynb](Ejercicios_Python/01_Cadenas.ipynb) | Tipos de delimitadores, indexación, slicing, stride, secuencias de escape, métodos (`.upper()`, `.replace()`, `.find()`), Quiz oficial y parseo de logs | **10%** |
| **02** | [02_Tuplas.ipynb](Ejercicios_Python/02_Tuplas.ipynb) | Inmutabilidad, tuplas singleton, indexación, slicing, tuplas anidadas, ordenamiento con `sorted()`, Quiz y coordenadas hashables | **10%** |
| **03** | [03_Listas.ipynb](Ejercicios_Python/03_Listas.ipynb) | Mutabilidad, operaciones `.append()` vs `.extend()`, `.pop()`, `.remove()`, aliasing vs clonación, list comprehensions y Quiz | **10%** |
| **04** | [04_Conjuntos.ipynb](Ejercicios_Python/04_Conjuntos.ipynb) | Colecciones únicas, tiempo de búsqueda $O(1)$, métodos `.add()` / `.remove()`, unión, intersección, diferencia, Quiz y cruce de IDs | **10%** |
| **05** | [05_Diccionarios.ipynb](Ejercicios_Python/05_Diccionarios.ipynb) | Estructuras clave-valor, acceso seguro con `.get()`, fusión con `.update()`, Quiz de ventas de álbumes y agregación tipo `GROUP BY` | **10%** |
| **06** | [06_Condiciones.ipynb](Ejercicios_Python/06_Condiciones.ipynb) | Comparaciones, bifurcaciones `if`/`elif`/`else`, operadores lógicos, evaluación de cortocircuito, Quiz y motor de reglas de riesgo | **10%** |
| **07** | [07_Bucles.ipynb](Ejercicios_Python/07_Bucles.ipynb) | Rango `range()`, bucles `for` por índice y por elemento, `enumerate()`, ciclos `while` con salida temprana, Quiz y batching de datos | **10%** |
| **08** | [08_Funciones.ipynb](Ejercicios_Python/08_Funciones.ipynb) | Modularidad con `def`, funciones nativas, argumentos por defecto, ámbito de variables (*scope* local/global), Quiz y escalado Min-Max | **10%** |
| **09** | [09_Clases.ipynb](Ejercicios_Python/09_Clases.ipynb) | POO, constructor `__init__`, `self`, métodos mutadores, clases `Circle` y `Rectangulo` en Matplotlib, y actividad de la clase `Elipse` | **10%** |
| **10** | [10_Bono.ipynb](Ejercicios_Python/10_Bono.ipynb) | Retos prácticos oficiales de `Practico_Bono_1` (Calentamiento, Nivel 1 y Nivel 2: Lesser of two evens, Animal crackers, Master Yoda, Blackjack, etc.) | **5%** |
| **—** | **Presentación (+Repositorio)** | Estructura ordenada de carpetas, membrete institucional en cada cuaderno, documentación personal y README | **15%** |
| **Total** | | | **105%** |

---

## Requisitos y Ejecución

* **Entorno de desarrollo:** Visual Studio Code / Project Antigravity con soporte de Jupyter Notebooks.
* **Kernel de Python:** Python 3.10 o superior.
* **Librerías principales:** `matplotlib` (para los cuadernos geométricos de clases).

### Instrucciones de uso local:
```bash
# 1. Clonar el repositorio
git clone [https://github.com/SamuelMC22/EDA_Lab01.git](https://github.com/SamuelMC22/EDA_Lab01.git)

# 2. Entrar a la carpeta del proyecto
cd EDA_Lab01

# 3. Abrir en el entorno de desarrollo
code .