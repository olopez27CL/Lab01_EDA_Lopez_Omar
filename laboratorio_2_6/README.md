# Laboratorio 2.6: Reglas de asociación

**Estudiante:** Omar Lopez

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olopez27CL/Lab01_EDA_Lopez_Omar/blob/main/laboratorio_2_6/Laboratorio_2_6_Reglas_Asociacion.ipynb)

## Objetivo
Identificar productos que suelen comprarse juntos en una panadería
mediante el algoritmo Apriori y proponer una decisión comercial.

## Dataset
Se utilizó Bakery, del autor akashdeepkuila, descargado desde Kaggle
mediante kagglehub y credenciales guardadas en Colab Secrets.

Después de la limpieza quedaron 9.464 compras y 93 productos distintos.

Fuente: https://www.kaggle.com/datasets/akashdeepkuila/bakery

## Comparación de configuraciones

| Configuración | Soporte mínimo | Confianza mínima | Conjuntos frecuentes | Reglas |
|---|---:|---:|---:|---:|
| Exigente | 5% | 60% | 11 | 0 |
| Intermedia | 2% | 40% | 33 | 8 |
| Exploratoria | 1% | 20% | 61 | 31 |

## Contenido del notebook
- Carga, revisión y limpieza de datos.
- Codificación de presencia y ausencia de productos.
- Obtención de conjuntos frecuentes y reglas.
- Comparación de tres configuraciones.
- Interpretación de cinco reglas y descarte justificado de una regla.
- Propuesta comercial, comprobación manual y reflexión final.

## Ejecución
Abrir el notebook mediante el botón Open in Colab.
Configurar el secreto KAGGLE_API_TOKEN con un token propio de Kaggle
y habilitar su acceso al notebook.
Ejecutar todas las celdas en orden.

## Propuesta
Probar un paquete de tostada con café y evaluar sus ventas y rentabilidad.
Las asociaciones encontradas no demuestran relaciones de causa.
