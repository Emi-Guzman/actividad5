## COMMIT 1:

1. Se cambiaron los numeros por letras en las tarjetas
 Se centraron las letras en los cuadros del memoria


## COMMIT 2:

 1. Se agrego un contador de taps el cambio se creo en la variable Tops = 0 y se añadio global taps, junto con taps += 1 dentro de la funcion Tap. Al usar global Permitimos que el numero persista y se vaya acumulando durante el tiempo de juego.

2. Se inserto un condicional: if all(not h for h in hide): dentor del ciclo de dibuji (Draw) El juego necesita una forma de saber que ya no quedan fichas por voltear. La lista hide es nuestro mapa de control:

 
















 


