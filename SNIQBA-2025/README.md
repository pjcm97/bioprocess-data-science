# Análisis Exploratorio Multivariable de un Biodigestor Semicontinuo mediante PCA

## 📋 Descripción y Presentación Científica

Este proyecto implementa **Análisis de Componentes Principales (PCA)** para el estudio de un biodigestor anaerobio semicontinuo operado en la **Facultad de Agronomía de la Universidad Autónoma de Nuevo León (UANL)**. El sistema utiliza co-digestión de estiércol de vaca y residuos de frutas y verduras para la producción de biogás.  

El trabajo es presentado en el **XIII Simposio Nacional de Ingeniería Química y Bioquímica Aplicada (SNIQBA 2025)** en modalidad póster en **Saltillo, Coahuila**, organizado por la [Sociedad Nacional de Ingeniería Química y Bioquímica, A.C.](http://sniqba.com.mx/).  

### 🎯 Objetivos

- **Explorar relaciones** entre variables operativas y de producción  
- **Identificar patrones** temporales en el comportamiento del biodigestor  
- **Detectar eventos atípicos** y cambios en la dinámica del sistema  
- **Reducir dimensionalidad** para facilitar la interpretación de datos multivariables  

## 🔬 Variables del Sistema

| Variable     | Descripción                        | Unidades  |
|--------------|------------------------------------|-----------|
| `ch4`        | Concentración de metano            | ppm       |
| `co2`        | Concentración de dióxido de carbono| ppm       |
| `gas_out`    | Extracción de biogás               | Binaria   |
| `agitation`  | Agitación del biodigestor          | Binaria   |
| `ph`         | pH del sistema                     | -         |
| `EV`        | Estiércol de vaca                  | g         |
| `RFV`        | Residuos de frutas y verduras      | g         |
| `temperature`| Temperatura del biodigestor        | °C        |
| `trh`        | Tiempo de Retención Hidráulico     | días      |
| `olr`        | Tasa de carga orgánica             | g VS/L·d  |

## 📊 Resultados Principales

### Visualizaciones Generadas
- **Gráfico de varianza explicada**: Contribución de cada componente principal  
- **Gráfico de cargas**: Influencia de variables en cada componente  
- **Biplot 2D**: Relaciones entre variables y observaciones  
- **Visualización 3D**: Análisis tridimensional con clustering  

## 📁 Estructura del Proyecto

```

SNIQBA-2025/
│
├── 📂 Notebooks/           # Análisis y código principal
│   ├── pca.ipynb           # Análisis PCA 
│
├── 📂 Figures/             # Figuras en alta resolución
│   ├── varianza\_pca.*      # Gráfico de varianza explicada
│   ├── cargas\_pca.*        # Gráfico de cargas
│   └── biplot\_pca.\*        # Biplot principal
│
└── 📄 README.md            # Este archivo

```

## 📈 Metodología

1. **Preprocesamiento**: Estandarización de variables numéricas  
2. **PCA**: Análisis de componentes principales completo  
3. **Visualización**: Generación de gráficos interpretativos  
4. **Clustering**: Agrupación de días según patrones PCA  
5. **Interpretación**: Análisis de cargas y componentes principales  

## 👥 Autores

- Pedro Jesús Camarena Martínez  
- Nancy Medina Herrera  

### Afiliación  
**Facultad de Agronomía, Universidad Autónoma de Nuevo León (UANL)**  

## 🔒 Política de uso y acceso a datos

Este repositorio tiene fines **exclusivamente de divulgación científica** en el marco del **XIII SNIQBA 2025**.  

- El **código** mostrado no está disponible para libre uso, reproducción ni redistribución.  
- Los **datos experimentales** utilizados en este estudio están reservados para consulta académica.  

Si deseas acceder a los datos o discutir posibles colaboraciones, por favor **contacta directamente con los autores**.  

---

> **Nota sobre IA**: Este trabajo fue desarrollado con asistencia de GitHub Copilot. Todo el contenido ha sido revisado y validado por los autores, quienes mantienen la responsabilidad completa sobre los resultados y las interpretaciones presentadas.  
