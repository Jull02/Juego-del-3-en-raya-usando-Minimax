# Juego del tres en raya  
Integrantes: Doménica Escobar, Julissa Ruales, Guillermo Álvarez, Gabriel Erazo  
## Descripcion del juego  
El juego de tres en raya es uno de los juegos m'as comunes que existen a nivel mundial, consiste en tener un espacio con tres filas y tres columnas dando como resultado una cuadricula con nueve cuadros vacios, se deben tener dos jugadores qu tomen roles diferentes puede ser por medio de X o de circulos (O) cada jugador elegira un simbolo y se turnaran para colocar el simbolo en un cuadro en blanco, el juego termina cuando uno de los simbolos consiga colocarse en tres espacios seguidos en cualquier direccion. Se declara un empate cuando ninguno de los simbolos o jugadores logro colocar seguidamente el simbolo que se encuentr utilizando.  
## Principales rutinas  
- ***Función playTresEnRaya:*** Crea un tablero, un contador de movimientos, dos variables para guardar la posición de la jugada y inicializamos el tablero y mostramos las instrucciones.Mientras el juego no haya terminado y no se hayan hecho todos los movimientos, si es el turno de la máquina, la máquina juega.  
- ***Función showInstructions:*** Esta función muestra las instrucciones del juego, mostrando un tablero con los números del 1 al 9. (Los tabs son para centrar el tablero)  
- ***Función gameOver:*** Esta función retorna true si alguno de los jugadores ha ganado, o false si no ha ganado nadie. Para esto, se evalúa si alguna fila, columna o diagonal ha sido completada por un jugador.  
- ***Función rowCrossed:*** Esta función recorre cada fila y se evalúa si la primera, segunda y tercera celda son iguales y no están vacías, en ese caso retorna true, si no retorna false.  
- ***Función columnCrossed:*** Aquí recorre cada columna y se evalúa si la primera, segunda y tercera celda son iguales y no están vacías, en ese caso retorna true, si no retorna false.  
- ***Función diagonalCrossed:*** Esta función evalúa si la primera, segunda y tercera celda de la diagonal principal son iguales y no están vacías, o si la primera, segunda y tercera celda de la diagonal secundaria son iguales y no están vacías, en ese caso retorna true, si no retorna false.  
- ***Función bestMove:*** Si el resultado de la función minimax es mayor que el mejor resultado hasta el momento, se guarda el resultado en la variable bestScore, y se guardan las coordenadas de la celda en las variables x y y. Al final de la función, se retorna la posición de la celda en el tablero, que es el resultado de multiplicar la coordenada x por el tamaño del tablero y sumarle la coordenada y.  
- ***Función minimax:*** La función minimax recibe el tablero, la profundidad y un booleano que indica si es el turno del computador o del jugador.  
- ***Función showBoard:*** La función showBoard recibe el tablero y muestra el tablero en la consola.  
- ***Función declareWinner:*** La función declareWinner recibe el turno actual y muestra en la consola el ganador.  
## Tabla de tiempos mejores y peores casos  
17Dentro de la experiencia de máquina vs humano existen varias posibilidades dondr la maquina puede ser mejor que el humano o viceversa, de tal manera existen casos peores y mejores de cada uno, dentro de la historia las primeras maquinas no mantenian un tiempo vorto ni estandarizadoby la mayoria de desiciones que tomaba el computador dentro de un juego de logica lo llevaba a la perfida del mismo haciendo que el ganador sea el humano, esto ha ido cambiando con el pasar de los años y en la actualidad gracias a la inteligencia artificial se ha podido ver como las máquinas han mejorado tanto su tiempo de desición y la efectividad de la misma al punto de que en algunas partidas o juegos completos de lógica las máquinashan salido victoriosas.  
- ***Computadora:*** Las máquinas en la actualidad se puede decir que han mejorado en todo sentido pero cuando se trata de juegos de lógica como el tres en raya muestra que su tiempo al tomar la desicion de realizar un movimiento es de 1 segundo e incluso menos dependiendo de la situación, lo que quiere decir que toma desiciones rápidas pero eso no quiere decir que sea la desicion correcta o efectiva necesariamente. Todo esto se da gracias a que existen algoritmos programados para la computadora en donde verifica los peores y mejores casos o respuestas de una manera rápida pero no necesariamente efectiva.  
- ***Humano:*** Los humanos no necesariamente mantienen un ritmo seguro o estático esto varía dependiendo de las personas que realicenla actividad aun así en términos generales estadísticos en el mejor de los casos se tiene una respuesta de movimiento en los primeros 10 o 20 segundos, mientras que en el peor de los casos el tiempo de respuesta puede llegar a tardar entre 1 o 2 minutos, cabe recalcar que aun así la respuesta no siempre es correcta o efectiva.  
## Arbol de posibilidades  
## Instrucciones Windows  
IDE: Para poder compilar el programa una opción puede ser descargar un IDE como Visual Studio Code con todas las configuraciones necesarias, por medio del IDE abrir el documento, verificar que este configurado los plugins del lenguaje en este caso C++ y luego compilarlo.  



## Instrucciones Linux  
