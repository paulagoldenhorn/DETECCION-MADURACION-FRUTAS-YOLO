# Proyecto de Visión por Computadora 
Trabajo Práctico Final del curso Procesamiento Acelerado de IA con GPU y Clusters.

Tareas realizadas:

1. **Dataset**: construcción de dataset propio recolectando imágenes y etiquetándolas en Roboflow.
2. **Fine-Tuning**: entrenamiento de modelo YOLO Nano en CPU vs. GPU.
3. **Inferencia**: procesamiento de videos propios con OpenCV.
4. **Benchmark CPU vs. GPU**: medición de latencia, FPS, Throughput, VRAM y Speedup.

El trabajo aborda la construcción de un dataset desde cero, recolectando y etiquetando manualmente imágenes de frutas para reentrenar un modelo YOLO Nano de manera que aprenda a detectar frutas en tres estados de maduración: sin madurar, maduro y pasado.

El objetivo principal fue el benchmark, donde se compararon los tiempos del entrenamiento y la inferencia en CPU vs. GPU. Los resultados mostraron que la inferencia en GPU fue 3,33 veces más rápida que en CPU.

Entorno utilizado: Google Colab - GPU T4.

<img width="960" height="540" alt="DETECCION MADURACION FRUTAS - Benchmark CPU vs GPU" src="https://github.com/user-attachments/assets/1174579c-e340-4577-9ad2-1eb057459e05" />

