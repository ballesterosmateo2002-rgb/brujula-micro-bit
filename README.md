Mateo Ballesteros Cervantes
11-7
Inem simon bolivar 

Brújula básica para micro:bit con MicroPython

Este es un programa de brújula básica, creado mediante un prompt, para la micro:bit utilizando MicroPython.

Apenas se enciende, la micro:bit calibra su sensor magnético, ya que este es muy sensible a los aparatos electrónicos y metales cercanos. 
Para calibrarse, primero necesita aprender cómo es el campo magnético del lugar, así que te pedirá que la inclines en diferentes direcciones mientras un 
punto en la pantalla va recorriendo el borde hasta completar un círculo. Cuando lo logras, aparece una marca de visto bueno.

Después de calibrar, el programa muestra un corazón en la pantalla. 
Esto significa que todo está listo, pero la brújula todavía no está funcionando. En ese momento, 
el programa queda en un ciclo infinito, revisando cada décima de segundo si alguien ha presionado alguno de los botones.

Cada vez que presionas el botón A, la brújula cambia de estado: si estaba apagada, se enciende, y si estaba encendida, se apaga y vuelve el corazón a la pantalla.

El botón B tiene otra función: recalibrar. Esto permite repetir la calibración en cualquier momento. 
Al presionarlo, el programa vuelve a pedirte que gires la placa, apaga la brújula y regresa al estado de espera con el corazón. Es útil si cambias de lugar, porque el 
campo magnético de una sala puede ser muy distinto al de un patio.
