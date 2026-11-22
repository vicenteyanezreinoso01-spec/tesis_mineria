# Evaluación de estrategias de cobertura frente a las fluctuaciones del precio del cobre cátodo en la mediana minería chilena

Memoria de título, Ingeniería Comercial, Universidad Técnica Federico Santa María.
Autor: Vicente Yáñez Reinoso. Profesor guía: Joaquín Vergara.

Este repositorio contiene el cuaderno y los datos del análisis cuantitativo de la memoria (capítulo 4), descrito en el capítulo 3.

## Contenido

| Archivo | Descripción |
|---|---|
| `TESIS_COLAB.ipynb` | Cuaderno de Google Colab. Cada sección corresponde a un apartado del capítulo 4 y reproduce sus tablas y figuras con la numeración de la tesis. |
| `datos/Precio_cobre_mensual_1960_2026.xlsx` | Hoja "Contado y futuro 2005-2026": promedio mensual del precio contado y del precio a tres meses del cobre Grado A en la Bolsa de Metales de Londres, en centavos de dólar por libra. Hoja "Serie 1960-2026": precio contado mensual de largo plazo (se usa desde 1990 en el análisis de sensibilidad). |
| `datos/FUENTE PRINCIPAL - Cochilco - Cotizaciones contado y futuro diaria 2005-2026.xls` | Cotizaciones diarias del precio contado y a tres meses publicadas por Cochilco. Se usa en el apartado 4.3 para construir el precio del último día hábil de cada mes (Tabla 14). |

Fuente de los datos: Comisión Chilena del Cobre (Cochilco). Período: enero de 2005 a julio de 2026 (259 observaciones mensuales y 258 rendimientos).

## Cómo ejecutar el cuaderno

1. Abrir `TESIS_COLAB.ipynb` en Google Colab.
2. *Entorno de ejecución → Ejecutar todas*. Cada celda de código carga sus datos desde este repositorio y puede ejecutarse por separado. Los escenarios se generan con una semilla fija (2026), por lo que los resultados son reproducibles.

| Sección del cuaderno | Apartado de la tesis | Tablas y figuras |
|---|---|---|
| 1 | 4.2.1 y 4.2.2 | Tabla 1; Figuras 1, 2 y 3; Tablas 8 y 9 |
| 2 | 4.2.3 | Figuras 4, 5 y 6; Tabla 10 |
| 3 | 4.3.1 y 4.3.2 | Figuras 7 a 10; Tablas 11 a 16 |
| 4 | 4.4 | Figura 11; Tabla 17 |
| 5 | 4.5 | Tablas 18 a 21; Figuras 12 y 13 |
| 6 | 4.6 | Tablas 22 a 24; Figura 14 |
| 7 | 3.5, 3.6, 4.5 y 4.6 | Verificaciones complementarias citadas en el texto |

## Versiones

Python 3.13, pandas 2.2.3, NumPy 2.4.6, SciPy 1.16.3, statsmodels 0.15.0 y arch 9.0.0 (apartado 3.6.3).
