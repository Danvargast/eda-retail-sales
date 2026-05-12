# Análisis Exploratorio de Datos — Retail Sales Dataset

**Proyecto de portafolio | Python · Pandas · Seaborn · Scipy**

---

## Descripción

Análisis exploratorio completo sobre un dataset de **5.000 registros de ventas retail** con 24 variables. El objetivo fue extraer información estratégica para la toma de decisiones comerciales, aplicando tres técnicas fundamentales:

- **Estadística descriptiva** — tendencia central, dispersión y posición
- **Detección y tratamiento de outliers** — método IQR con análisis comparativo
- **Análisis de correlación** — Pearson y Spearman con heatmaps

---

## Hallazgos principales

- Las ventas muestran **alta heterogeneidad**: el valor total por orden varía entre clientes pequeños y grandes cuentas corporativas, evidenciando una cartera diversificada.
- Se detectaron outliers en variables monetarias consistentes con pedidos corporativos de alto volumen. Tras la limpieza, la desviación estándar se redujo significativamente en todas las variables.
- **Office Supplies** concentra el 79% de las órdenes, mientras que Furniture representa apenas el 3.4% — señal clara de priorización de recursos.
- El canal **Regular Air** domina con el 84.7% del volumen de envíos, sugiriendo oportunidad de optimización logística.
- La correlación entre variables de precio y totales de orden confirma redundancia estructural: útil para simplificar modelos predictivos futuros.

---

## Tecnologías utilizadas

| Librería | Uso |
|:---------|:----|
| `pandas` | Carga, limpieza y transformación de datos |
| `numpy` | Cálculos estadísticos y manejo de arrays |
| `matplotlib` | Visualizaciones base y personalización |
| `seaborn` | Heatmaps y gráficos estadísticos |
| `scipy` | Soporte estadístico |

---

## Estructura del proyecto

```
├── archive/
│   └── data.csv                          # Dataset original (Retail Sales)
├── EDA_RetailSales_DanielVargas.ipynb    # Notebook principal con análisis completo
└── README.md
```

---

## Cómo ejecutar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/TU_USUARIO/eda-retail-sales.git
   cd eda-retail-sales
   ```

2. Instala las dependencias:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy jupyter
   ```

3. Abre el notebook:
   ```bash
   jupyter notebook EDA_RetailSales_DanielVargas.ipynb
   ```

4. Ejecuta todas las celdas: `Kernel → Restart & Run All`

---

## Estructura del notebook

| Sección | Contenido |
|:--------|:----------|
| **1. Carga y Exploración** | Dimensiones, tipos de variables, calidad de datos, limpieza |
| **2. Estadística Descriptiva** | Media, mediana, moda, desv. estándar, varianza, Q1, Q3, IQR para 10 variables numéricas + frecuencias para 5 variables categóricas |
| **3. Detección de Outliers** | Método IQR, boxplots antes/después, análisis comparativo |
| **4. Análisis de Correlación** | Matrices Pearson y Spearman, heatmaps, propuesta de reducción de variables |
| **5. Conclusiones** | Hallazgos de negocio, limitaciones, consideraciones éticas |

---

## Autor

**Daniel Vargas**
Analista de Datos | Python · SQL · Visualización · EDA

> Disponible para proyectos freelance de análisis de datos, limpieza de datasets y generación de reportes con insights de negocio.
