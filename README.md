# Rompecabezas de Números en Python con Pygame

Este es un juego de **rompecabezas de números** en el que el jugador debe organizar los números desordenados en un tablero de 4x4, donde un espacio vacío permite mover las piezas. El juego tiene una interfaz gráfica creada con **Pygame** y cuenta con un sistema de puntaje, indicando los errores cometidos. Si el jugador se equivoca más de 5 veces, el juego se reinicia con un mensaje de error.

## Características

- Tablero 4x4 con números del 1 al 15 y un espacio vacío.
- Movimiento de piezas al hacer clic en las celdas adyacentes al espacio vacío.
- Un contador de errores que termina el juego si el jugador se equivoca más de 5 veces.
- Una interfaz gráfica minimalista con colores fríos, agradable a la vista.
- Sistema de reinicio del juego tras ganar o cometer más de 5 errores.

## Requisitos

- **Python 3.x**
- **Pygame** (librería para crear juegos en Python)

## Instalación

1. Clona este repositorio en tu máquina local:

   ```bash
   git clone https://github.com/tu-usuario/rompecabezas-numeros.git
   cd rompecabezas-numeros
2.Instala las dependencias necesarias:
pip install pygame

3.Ejecuta el juego:
python puzzle_game.py

#Instrucciones del Juego
1.El tablero está compuesto por 16 celdas, numeradas del 1 al 15, con un espacio vacío.
2.Haz clic en las celdas adyacentes al espacio vacío para mover los números en el tablero.
3.El objetivo es organizar los números de manera ascendente, desde el 1 hasta el 15, dejando el espacio vacío en la última posición.
4.Si cometes más de 5 errores (movimientos no válidos), el juego terminará y te mostrará un mensaje de error con la opción de reiniciar.
5.Si logras organizar el tablero correctamente, recibirás un mensaje de victoria y podrás reiniciar el juego.

Posibles Mejoras
1.Tablero Personalizable: Permitir que el usuario seleccione el tamaño del tablero (por ejemplo, 3x3, 5x5).
2.Niveles de Dificultad: Implementar diferentes niveles de dificultad (fácil, medio, difícil) cambiando el tamaño del tablero o la cantidad de movimientos permitidos.
3.Temporizador: Agregar un temporizador para registrar cuánto tiempo tarda el jugador en resolver el rompecabezas.
4.Sonidos: Incluir efectos de sonido al hacer movimientos correctos o incorrectos.
5.Estilos Visuales: Mejorar los gráficos o agregar animaciones para que la experiencia visual sea más dinámica.
