# datasets_pesados_para_analizar
## Dataset para realizar la prueba de procesamiento tradicional con una gran cantidad de datos

El link para el dataset más grande es este de aquí:
https://drive.google.com/file/d/133uwpbEiMRkef64Sji3hbTPvx2oEZnlI/view?usp=drive_link
Se anexa de esta manera por el tamaño del archivo
También se añade el link para entrar al dataset de vinos aquí:
[https://drive.google.com/file/d/1Rtj8gA1z-3QDn1jscPmSw-bHpvpAIwZ9/view?usp=drive_link](https://drive.google.com/file/d/1Rtj8gA1z-3QDn1jscPmSw-bHpvpAIwZ9/view?usp=sharing)

## Conclusiones

### Conclusión de Jethro:
El análisis comparativo evidencia que la tabla 2 contiene un volumen de datos mayor, reflejado en tiempos de ejecución superiores en 65.8 ms vs 9.04 ms en verificación de nulos a comparación de la tabla 3, la tabla 1 tardo considerablemente más tiempo debido a su gran volumen y la potencia del equipo. 

Conforme la escala de los datos crece, las operaciones sobre la estructura como lo son la verificación e imputación de nulos generan "cuellos de botella". Esto demuestra que cuando el volumen de datos supera el umbral del procesamiento tradicional, se vuelve necesaria la transición hacia arquitecturas de Big Data, donde el procesamiento distribuido sustituye la dependencia de la potencia de un único equipo.