# Análisis exploratorio de sonidos respiratorios

Material de exploración de **señales de audio respiratorio** con Python. El nombre histórico del repositorio hace referencia a detección de enfermedades respiratorias mediante aprendizaje automático, pero los archivos públicos revisados **no permiten acreditar aquí un clasificador final entrenado o validado**.

## Archivos disponibles

| Archivo | Descripción |
| --- | --- |
| [exploracion1](exploracion1) | Script de Python que carga audio respiratorio y utiliza bibliotecas de análisis de señal y visualización. |
| [exploracion2](exploracion2) | Script exploratorio con lectura de audio y bibliotecas como librosa, NumPy y Matplotlib. |
| [exploracion.ipynb](exploracion.ipynb) | Notebook presente en el repositorio, actualmente vacío. |

## Herramientas identificadas

- Python
- NumPy y Matplotlib
- librosa
- Funciones de lectura y procesamiento de audio de SciPy

## Reproducibilidad

Los scripts existentes contienen **rutas absolutas de Windows** hacia un dataset situado en la caché local. Estas rutas no funcionarán automáticamente en otro equipo. Antes de ejecutar el proyecto es necesario:

1. Obtener el conjunto de datos y revisar sus condiciones de uso.
2. Actualizar las rutas de entrada de audio en los scripts.
3. Instalar las dependencias utilizadas por cada archivo.
4. Comprobar formatos, frecuencias de muestreo y resultados de las visualizaciones.

No se ha creado un archivo de dependencias ni modificado código funcional en esta mejora documental.

## Qué falta para hablar de detección automatizada

- Definir la tarea de clasificación y sus clases clínicas con precisión.
- Documentar el conjunto de datos, permisos, criterios de separación y preprocesamiento.
- Publicar, si existe, el entrenamiento reproducible y las métricas de evaluación.
- Presentar resultados experimentales verificables con sus limitaciones.

**Aviso:** este repositorio debe tratarse como exploración de audio, no como herramienta de diagnóstico médico ni como demostración de rendimiento clínico.

---

**Estado:** exploración preliminar; clasificación y validación no verificadas.
