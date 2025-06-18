# 🧠 Clasificación de Edad con Visión Artificial — Proyecto Good Seed

Este proyecto tiene como objetivo desarrollar un modelo de aprendizaje profundo que determine la edad aproximada de una persona a partir de una fotografía. La cadena de supermercados **Good Seed** busca implementar esta tecnología en sus tiendas para **prevenir la venta de alcohol a menores de edad**, cumpliendo con las regulaciones legales.

---

## 📘 Descripción del Proyecto

Las tiendas **Good Seed** están equipadas con cámaras en las áreas de pago. Estas cámaras se activan cuando una persona intenta comprar alcohol, y se propone usar modelos de visión por computadora para estimar si el cliente es mayor de edad (18+).

Para ello, se proporciona un conjunto de datos de imágenes de rostros etiquetadas con edades. La meta del proyecto es:

- Analizar el conjunto de imágenes.
- Construir y entrenar un modelo de red neuronal convolucional (CNN).
- Evaluar su rendimiento para clasificar correctamente la edad.

---

## 🗂️ Instrucciones del Proyecto

1. **Comprender el problema**: Pasar un cuestionario de comprensión.
2. **Análisis exploratorio de datos (EDA)**:
   - Visualizar imágenes y distribución de edades.
   - Evaluar balance y calidad del conjunto.
3. **Entrenamiento del modelo** (en plataforma con GPU):
   - Preprocesamiento de imágenes.
   - División en conjuntos de entrenamiento y prueba.
   - Construcción y entrenamiento de una red neuronal.
4. **Evaluación del modelo**:
   - Medición de precisión del modelo (RMSE o métricas de clasificación si se agrupan rangos de edad).
5. **Conclusiones**:
   - Interpretar resultados, limitaciones y posibles mejoras.
   - Todo documentado en un Jupyter Notebook.

---

## 🧠 Modelos Utilizados

- **Red Neuronal Convolucional (CNN)** con TensorFlow/Keras.
- Posible uso de **transfer learning** (ej. MobileNet, ResNet) para mejorar la precisión.

---

## 🧪 Evaluación del Proyecto

Los siguientes aspectos fueron clave en el desarrollo y revisión del proyecto:

- ¿Cómo se analizó y limpió el conjunto de datos?
- ¿Cómo se dividieron los datos en entrenamiento y prueba?
- ¿Qué arquitectura de red se utilizó y por qué?
- ¿Cómo se ajustaron los hiperparámetros?
- ¿Qué tan bien generaliza el modelo?
- ¿Se mantuvo una buena estructura y limpieza del código?

---

## 📁 Estructura del Proyecto

```bash
GoodSeed-AgeVerification/
│
├── data/
│   └── images/                 # Imágenes de rostros con etiquetas de edad
│
├── notebooks/
│   └── age_estimation.ipynb    # Jupyter notebook principal
│
├── models/
│   └── cnn_model.h5            # Modelo entrenado
│
├── src/
│   ├── dataloader.py           # Funciones de carga y procesamiento de datos
│   ├── model.py                # Definición de la red neuronal
│   └── utils.py                # Utilidades generales
│
├── README.md                   # Este archivo
└── requirements.txt            # Dependencias del proyecto
