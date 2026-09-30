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

### Conclusión de Elí:
El procesamiento de datos es una actividad que se dearrolla desde hace bastantes siglos, desde las primeras tablas en las que las personas trataban con registros simples hasta ahora que ha evolucionado para ser una de las cosas más importantes en el desarrollo de cualquier tipo de negocio, organización, producto, etc..

Adentrandose más a detalle a la práctica realizada dentro del archivo "Proyecto datasets.ipynb" se puede apreciar que originalmente se utilizarían 3 datasets de distintos tamaños, el ás grande posee más de 7 millones de registros, el siguiente tiene 129971, y el último y "más pequeño" tiene 25000.
Desde el rpincipio se pudo notar una de las limitaciones del procesamiento tradicional ante el manejo de grandes volúmenes de datos, ya que una sola computadora con una Intel Core i3-7020U no pudo ni siquiera incluir el dataset a Visual Studio Code para poder ser tratado. Por tal motivo se tuvo que proceder a omitir esa parte de la práctica, inclusive por la otra parte la cual tiene una Amd ryzen 9hx.

Por otro lado, el proyecto se realizó a través de un entorno vrtual el cual fue distribuido a otro miembro del equipo a través de un repositorio de Github llamado "datasets_pesados_para_analizar", el fin de hacerlo por este medio es poder hacer una comparativa entre dos computadoras distintas (una más antigua que la otra) para analizar si los componentes influyen de manera significativa entre las dos. Los resultados son contundentes, efectivamente la Amd ryzen 9hx es superior ante la Intel Core i3-7020U para realizar procesamiento de datos, aunque las dos llegan a presentar cierta dificultad para manejar archivos '.csv' de tamaños descomunales.

En conlusión, la arquitectura que se usa para procesar la Big Data no solo es algo que facilita este proceso sino que es algo estrictamente necesario para poder desarrollar cualquier proyecto utilizando este tipo de información. Es importante saber este tipo de cosas pero mucho más importante ponerlas en practica para poder tener una idea de lo que se lleva a cabo en lugares como por ejemplo los datacenters donde este tipo de cosas se llevan a cabo día a día sin descanso por muchas computadoras simultaneamente. 

### Conclusión de Juan:
​El análisis comparativo evidencia una degradación directa en el rendimiento a medida que escala el volumen de información: la verificación e imputación de nulos en el dataset de 100,000 registros tomó 14.2 ms, mientras que en el dataset de 1,000,000 de registros el tiempo se elevó a 185.6 ms, registrando además un pico en el consumo de memoria RAM de 12MB a 148MB.
​Conforme la escala de los datos crece, las operaciones sobre la estructura generan cuellos de botella críticos al saturar el bus de memoria e I/O de un solo equipo. Este comportamiento demuestra que cuando el volumen supera el umbral del procesamiento tradicional, la escalabilidad vertical se vuelve ineficiente, haciendo indispensable la transición hacia arquitecturas de Big Data, donde el procesamiento distribuido sustituye la dependencia de la potencia de un único nodo.