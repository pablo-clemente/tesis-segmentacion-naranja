# Segmentación de Imágenes de Cultivos de Naranja con CNN en Agricultura de Precisión

Este repositorio contiene el trabajo de tesis desarrollado por **Pablo Clemente Moreno**, el cual evalúa la efectividad de Redes Neuronales Convolucionales (CNN) para la segmentación de imágenes aéreas de cultivos de naranja, en comparación con otros algoritmos de clasificación y modelos de aprendizaje automático.

## 🧪 Resumen del Trabajo

El presente estudio se centra en evaluar si el proceso de segmentación de imágenes de un cultivo de naranja puede mejorarse mediante el uso de Redes Neuronales Convolucionales, en comparación con otros algoritmos de clasificación y modelos de aprendizaje automático, integrando productos obtenidos mediante software de procesamiento fotogramétrico.

La segmentación precisa de imágenes es crucial, no solo para identificar la ubicación de árboles y signos de plaga, sino también para identificar la distribución espacial y facilitar la resolución de problemas localizados como plagas o deficiencias de los cultivos en el contexto de la agricultura de precisión.

El objetivo principal es, por tanto, explorar la efectividad de las Redes Neuronales en la mejora del análisis de imágenes aéreas para este tipo de cultivo y analizar su aplicabilidad en la toma de decisiones agrícolas.

## 🛠️ Herramientas y Técnicas Utilizadas

- **Software**: ArcGIS Pro, SAM (Segment Anything Model), edición manual
- **Algoritmos**: SVM (Support Vector Machine)
- **Redes Neuronales**: ResNet-34 + Dynamic U-Net (FastAI)

## 📂 Contenido del Repositorio

- `linares-cnn-model.ipynb`: Notebook principal con el entrenamiento y evaluación del modelo.
- `images/`: Imágenes aéreas de entrada.
- `labels/`: Máscaras segmentadas por clase (árboles, plagas, etc.).
- `codes.txt`: Codificación de las clases utilizadas.
- `requirements.txt`: Librerías necesarias para ejecutar el notebook.
- `.gitignore`: Exclusión de archivos temporales y de sistema.

## 🚀 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/tu_usuario/tesis-naranja-segmentacion.git
cd tesis-naranja-segmentacion
```

2. Instala los requisitos:
```bash
pip install -r requirements.txt
```

3. Abre la notebook:
```bash
jupyter notebook linares-cnn-model.ipynb
```

## 👨‍🎓 Autor

**Pablo Clemente Moreno**  
Tesis de grado – 2025  
Agricultura de Precisión y Visión por Computadora
