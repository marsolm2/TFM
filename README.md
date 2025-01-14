# Título del trabajo: Desarrollo de modelos de aprendizaje automático para la clasificación de la leucemia mieloide y linfoide aguda basados en análisis de expresión diferencial de genes
Este repositorio incluye información adicional y el código empleado para el desarrollo del trabajo.  
Aquí se muestra una descripción del contenido del repositorio:
- genes_diferencialmente_expresados: carpeta que contiene 3 archivos PDF con las listas completas de los genes diferencialmente expresados. 
  - AMLvsALL: contiene dos tablas con los genes infra y sobrexpresados del contraste experimental AML vs. ALL.
  - csvsALL: contiene dos tablas con los genes infra y sobrexpresados del contraste experimental de controles sanos vs. ALL.
  - csvsAML: contiene dos tablas con los genes infra y sobrexpresados del contraste experimental de controles sanos vs. AML.
- genes_seleccionados: archivo PDF que contiene una tabla con los genes seleccionados tras la aplicación del algoritmo de selección de características importantes. Se adjunta el identificador del gen y su valor de importancia media. 
- codigo: una carpeta que incluye el código empleado para generar los resultados del trabajo en HTML y en .ipynb.
  - bag_svm.ipynb: código en .ipynb utilizado para generar el algoritmo bagSVM en Python usando Google Colab como plataforma.
  - codigo_analisis_expr_diff: código en HTML (que muestra los resultados de ejecutarlo) y .Rmd utilizado para generar los resultados del análisis de expresión diferencial y de la selección de características para el desarrollo de los modelos de aprendizaje automático.
  - codigo_modelos: código en HTML (que muestra los resultados de ejecutarlo) y .Rmd de la generación de los modelos de aprendizaje automático y de la evaluación de los mismos. 
