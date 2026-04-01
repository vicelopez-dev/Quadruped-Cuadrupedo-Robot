# Quadruped / Cuadrúpedo - Robot

## Description / Descripción

This project consists of a controlled (soon-to-be autonomous) robot that moves by imitating the motion of a quadruped (bio-inspired design) and performs functions such as soil moisture detection, and soon, ambient temperature detection.
Este proyecto consiste en un robot controlado (próximamente autónomo) que se desplaza imitando el movimiento de un cuadrúpedo (diseño bio-inspirado) y realiza funciones como la detección de humedad del suelo y, próximamente, la detección de temperatura ambiental.

## Images / Imágenes

## Components / Componentes
- ESP32
- PCA9685
- Buck Converter
- Battery pack, 12V-6000mAh
- MG996R and SG90 servomotors
- LoRa EBYTE E220-400T22D
- 
## Operation / Funcionamiento
The robot is controlled using a custom controller via LoRa, allowing movement forward-backward and left-right. Additionally, using a "U"-shaped sensor, it can detect soil moisture.
El robot se controla mediante un control propio a través de LoRa, pudiéndose desplazar adelante-atrás e izquierda-derecha. Además, mediante un sensor en forma de "U", puede detectar la humedad del suelo.

## Results / Resultados
The robot can move across uneven surfaces, giving it a significant advantage compared to robots of the same weight that use more conventional movement systems such as DC motors and wheels. Although the speed cannot be matched, this is compensated by the robot's agility. Furthermore, the data it detects can be transmitted directly to the controller for use or storage for research and analysis.
El robot logra desplazarse por superficies irregulares, obteniendo una ventaja relevante frente a robots del mismo peso que utilizan sistemas de desplazamiento más convencionales como motores DC y ruedas. Aunque la velocidad no es comparable, esto se compensa con la agilidad del robot. Además, los datos que puede detectar pueden ser transmitidos directamente al control para ser usados o guardados en investigaciones o análisis.
