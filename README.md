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

1. **Comprender el problema**
2. **Análisis exploratorio de datos (EDA)**:
   - Visualizar imágenes y distribución de edades.
   - Evaluar balance y calidad del conjunto.
3. **Entrenamiento del modelo**:
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
