# pokerGame
Ejercicio para la programación en Nodejs

Planteamiento inicial:

1) Realizar un servidor con express y servir las páginas web estáticas para el logging y la interacción con las cartas.
2) Desarrollo de las clases (Carpeta class):
3)  * Player (Clase en la que se definen las propiedades del jugador y los métodos de apostar, pasar, igualar, etc).
4)  * Dealer (Clase para el manejo de las cartas. Barajar, repartir, extraer.
5)  * Rules (clase que permite evaluar las jugadas. Toda la interpretación de las jugadas)

En la carpeta account se encuentra el archivo main.js en el que se encuentra la máquina de estados que debe controlar el juego. Al faltar el front restaría por habilitar un Do-While que permita mantenerse en la partida hasta que haya un ganador. También faltarían pulir detalles al respecto de condicionantes que pueden darse y he obviado.

Desarrollo del proyecto

Realicé una prueba de concepto con el servidor y pasé a programar todas las clases. Toda la parte del servidor y el front de interface de usuario está sin empezar.

Las clases Player, Dealer y Rules están operativas y junto con la máquina de estados Main, aunque me llevaron la mayor parte del tiempo. Me hubiera gustado meterme a fondo con el servidor express, pero no he llegado.

He aprendido muchas cosas durante el proceso y hay (creo) bastantes líneas de código programadas. Analizando a posteriori (23:45 del 18.04.2022) y con las horas de que tengo disponibles para dedicar al proyecto, quizás fui demasiado ambicioso al elegir el poker. Me ha llevado mucho trabajo por su complejidad y por el planteamiento que me había montado, lo que ha provocado que llege demasiado apurado a la fecha de entrega.

El en último momento y a toda prisa he tenido problemas con la sincronizació del servidor git local y el remoto y del tema del bundler he elegido Vite porque hemos trabajado más que con webpack aunque el código no está comprimido.

Un cordial saludo.
