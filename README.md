# Proyecto hipótesis

## Resumen
Proyecto desarrollado en BigQuery y presentado en Power BI acerca de un dataset del 2023 con información de canciones de Spotify.

## Contenido
1. [Objetivo]()
2. [Introducción]()
3. [Metodología]()
4. [Resultados]()
5. [Conclusionesy recomendaciones]()

## Objetivo 
Proporcionar recomendaciones estratégicas basadas en los hallazgos resultantes de validar hipótesis. El objetivo es que la discográfica y el nuevo artista puedan tomar decisiones informadas que aumenten sus posibilidades de conseguir el “éxito”.

## Introducción
En un mundo en el que la industria musical es extremadamente competitiva y está en permanente evolución, la capacidad de tomar decisiones basadas en datos se ha convertido en un activo invaluable.

En este contexto, una discográfica se enfrenta al emocionante desafío de lanzar un nuevo artista en el escenario musical global. Cuenta con un extenso dataset de Spotify.

La discográfica planteó las siguientes 5 hipótesis acerca de lo podría hacer que una canción sea más escuchada. 

* Las canciones con un mayor BPM (Beats Por Minuto) tienen más éxito en términos de cantidad de streams en Spotify.
* Las canciones más populares en el ranking de Spotify también tienen un comportamiento similar en otras plataformas como Deezer.
* La presencia de una canción en un mayor número de playlists se relaciona con un mayor número de streams.
* Los artistas con un mayor número de canciones en Spotify tienen más streams totales.
* Las características de la música influyen en el éxito en términos de cantidad de streams en Spotify.

## Metodología

Para más detalle del desarrollo del proyecto da click [aquí](https://colab.research.google.com/drive/167ST72UdpPPgN4-55t6nm5Ds1Ib7nKEr?usp=sharing)

#### Datos
Dataset de Spotify con información sobre las canciones más escuchadas en 2023.

#### Recursos
SQL (Big Query), Python (Google Colab) y Power BI.

#### Limpieza del dataset > Análisis exploratorio > Aplicar técnica de análisis 

## Resultados
### Hipótesis 1: 
![](https://github.com/YazminJoandi/proyecto-hipotesis/blob/main/hipotesis1.png)

REFUTADA
Correlación negativa cercana a cero. 

### Hipótesis 2:

![](https://github.com/YazminJoandi/proyecto-hipotesis/blob/main/hipotesis2.png)

CONFIRMADA
Correlacioń positiva de 0.60

### Hipótesis 3:

![](https://github.com/YazminJoandi/proyecto-hipotesis/blob/main/hipotesis3.png)

CONFIRMADA
Correlación de 0.78

### Hipótesis 4:

![](https://github.com/YazminJoandi/proyecto-hipotesis/blob/main/hipotesis4.png)

RECHAZADA
Correlación -0.13

### Hipótesis 5:

![](https://github.com/YazminJoandi/proyecto-hipotesis/blob/main/hipotesis5.png)

## Conclusiones y recomendaciones

Para más detalles, da click [aquí]()

## Tecnologías


![Python](https://img.shields.io/badge/Language-Python-blue?logo=python)
![Pandas](https://img.shields.io/badge/Library-Pandas-green?logo=pandas)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-blue?logo=plotly)
![Seaborn](https://img.shields.io/badge/Library-Seaborn-blue?logo=seaborn)
![Scikit-learn](https://img.shields.io/badge/Library-Scikit_Learn-yellow?logo=scikit-learn)
![Power BI](https://img.shields.io/badge/BI_Tool-Power_BI-yellow?logo=power-bi)
![Git](https://img.shields.io/badge/Version_Control-Git-red?logo=git)
![Google Drive](https://img.shields.io/badge/Tool-Google_Drive-blue?logo=google-drive)
![Slack](https://img.shields.io/badge/Chat-Slack-purple?logo=slack)

