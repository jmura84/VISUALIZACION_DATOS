# VISUALIZACION_DATOS
# Visualización de Datos sobre CO₂ y Temperatura en Europa (PRAC 2)

Este proyecto forma parte de la asignatura *Visualización de Datos* del Máster de Ciencia de Datos de la UOC.

Aquí se presentan visualizaciones interactivas y estáticas sobre la evolución de indicadores medioambientales en Europa, como:

- Temperatura media
- Emisiones de CO₂ per cápita
- Gases de efecto invernadero
- Vehículos eléctricos
- Comparativas entre países y con España

---

## 📁 Estructura del proyecto

```
├── data/               # Datasets utilizados (CSV y shapefile)
├── graphs/             # Imágenes PNG y visualizaciones interactivas en HTML
├── index.html          # Página principal que organiza todas las visualizaciones
├── visualizacion_datos_data_prep.ipynb  # Notebook de generación
```

---

## 🌐 Cómo visualizar el proyecto

Puedes abrir el archivo `index.html` directamente o acceder al proyecto en línea a través de:

👉 **[GitHub Pages](https://jmura84.github.io/VISUALIZACION_DATOS/)**  

No se requiere registro.

---

## 🛠️ Requisitos para ejecutar el proyecto

- Python 3.8 o superior
- Jupyter Notebook

### Bibliotecas utilizadas:

```python
import pandas as pd
import matplotlib.pyplot as plt
from sklearn.preprocessing import MinMaxScaler
import seaborn as sns
import geopandas as gpd
import folium
from folium.features import GeoJsonTooltip, DivIcon
from branca.colormap import LinearColormap
import plotly.express as px
import plotly.io as pio
import statsmodels.api as sm
from statsmodels.stats.outliers_influence import variance_inflation_factor
```

---

## 📜 Licencia

Este proyecto está publicado bajo la [Licencia MIT](LICENSE).

---

## 👤 Autor

Javier Muñoz  
Máster de Ciencia de Datos – UOC
