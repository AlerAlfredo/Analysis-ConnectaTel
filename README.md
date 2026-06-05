# Analysis-ConnectaTel

# ConnectaTel Analysis – Sprint 7

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso Connecta Telecomunicaciones.

Se incluyen 3 datasets:
El dataset `plans` incluye los dos planes básico y premium con las características de cada uno. 
Los datasets `users_plans` y `usage` incluyen 4,000 registros de clientes con valores faltantes, sentinels, outliers y problemas de calidad diseñados para simular datos reales. 
Fuente: Base de datos histórica de ConnectaTel. Datos demográficos y de consumo analizados bajo un entorno controlado de simulación comercial para fines de optimización interna.

## 📂 Contenido del repositorio

- `S7 Version-Estudiante-Project-ConnectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AlerAlfredo/Analysis-ConnectaTel/blob/main/S7_Version_Estudiante_Project_ConnectaTel.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `S7 Version-Estudiante-Project-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

- Aplicar técnicas de validación, estandarización de tipos de datos y detección de valores inconsistentes. 
- Construir un perfil estadístico del uso (llamadas y mensajes) por clientes.
- Detectar outliers y comportamientos atípicos mediante métodos estadísticos y visuales. 
- Crear segmentaciones de clientes basadas en edad y comportamiento de uso.
- Visualizar diferencias entre segmentos y extraer insights comerciales relevantes. 
