# Escapa-del-mostruo
juego creado por Gleider Ramirez
Escapa del Monstruo
Este es un juego desarrollado en Python con la libreia de Pygame, donde controlas un cuadrado azul y tu objetivo es sobrevivir la mayor cantidad de tiempo posible evitando enemigos y enfrentandote a un jefe que se vuelve mas fuerte con cada aparicion.

Como jugar
1. Ejecuta el archivo `juego.py`.
2. En el menu principal selecciona la dificultad:
   - `1` → Facil
   - `2` → Medio
   - `3` → Dificil
3. Usa las flechas del teclado para mover al jugador.
4. Evita chocar con los enemigos, balas o el jefe.
5. Presiona `P` en cualquier momento para abrir el menu de pausa.

 Caracteristicas principales
Tres modos de dificultad: facil, medio y dificil.
Menu de pausa: permite reanudar, reiniciar o volver al menu principal.
Sistema de puntos: solo aumentan si el jugador esta en movimiento.
Sistema de vidas: empiezas con 1 vida y ganas +1 vida extra cada vez que sobrevives a un jefe.
Enemigos normales: aparecen continuamente segun la dificultad.
Jefe final:
Aparece por primera vez en 8,000 puntos (desaparece a los 10,000).
Vuelve a aparecer cada 3,000 puntos.
Cada vez es 10% mas grande y **15% mas rapido.
Persigue directamente al jugador y dispara proyectiles dirigidos.
Mientras esta activo, todos los demas enemigos desaparecen.

Requisitos
Python 3.8 o superior
Libreria Pygame 

Notas
El objetivo es sobrevivir el mayor tiempo posible, esquivando enemigos y superando las apariciones del jefe.  
Cada jefe es mas desafiante que el anterior, pero tambien te recompensa con una vida extra.
