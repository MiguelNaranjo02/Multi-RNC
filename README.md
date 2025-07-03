# 🧠 Análisis y Clasificación de Imágenes con Redes Neuronales

Este repositorio contiene el desarrollo de dos ejercicios principales utilizando redes neuronales y procesamiento de imágenes:

---

## 🧩 Parte 1: Análisis de Características de Imágenes

Se implementa una red neuronal para analizar cómo distintas características visuales afectan el tratamiento y comprensión de imágenes por modelos de aprendizaje automático. Las características evaluadas incluyen:

- 📸 **Imágenes en Blanco y Negro** (Escala de Grises)
- 🔳 **Imágenes a 16 Bits por Canal**
- 🖥️ **Imágenes en Resolución Full HD (1920x1080)**

### Propósito

Explorar el impacto que tiene el tipo de codificación y resolución de una imagen sobre su procesamiento y representación en modelos neuronales.

### Archivo relacionado

- `Multimedia_Ejercicio1.ipynb`: Conversión, análisis y visualización de imágenes con diferentes configuraciones de bits y resolución.

---

## 🔷 Parte 2: Clasificación de Figuras Geométricas Planas con CNN

Se desarrolla una **red neuronal convolucional (CNN)** para reconocer y clasificar figuras geométricas planas (como círculos, triángulos, cuadrados, etc.) a partir de imágenes sintetizadas.

### Objetivo

Entrenar un modelo capaz de identificar automáticamente la figura contenida en una imagen, aplicando técnicas modernas de visión por computador.

### Funcionalidades

- Generación automática de dataset de figuras usando OpenCV.
- Preprocesamiento de imágenes (escalado, normalización).
- Arquitectura CNN simple implementada con Keras.
- Entrenamiento, validación y evaluación del modelo.

### Archivo relacionado

- `Clasificacion_Figuras_cv2.ipynb`: Creación del dataset de figuras geométricas, definición de la red CNN y entrenamiento.

---

## 🧰 Tecnologías Utilizadas

- Python 3
- NumPy
- OpenCV (`cv2`)
- TensorFlow / Keras
- Matplotlib
- Jupyter Notebooks

---

## ▶️ Cómo Ejecutar

1. Clona este repositorio:
   - git clone https://github.com/MiguelNaranjo02/Multi-RNC
   - cd Multi-RNC
2. Instala los requerimientos:
   - pip install -r requirements.txt
3. Cambia las rutas de las imagenes dependiendo de tu computador y usa tus propias imagenes
4. Ejecuta los notebooks en Jupyter o Google Colab (preferiblemente Jupyter en local por temas de memoria RAM)
