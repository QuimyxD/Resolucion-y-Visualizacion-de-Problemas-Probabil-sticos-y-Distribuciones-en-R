# Resolución y Visualización de Problemas de Probabilidad y Distribuciones en R

Desarrollo de una implementación en **R** para resolver problemas de probabilidad, abarcando espacios muestrales, técnicas de conteo, probabilidad condicional y distribuciones de probabilidad. El proyecto integra variables discretas y continuas mediante **Data Frames** estructurados, combinando cálculos numéricos con la visualización de densidades y probabilidades acumuladas.

El sistema fue diseñado para cubrir los principales aspectos del análisis probabilístico en R: la rigurosidad de los cálculos matemáticos utilizando **R Base**, la generación de gráficos científicos con **ggplot2**, y la exportación automática de resultados para su documentación y análisis.

---

# Estructura del Repositorio

```text
Practica_probabilidad/
├── Proyecto_Final.Rproj        # Archivo de proyecto de RStudio
├── main.R                      # Script principal
├── Data/                       # Datos de entrada
│   └── Datos.txt
├── Funciones/                  # Funciones auxiliares
│   ├── Funcion_1.R
│   ├── Funcion_2.R
│   └── Funcion_3.R
|__ Reporte/
|    |__ Reporte.pdf            # Reporte del proyecto
└── Resultados/                 # Resultados generados automáticamente
    ├── Data.frames/            # Tablas exportadas (.csv)
    └── Graficas/               # Gráficas generadas (.png)
```

---

# Características

| Característica | Descripción |
| :--- | :--- |
| **Arquitectura Modular** | Código organizado en módulos independientes que facilitan el mantenimiento y la reutilización. |
| **Reproducibilidad** | Uso de rutas relativas y `set.seed()` para obtener resultados consistentes en simulaciones. |
| **Visualización Científica** | Creación de funciones de masa de probabilidad, funciones de densidad, distribuciones acumuladas y gráficos estadísticos con **ggplot2**. |
| **Exportación Automática** | Generación automática de tablas (`.csv`) y gráficas (`.png`) en carpetas específicas. |
| **Manipulación de Datos** | Organización y análisis de información mediante **Data Frames** y estructuras de datos de R. |
| **Análisis Probabilístico** | Resolución de ejercicios relacionados con probabilidad clásica, condicional, variables aleatorias discretas y continuas, y distribuciones de probabilidad. |

---

# Tecnologías Utilizadas

- **R**
- **RStudio**
- **ggplot2**
- **dplyr**
- **readr**

---

# Funcionalidades

- Resolución de problemas de probabilidad clásica.
- Cálculo de probabilidades condicionales.
- Técnicas de conteo (permutaciones, variaciones y combinaciones).
- Manejo de variables aleatorias discretas y continuas.
- Construcción de funciones de probabilidad y densidad.
- Visualización de distribuciones mediante gráficos.
- Exportación automática de resultados y evidencias.

---

# Objetivo

Desarrollar una solución modular en **R** que permita automatizar la resolución de ejercicios probabilísticos, facilitar la interpretación de resultados mediante visualizaciones y generar salidas organizadas para su posterior análisis o documentación.
