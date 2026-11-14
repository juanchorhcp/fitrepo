Acá voy a poner todo lo que aprenda sobre uso avanzado de FMOD.

## FMOD Audio Implementation for Video Games *by Beatrix Moersch*

Event instrument
Trae el sonido de otro evento al evento actual para manejarlo como un track

Multi-instrument
Se puede poner eventos adentro a la vez que audios. Se lo llama "Stacking events"

Scattered instrument
Útil en ambiences - tipo aves y sonidos que se van disparando aleatoriamente

Noise instrument
AudioWeather y AudioMotors en el video eran generadores de ruido DE PAGO

*Al final no pude seguir el curso porque era una plataforma de pago*

## Truquitos
#### Raiser - Lena Raine (Celeste)
En situacion de música por capas en la que se van agregando instrumentos, poner un raiser para que no suene pedorro el fade in del instrumento que entra [Simple Secret to Transition Game Music - YouTube](https://www.youtube.com/shorts/FhsgAM1AgX4)

#### Verticalidad made simple (drums)
Layer 1: background. Acompañamiento + melodías
Layer 2: Slow drums
Layer 3: Fast drums
#### Evitando repetitividad
3 versiones de exploración + 3 versiones de combate
Lo importante es componer las transiciones musicales entre cada conexión
En este caso van a ser 9 de ida y 9 de vuelta
	Importante en roguelikes o niveles largos


## Variation
#### SFX compuestos
Recordar que se puede hacer un multi-instrument para cada factor que compone al sfx
	Ej: secuencia de ataques, muerte de enemigo (cae+grito+fuego), etc.