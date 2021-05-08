# Stec_Actividad4
Semana Tec Actividad 4 TIRO PARABÓLICO 
</br>
Este repositorio cuenta con coommits y branches que fueron creados para realizar lo pedido en la actividad 4.

## Tabla de Contenidos
1. [Información General](#general-info)
2. [Collaboration](#collaboration)

## Información General
En esta actividad se no pidió hacer que la velocidad en la cual se lanzaban los proyectiles fuera mayor a la original, al igual que se nos pidió que 
a pesar de que los objetivos llegaran al límite de la pantalla izquierda no se terminará el juego, sino que siguiesen apareciendo del lado derecho.

## Aumento de velocidad (Jorge-TL)
Una de las especificaciones que tuvimos en el juego es que se volviera más rápido, tanto el proyectil, como los blancos, en este caso buscamos los
parámetros para modificar su velocidad, y encontramos las líneas de código importantes, es decir las de speed. El proyectil y los blancos tienen
cada uno su apartado distinto el cual modifica su velocidad.
</br>
</br>
El apartado de la velocidad el proyectil se encuentra en tap(), donde y es donde se modifica tanto la velocidad como los ángulos de salida en este
caso jugamos con distintas velocidades y decidimos que la de 600 era muy divertida </br>
Y por su parte la velocidad de los blancos en move() en la parte de inside y solo modificamos un poco para que no fueran tan lentas pero tampoco
que se muevan excesiva o notoriamente rápido.

## Bucle de Juego (Chava27)
Una vez que se realizó el cambio de velocidad de los proyectiles, fue momento de crear el bucle en el juego, para esto fue necesario cambiar la
función def move() en la línea 46, siendo más específico en la línea 69, donde agregamos un for para los objetos
targets, donde se crea una condición que establece que cuando los objetivos salen de la pantalla (límite de la derecha)
se crean nuevos objetivo (dots) con las mismas especificaciones en el lado derecho de la ventana.
</br>
</br>
Para hacer un poco más interesante el juego, decidimos incluir un randrange en la función de dot, lo que hace que nuestros
objetivos esten cambiando de tamaño de manera aleatoria entre 23 a 30, lo que hace que parezca que tiene una
animación interesante.


## Collaboration
Chava_27 (Salvador Salgado)</br>
Jorge-TL (Jorge Tamariz)
