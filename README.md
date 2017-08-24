# -Laboratorio-02-Bioinformatica-Ox

## Nombre: Byron Guzmán Marín

## Profesor(a): Katterinne Méndez Carrasco

## Parte 1: Colectar genes homólogos

__Responde__

__¿Qué función cumple el gen?__

El gen SRY codifica para un factor  de transcripción, proteína la cual es el factor determinante de testiculos (TDF), en el que inicia la determinación del sexo masculino.

__¿Cuántos genes ortólogos están anotados en esa base de datos?__

Al revisar la homología en la información referente a Homo sapiens, se encuentran 26 organismos que tienen ortólogos del gen SRY.

## Parte 2: Alineamiento múltiple

__¿Qué es el EMBL-EBI?__

El EMBL-EBI es el Instituto Europeo de Bioinformática (EBI), quienes forman parte del Laboratorio Europeo de Biologia Molecular (EML), se encargan de manejar la información  biológica pública del mundo para hacerlo necesario sin costo alguno para la comunidad científica a través de una serie de servicios y herramientas, realizando la búsqueda básica y probando la formación profesional en Bioinformática, manteniendo la información a la fecha de bases de datos Moleculares

__¿Cuántos  tipos de alinenamiento múltiple se pueden realizar en EMBL-EBI?__
Se pueden realizar alineamientos globales, locales, tipo HMM (Modelo Markov Oculto), árboles guía, alineamientos por método de consenso e iterativos.

__¿Cuál es el programa que ellos ofrecen que funciona mejor para secuencias de proteínas?__

El programa MUSCLE (MUltiple Sequence Comparison by Log-Expectation) se especializa en proteinas.

__¿Qué otros tipo de herramientas ofrece EMBL-EBI?__

En la sección de MSA (Multiple Sequence Alignment), se listan herramientas como Clustal Omega, con el cual se puede realizar alineamientos del tipo global, además de alineamientos HMM y árboles guía; Kalign es otra herramienta MSA que se especializa en alineamientos locales; MAFFT es una herramienta de tipo progresivo e iterativo; MUSCLE es de tipo iterativo, pudiendo hacer tanto alineamientos globales como locales; Mview transforma resultados de búsquedas de secuencias similares en secuencias de alineamiento múltiple; T-Coffee utiliza ambos tipos de alineamiento global y local, mitigando las dificultades de métodos de alineamiento progresivos; y WebPRANK, es un programa MSA que sirve para colocar inserciones y deleciones.

__¿Cuál es el costo de abrir un gap?__

El costo de abrir un gap en MAFFT es 1.53 como valor default.

__¿Cuál es el costo de extender un gap?__

El costo de extender un gap en MAFFT es 0.123 como valor default.


__¿Cuál es la longitud total del alineamiento?__

1932 pb.

__¿Cuál es la especie cuyo gen SRY está más relacionado con el gen SRY de humanos?__

Pan troglodyte (chimpancé)

__¿Cuál es el más lejano?__

Al observar el árbol filogenético, el gen SRY de Pteropus alecto se encuentra más alejado del humano.

__¿Cuál es la especie cuyo gen SRY es más cercana a la del burro?__

Equus przewalskii (caballo de Przewalskii).

# Modificando costos

__¿Cómo esperas que sea el alineamiento si el costo de abrir un gap aumenta? ¿Y si disminuye?__

Si el costo de abrir un gap aumenta, entonces provocará que los gaps sean menos frecuentes al incrementar el costo, el programa desfavorecerá la aparición de gaps si el valor de costo es alto para obtener una matriz de costo razonable. En cambio, si el costo de abrir un gap se disminuye, aparecerán más gaps en el alineamiento, observando entonces más divergencias (indels) entre las especies.

__¿Cómo esperas que sea el alineamiento si el costo de extender un gap aumenta? ¿Y si disminuye?__

Si se incrementa el costo de extender un gap, provocará que los gaps sean más cortos, debido a que el costo será mayor, extendiendo los gaps cada vez menos a medida que se incrementa el costo. En cambio, si se disminuye el costo de extender un gap, ocurrirá lo contrario al ser más "barato", provocando la aparición de gaps más largos al colocar un costo menor.

__¿Cuál fue el efecto de aumentar el costo de abrir un gap en la longitud total del alineamiento?__
 
 Al aumentar el costo de abrir un gap a 2.0, no varió la longitud.

__¿Cuál fue el efecto al disminuir al mínimo el costo de extender un gap?__

Al disminuir el costo provoco una disminución en la longitud quedando 1907 pb.

## Parte 3: Diseño de partidores

__Secuencias con nombres modificados__

https://www.dropbox.com/s/u65tm0fx7wy1epn/Captura%20de%20pantalla%202017-08-23%20a%20la%28s%29%2022.00.11.png?dl=0

__Partidores generados__

https://www.dropbox.com/s/76854lsrn97bpsj/Captura%20de%20pantalla%202017-08-23%20a%20la%28s%29%2022.14.03.png?dl=0



