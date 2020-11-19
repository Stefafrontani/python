# python
Introducción a python

Temario:

- Introducción. Requisitos previos. Instalación de software.
- Fundamentos y sintaxis básica del lenguaje.
- POO con Python.
- Algoritmos, listas y tramos.
- BBDD.
- Trabajo con gráficos y contenidos.
- Procesos y tareas.
- Programación de red. Sockets.
- Ejercicios prácticos.

Características:

- Muy alto nivel. Gramática sencilla, clara, legible.
- Tipado dinámico (tipo se generá automáticamente en tiempo de ejecución) y fuerte (distinción muy clara entre tipos).
- Orientado a objetos.
  - Sobrecarga de constructores. Herencia múltiple. Encapsulación. Interfaces. Polimorfismo.
- Open Source.
- Librería estándar muy amplia.
- Interpretado.
- Flexible. Se pueden hacer muchas cosas:
  - Aplicaciones de escritorio.
  - Aplicaciones de servidor.
  - Aplicaciones web.
  
La descarga de python de la pagina https://www.python.org/downloads, tambien traeré su propio idle, que es un shell - consola. 
Algunos ambientes de trabajo:
- Eclipse
- Notepad++
- sublimeText3

Seleccionar python como interpretar de este proyecto:
- ctrl+shift+p
- Type: 'Python: Select Interpeter'
- Presionar enter y deberías ver ese interpeter abajo a la izquierda.

Cuando crees un archivo .py, arriba a la derecha te debería aparecer el simbolo para ejecutar el filename.py

Tipos de datos:
- Numéricos
  - Enteros
  - Float - Decimales (coma flotante)
  - Complejos
- Textos
- Boolean

Listas:

miLista = ['elemento1', 'elemento2', 'elemento3']
miLista2 = ['elemento4']
miLista[:] y miLista es lo mismo.

Pueden tener valores negativos como indice. miLista[-2] // elemento1

Acortar lista:
miLista[0:2] -> 0 incluido : 2 no incluido // [elemento1, elemento2]
miLista.append(elemento4) -> Agrega al final
miLista.insert(2, elemento5) -> Agrega en el índice o posición
miLista.extend(miLista2) -> concatena listas
miLista + miLista2 -> Mismo resultado que miLista.extend(miLista2)
miLista.pop(2) -> Te devuelve el elemento del indice, removiendolo de la lista // elemento3
miLista.index("elemento1") -> Me da posición, si ha repetidos, me da el primero
miLista.remove("elemento1") -> Remueve ese elemento
"elemento1" in miLista -> Da boolean si esta o no en la lista // true
