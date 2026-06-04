# 👗 Clasificador de Imágenes de Ropa con Deep Learning

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yasminbeltre/clasificador-imagenes-ropa-dl/blob/main/clasificador_imagenes_ropa_dl.ipynb)

> Proyecto académico desarrollado como parte del curso de Inteligencia Artificial — Módulo 4  
> **Autora:** Yasmin Beltre | Customer Success & Operations Specialist  
> [![LinkedIn](https://img.shields.io/badge/LinkedIn-Yasmin%20Beltre-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/yasminbeltre)

---

## 📌 Descripción

Red neuronal profunda entrenada para clasificar automáticamente 10 categorías de prendas de vestir usando el dataset Fashion MNIST, implementada con TensorFlow y Keras.

---

## 🎯 Objetivo

Demostrar el uso de Deep Learning para resolver un problema de visión por computadora, clasificando imágenes de ropa de forma automática y precisa.

---

## 🛠️ Tecnologías utilizadas

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-orange?style=flat&logo=googlecolab)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=flat&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?style=flat)

- **Python 3**
- **Google Colab**
- **TensorFlow**
- **Keras**
- **NumPy**
- **Matplotlib**

---

## 🏷️ Categorías clasificadas

| # | Categoría |
|---|---|
| 0 | Camiseta |
| 1 | Pantalón |
| 2 | Suéter |
| 3 | Vestido |
| 4 | Abrigo |
| 5 | Sandalia |
| 6 | Camisa |
| 7 | Tenis |
| 8 | Bolso |
| 9 | Botín |

---

## 🧠 Arquitectura del modelo

```
Flatten (28x28) → Dense 128 (ReLU) → Dropout 0.2 → Dense 64 (ReLU) → Dense 10 (Softmax)
```

---

## 📈 Resultados

| Métrica | Valor |
|---|---|
| Imágenes de entrenamiento | 60,000 |
| Imágenes de prueba | 10,000 |
| Categorías clasificadas | 10 |
| **Precisión final** | **87.72%** |

---

## 🚀 ¿Cómo ejecutarlo?

1. Abre el archivo `.ipynb` en **Google Colab**
2. Ejecuta las celdas en orden
3. El dataset se carga automáticamente desde TensorFlow
4. El entrenamiento tarda aproximadamente **2-3 minutos**

---

## 👩‍💼 Sobre la autora

**Yasmin Beltre** — Customer Success & Operations Specialist con 20+ años optimizando operaciones y procesos. Especializada en CRM Management, Process Optimization y Digital Transformation con foco en AI in Business.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Conectar-blue?style=flat&logo=linkedin)](https://www.linkedin.com/in/yasminbeltre)

---

*Proyecto desarrollado como parte del curso de Inteligencia Artificial — 2026*
