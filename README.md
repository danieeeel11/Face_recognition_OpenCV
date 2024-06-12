# Face_recognition_OpenCV

Este repositorio contiene la implementación de un proyecto de reconocimiento facial en C++ utilizando OpenCV. El proyecto detecta los rostros en cada frame de un video o imagen y extrae descriptores y keypoints para encontrar coincidencias.

## Contenido

1. [Abstract](#abstract)
2. [Tecnologías Utilizadas](#Tecnologías_Utilizadas)
3. [Implementación](#Implementación)
4. [Referencias](#Referencias)

## Abstract
El reconocimiento facial es una tarea compleja que se puede abordar eficazmente mediante técnicas de procesamiento de imágenes y visión por computadora. Este proyecto en C++ utiliza OpenCV para detectar rostros en tiempo real y extraer descriptores y keypoints de cada frame. Estos datos se utilizan para encontrar coincidencias entre diferentes imágenes o frames de video, permitiendo la identificación de personas. La implementación incluye el uso de algoritmos de detección de rostros y extracción de características para lograr una alta precisión en el reconocimiento.

## Tecnologías_Utilizadas
* C++: Lenguaje de programación principal para la implementación del proyecto.
* OpenCV: Biblioteca de procesamiento de imágenes y visión por computadora utilizada para la detección y reconocimiento de rostros.
* CMake: Herramienta de gestión de compilación utilizada para compilar el proyecto.

## Implementación
La implementación del proyecto se divide en varias etapas:
* Captura de Video/Imagen: Uso de la cámara del dispositivo o carga de imágenes desde un archivo para capturar frames.
* Detección de Rostros: Uso de clasificadores en cascada de Haar o algoritmos de redes neuronales para detectar rostros en cada frame.
* Extracción de Keypoints y Descriptores: Aplicación de algoritmos como SIFT, SURF, ORB, etc., para extraer keypoints y descriptores de los rostros detectados.
* Coincidencia de Descriptores: Uso de algoritmos de correspondencia de descriptores para encontrar coincidencias entre diferentes imágenes o frames.
* Visualización de Resultados: Mostrar los rostros detectados y las coincidencias encontradas en la pantalla del dispositivo.

## Referencias
OpenCV Documentation: https://docs.opencv.org/
CMake Documentation: https://cmake.org/documentation/
