# PROYECTO 'FRIENDS':  Análisis de Datos de la Icónica Serie.

<p align="center">
  <img src="images/Friends_logo.svg.png" width="100%" alt="Friends Banner">
</p>

## ¡Bienvenido al Central Perk de los datos!

Este repositorio recoge el trabajo de análisis y visualización realizado sobre el universo de la serie Friends. A través de Tableau Public, hemos transformado numerosas líneas de guiones y métricas de audiencia en un Dashboard interactivo que revela los datos que nos han parecido más relevantes de los seis amigos más famosos de Nueva York.


## Objetivo principal del proyecto: 

El propósito principal es demostrar la capacidad técnica para gestionar fuentes de datos complejas, realizar limpieza de datos mediante campos calculados y diseñar visualizaciones que cuenten una historia clara y atractiva y hagan accesible el entendimiento de la información recavada. 



## Objetivos pormenorizados:

Los objetivos están divididos de acuerdo a los ejercicios de cada sesión de trabajo. 

1.  **Importación y gestión de datos en Tableau:**
    *   Descarga y guardado de los datasets en una carpeta local.
    *   Carga del primer dataset para comprobación de la correcta carga de los datos, el formato de las columnas, separadores y configuración regional.
    *   Unión de datasets y verificación de los datos.
    *   Incorporación de una segunda fuente de datos con las comprobaciones necesarias.
    *   BONUS de transformación de columnas: División con separador.


2.  **Creación gráficas iniciales de análisis:**
    *   Big Numbers: Práctica de métricas clave y funciones de agregación.
    *   Gráfico de barras: Comparación de catergorías usando codificación visual dual (altura + color).
    *   Gráfico de líneas: Análisis de tendencias temporales.
    *   Histograma: Comprensión de la distribución de audiencia.
    *   Gráfico circular: Identificar proporciones en una variable categórica.


3.  **Personalización de gráficas:**
    *   Eje doble.
    *   Donut.
    *   Primer esbozo de dashboard.


4.  **Filtros:**
    *   Filtro Top N.
    *   Filtro por categoría (temporadas).
    *   Descripciones emergentes.
    *   Inserción de imágenes.
    *   Contenedores y formato de los Big Numbers.


5.  **Inconsistencia de los datos:**
    *   Limpieza columna 'Author'.
    *   Función CONTEINS y métodos LOWER, UPPER, etc.
    *   Crear campo de capítulo y temporada.
    *   Personalización creativa modificando colores de contenedores, filtros, botones, etc.

6.  **Personalización del enfoque del proyecto:**
    *   Desarrollo de un enfoque personal para abordar las visualizaciobnes
    *   Creación de dashboards que faciliten la comprensión de los insights seleccionados.


## Insights y Visualizaciones Destacadas:

A partir del análisis de los distintos datasets, hemos desarrollado las siguientes visualizaciones clave:

1. El Pulso de la Audiencia (Big Numbers & Tendencias)
Métricas Clave: Visualización de la audiencia media y el total de episodios para entender el alcance global de la serie.

Evolución por Temporada: Un gráfico de líneas que muestra cómo el interés del público fluctuó, identificando los "picos" de popularidad.

2. ¿Quién domina la conversación? (Análisis de líneas de diálogo)
Utilizando técnicas de limpieza de datos con funciones LOWER, UPPER y CONTAINS, hemos normalizado la columna Author para identificar quién tiene más peso en los diálogos.

Gráfico de Barras: Comparamos el volumen de frases por personaje, utilizando color y altura para resaltar a los protagonistas.

3. Emociones a flor de piel:
Cruzando el dataset de frases con el de emociones, hemos creado una visualización de Burbujas Empaquetadas que muestra el "clima emocional" de la serie, según el escenario.

Identificamos que la emoción más destacada en todod los escenarios es la alegría, y eso nos llevó a centrarnos posteriormente en el personaje más alegre: Phoebe.

4. Personalización en Tableau:
Diseño Creativo: Uso del Marco Amarillo de Monica como contenedor visual, paletas de colores personalizadas basadas en los colores del Central Perk, botones de navegación, descripciones emergentes, etc.


## Desafíos técnicos superados:

* Limpieza de Datos: Gestión de inconsistencias en los nombres de los personajes ("Rachel", "RACHEL").

* Arquitectura de Datos: Unión de múltiples datasets (episodios, info y frases) asegurando su correcta relación.

* Cálculos Avanzados: Creación de campos para agrupar escenarios por palabras clave (si la frase contiene "coffee", asignar al "Central Perk").


## Estructura del repositorio:

* /data : Datasets originales obtenido de Kaggle.
* /images : Imágenes usadas para el proyecto.
* PairFriends-local.twbx : Libro de trabajo de Tableau Public, con todas las hojas de los ejercicios y dashboards.


## Equipo PAIR1:

Proyecto realizado (con casi tanto café ☕ como el consumido por los personajes a lo largo de las 10 temporadas) por el **PAIR 1** de la promoción 60 del bootcamp de Data Analytics de Adalab, formado por:
* Elena Pavón
* Romina Altamura
* Andrea R.Virgós.

### Análisis de café consumido por temporada:
![Gráfica de café](images/gráfica%20café.png)
*Recuento de consumo de café por temporada en el set del Central Perk.*

## Enlaces de Interés

* **Dashboard Interactivo:** [Ver en Tableau Public](friends - definitivo.twbx)
* **Datasets originales:**
    * [Dataset Principal - Kaggle](https://www.kaggle.com/datasets/rezaghari/friends-series-dataset?select=friends_episodes_v3.csv)
    * [Dataset Complementario - Kaggle](https://www.kaggle.com/datasets/sujaykapadnis/friends?select=friends_info.csv)
    * [Dataset Transcripciones - Kaggle](https://www.kaggle.com/datasets/ryanstonebraker/friends-transcript)

