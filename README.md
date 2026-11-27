# Entrega final — Herramientas para el Análisis de Datos

Este repositorio reúne los trabajos realizados durante el semestre en el curso de Herramientas para el Análisis de Datos. Incluye análisis de población y actividad económica de Chile, además de un caso de análisis comercial para la empresa Visión Clara.

## Contenido

- **`Moreno_Valentina_Reporte1-Python.ipynb`**: Análisis de la población nacional de Chile, con cifras históricas desde 2000 y proyecciones hasta 2070. Utiliza Python, pandas, NumPy y Matplotlib.
- **`Poblacion_nacional(in).csv`**: Base de datos utilizados en el notebook de Python.
  
- **`Moreno_serie-R.ipynb`**: Análisis de la serie mensual del IMACEC minero, desde enero de 2013 hasta agosto de 2026, expresada como índice con base promedio 2018 = 100. Utiliza R.
- **`CCNN2018_IMACEC_01_A (Mineria).xlsx`**: Base de datos utilizados en el notebook de R.

- **`Caso_VisionClara_Moreno-PBI.pbix`**: informe del caso de Visión Clara para Power BI.
- **ˋCaso_Vision_Clara(-).csv´**: Bases de datos utilizadas para analisis comercial VisionClara.

- **`VisionClara_ValentinaMoreno.twb`**: Libro de trabajo de Tableau para el caso de ventas de Visión Clara.
- **`Caso_10_Vision_Clara_Sabana_de_datos.xlsx`**: Base de datos utilizada en libro de Tableau.
-

## Cómo abrir los archivos

### Notebooks de Python y R

Los notebooks se pueden abrir con [Google Colab](https://colab.research.google.com/) o con Jupyter Notebook/JupyterLab:

1. Se debe descargar o clonar este repositorio.
2. En Colab, se debe seleccionar **Archivo → Subir notebook** y cargar el archivo `.ipynb`. En Jupyter, se debe abrir el notebook desde la carpeta del repositorio.
3. Se debe comprobar que el archivo de datos correspondiente esté accesible desde el entorno de ejecución y que conserve el nombre indicado en el notebook.
4. Se deben ejecutar las celdas en orden.

En Colab, también se debe subir el archivo de datos al entorno de ejecución. El notebook de Python busca `Poblacion_nacional(in).csv` en `/content/`. El notebook de R busca el archivo Excel en `/content/` o en la carpeta de trabajo; se debe configurar el entorno de ejecución como R, tal como indica el propio notebook.

### Power BI

Se debe abrir `Caso_VisionClara_Moreno-PBI.pbix` con Microsoft Power BI Desktop. Si Power BI solicita actualizar o confirmar una conexión, se deben seguir las indicaciones de la aplicación para cargar el informe.

### Tableau

Se debe abrir `VisionClara_ValentinaMoreno.twb` con Tableau Desktop. El libro utiliza `Caso_10_Vision_Clara_Sabana_de_datos.xlsx`, que está incluido en el repositorio. Si Tableau no encuentra la fuente debido a que la ruta guardada corresponde a otro equipo, se debe volver a conectar seleccionando ese archivo en la carpeta del repositorio.

## Detalle de los trabajos

###   
