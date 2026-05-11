
# Evaluación 3 - Aplicación Web con Flask

Este proyecto corresponde a la **Envaluación 3** de la asignatura **Programación Web**.  
La aplicación fue desarrollada con **Python** y **Flask**, e incluye un menú principal con dos ejercicios y una página adicional de créditos.

## Descripción del proyecto

La aplicación permite acceder a dos ejercicios:

- **Ejercicio 1:** cálculo del promedio de tres notas y determinación del estado final del estudiante según promedio y asistencia.
- **Ejercicio 2:** comparación de tres nombres para identificar cuál tiene más caracteres.
- **Repositorio:** página breve con link directo al repositorio del proyecto.

## Estructura del proyecto

```bash
ev3/
│
├── main.py
├── templates/
│   ├── index.html
│   ├── ejercicio1.html
│   ├── ejercicio2.html
│   └── repositorio.html
│
├── static/
│   └── style.css
│
└── README.md
```


## Requisitos

- Python 3 instalado
- Flask instalado mediante pip

## Instalación de Flask
En la terminal ejecutar:
```py -m pip install flask```

## Ejecución del proyecto
Desde la carpeta del proyecto ejecutar:
```py main.py```

## Luego abrir en el navegador:
```http://127.0.0.1:5000/```