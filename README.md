# 🌍 earthquakes_app

![earthquakes_app img](img/Eart.jpg)

**earthquakes_app** es un dashboard interactivo y profesional para el análisis avanzado de actividad sísmica, desarrollado en Python con [Streamlit](https://streamlit.io/) y [Plotly](https://plotly.com/python/). Permite explorar, visualizar y analizar datos de terremotos a nivel mundial de manera intuitiva y flexible.


## 🚀 Características principales

- **Visualización interactiva:** Mapas, histogramas, gráficos de dispersión y tablas dinámicas
- **Filtros avanzados:** Por fecha, magnitud, profundidad, tipo de evento y región
- **Análisis de clústeres:** Identificación de agrupamientos espaciales usando DBSCAN
- **Análisis temporal:** Evolución diaria, semanal y horaria de la actividad sísmica
- **Comparaciones y correlaciones:** Matrices de correlación y análisis comparativo entre variables
- **Exportación de datos:** Descarga de los datos filtrados en formato CSV
- **Interfaz profesional:** Navegación por pestañas, métricas clave y opciones avanzadas

## 🛠️ Tecnologías utilizadas

- Python 3.8+
- [Streamlit](https://streamlit.io/)
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- [Plotly](https://plotly.com/python/)
- [Matplotlib](https://matplotlib.org/)
- [scikit-learn](https://scikit-learn.org/)
- [datetime](https://docs.python.org/3/library/datetime.html)

## 📦 Instalación

1. **Clona este repositorio:**
```bash
git clone https://github.com/tu_usuario/earthquakes_app.git
cd earthquakes_app
```

2. **Instala las dependencias** añadiendo el archivo de datos sísmicos (`all_month.csv`) en la carpeta `data`. 
    Puedes descargar los datos desde [USGS Earthquake Catalog](https://earthquake.usgs.gov/earthquakes/feed/).

## ▶️ Uso

1. Ejecuta la aplicación:
```bash
streamlit run app.py
```
2. Abre tu navegador en `http://localhost:8501`

## 📊 Estructura del dashboard

La aplicación (`app.py`) organiza la visualización en pestañas:

- **General Summary:** Métricas clave y distribuciones
- **Geographic Analysis:** Mapas interactivos y análisis de clústeres
- **Temporal Analysis:** Evolución diaria y patrones temporales
- **Advanced Analysis:** Correlaciones y análisis comparativos
- **Tabla de datos:** Visualización y exportación de datos

## 💡 Personalización

- Modifica los filtros y visualizaciones en `app.py`
- Integra nuevas fuentes de datos o ajusta parámetros de clustering

## 📝 Licencia

Este proyecto está bajo la licencia MIT. Ver archivo [LICENSE](LICENSE) para detalles.

## 🤝 Contribuciones

¡Las contribuciones son bienvenidas! Abre un issue o pull request.

## 📬 Contacto

¿Dudas o sugerencias? Abre un [issue](../../issues) o contacta a tu_email@ejemplo.com
