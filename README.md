# mario-quintus
tercera practica de DVI

Para iniciar el juego es necesario inicializar un server local:

python -m SimpleHTTPServer (en caso de python 2)

python -m http.server (en caso de python 3)

El juego es una versión muy simplificada de Super Mario Bros.

Por un lado el personaje de Mario usara las flechas direccionales para moverse y saltar. Si choca contra alguno de los enemigos o cae al suelo muere. En cambio si entra en contacto con la princesa se gana la partida.

Los enemigos son el goomba que se mueve horizontalmente y si choca contra algo que no sea Mario cambia de dirección y los bloopa que simplemente saltan en el mismo lugar. Ambos enemigos mueren cuando Mario colisióna con ellos por encima.

También hay una moneda para conseguir puntuación extra si se entra en contacto con ella sin generar ningun peligro para el jugador.

Por su parte el jugador tiene 3 vidas para conseguir llegar a la princesa y guardando su puntuación conseguida hasta el momento, pues aparte de la moneda eliminar enemigos aumenta también los puntos.
