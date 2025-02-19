# 📔 Bookdown: Índice de Calidad del Entorno (ICE) - CONAPO

El Índice de Calidad del Entorno (ICE) es un indicador que busca analizar las características de los factores contextuales determinados por las condiciones de marginación, la disponibilidad y concentración de servicios y el equipamiento urbano. El ICE permite valorar y diferenciar municipios y localidades según los efectos facilitadores o de barrera que genera el entorno para la población.

## 📑 Contenido

El bookdown se estructura en los siguientes capítulos:

1.  **Introducción** - Contexto y objetivos del estudio.
2.  **Metodología** - Descripción de la construcción del ICE.
3.  **Fuentes de Datos** - Datos utilizados y su procesamiento.
4.  **Resultados** - Análisis y visualizaciones.
5.  **Históricos** -Avances en el tema de discapacidad.
6.  **Marco Normativos** - Normas Oficiales de la Federación (NOM).\
7.  **Marco Teóricos** - Aproximaciones e investigaciones en materia del entorno.
8.  **Conclusiones** - Reflexiones y hallazgos principales.

## Metodología

La construcción del ICE se realizó en cuatro etapas:

1.  **Construcción de indicadores:** Se identificaron y analizaron una serie de indicadores simples asociados a las tres dimensiones que lo componen (sociodemográfica, equipamiento y accesibilidad).
2.  **Análisis de Componentes Principales (PCA):** Se redujo la complejidad de múltiples dimensiones en unas pocas componentes que explicaran la mayor parte de la varianza de los datos originales.
3.  **Regresión de Componentes Principales (PCR):** Se ajustó un modelo de regresión lineal por mínimos cuadrados empleando como predictores las componentes generadas en el PCA.
4.  **Cálculo del ICE:** Se aplicó un método de distancias para obtener el ICE a partir de los resultados de la PCR.

## Resultados

El ICE 2020 permite valorar y diferenciar municipios y localidades según los efectos facilitadores o de barrera que genera el entorno para la población. Es una herramienta útil para la toma de decisiones en materia de políticas públicas y para la planificación del desarrollo territorial.

### Nivel municipal

<img src="images/Municipio/ICE_Mun_Mapa.png" width="70%">

### Nivel localidad

<img src="images/Localidad/ICE_Loc_Mapa.png" width="70%">

## 🛠️ Instalación y Uso
Para visualizar el bookdown localmente, sigue estos pasos:
  
  1. Clonar el repositorio:
  ```sh
git clone https://github.com/dvillasana/bookdown_ICE.git
cd bookdown_ICE
```
2. Instalar las dependencias en R:
  ```r
install.packages("bookdown")
```
3. Compilar el bookdown:
  ```r
bookdown::render_book("index.Rmd")
```

## 🌐 Publicación
El bookdown está disponible en [Netlify](https://ice-bookdown.netlify.app/) para consulta en línea.

## Referencias

-   Instituto Nacional de Estadística y Geografía (2021). Censo Nacional de Población y Vivienda 2020. México: INEGI.
-   Secretaría General del Consejo Nacional de Población. (2023). Índices de marginación 2020. <https://www.gob.mx/conapo/> documentos/indices-de-marginacion-2020- 284372 Consejo Nacional de Población, Instituto Mexicano del Transporte y Centro de Investigación en Ciecias de Información Geoespacial. (2023). Análisis geoespacial de la accesibilidad a centros urbanos de las localidades de México. <https://www>. gob.mx/conapo/documentos/analisis-geoespa- cial-de-la-accesibilidad-a-centros-urbanos-de- las-localidades-de-mexico?idiom=es.
-   Secretaría General del Consejo Nacional de Población (2023). Índice de Calidad del Entorno 2020. México: CONAPO.
-   Secretaría de Desarrollo Social (2012). Sistema Normativo de Equipamiento. México: SEDESOL.

## Licencia

Este documento está licenciado bajo la licencia Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0). Esto significa que puedes copiar, distribuir y modificar el trabajo, siempre y cuando atribuyas la obra original y la compartas bajo los mismos términos.
