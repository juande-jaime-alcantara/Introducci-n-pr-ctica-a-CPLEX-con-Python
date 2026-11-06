# Introducción práctica a CPLEX con Python

Material docente para aprender a utilizar CPLEX con Python y DOcplex, con ejemplos y ejercicios organizados por temas en cuadernos Jupyter para Google Colab.

Los cuadernos acompañan al manual *Introducción práctica a CPLEX con Python*. Cada tema incluye los modelos matemáticos, su implementación en Python y ejercicios con celdas para completar el código.

## Contenido

1. **Primeros pasos con CPLEX.** Creación de un modelo, declaración de variables continuas, función objetivo, restricciones y consulta de la solución.
2. **Variables indexadas y sumatorios.** Diccionarios de datos y variables, sumatorios, variables con dos índices y uso de condicionales sobre índices y datos.
3. **Tipos de variables y relajación lineal.** Variables continuas, enteras, binarias y libres, y obtención de la relajación lineal mediante `LinearRelaxer`.

## Uso en Google Colab

Puedes trabajar con los cuadernos desde el navegador, sin instalar Python en tu ordenador:

1. Accede a [Google Colab](https://colab.research.google.com/).
2. En **Abrir cuaderno**, selecciona **GitHub** y pega la dirección de este repositorio:
   ```text
   https://github.com/juande-jaime-alcantara/Introducci-n-pr-ctica-a-CPLEX-con-Python
   ```
3. Abre el cuaderno del tema que quieras trabajar y guarda una copia en tu Google Drive para conservar tus cambios.
4. Ejecuta la primera celda para instalar los paquetes necesarios:
   ```python
   %pip install docplex cplex
   ```
5. Ejecuta las celdas en orden y completa los ejercicios en los espacios indicados.

## Ejecución local

También puedes descargar los cuadernos y abrirlos en un entorno compatible con Jupyter, como VS Code. Necesitarás Python, un núcleo de Jupyter y los paquetes del manual:

```bash
python -m pip install docplex cplex ipykernel
```

En VS Code, instala las extensiones de Python y Jupyter y selecciona el entorno donde hayas instalado los paquetes.

## Autor

**Juan de Dios Jaime Alcántara**  
Universidad Miguel Hernández de Elche

Material elaborado con fines docentes y de estudio.
