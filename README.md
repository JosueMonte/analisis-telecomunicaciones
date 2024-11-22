# Analisis en el sector de las telecomunicaciones

Este repositorio contiene un análisis detallado del sector de las telecomunicaciones. Se considera la principal actividad que es brindar accesos a internet, además de visualizar las tecnologías más importantes y su consecuente velocidad. Esto permitirá al cliente gitla posibilidad de tomar decisiones en cuanto a su negocio y encontrar oportunidades de crecimiento.

## Descripción
Se desarrollan dos fases para el proyecto:

- `Análisis exploratorio de los datos.`
- `Tablero de control para toma de decisiones.`

#### Análisis exploratorio de los datos

Primero se realizan diversas transformaciones en los datos provenientes del dataset de internet, como ser:

- `Selección de las columnas a analizar`.
- `Formateo de las columnas`.

Y luego se realiza el análisis exploratorio o EDA, abordando problemas como:

- `Valores faltantes o nulos.`
- `Datos duplicados`.
- `Valores outliers o anómalos`.
- `Análisis univariado y bivariado.`
- `Análisis de tendencias.`
- `Análisis de segmentos.` 

Como aclaración en el análisis de tendencia en los ingresos, también se extrajo un archivo del IPC de Argentina proveniente de la página del INDEC. Es decir, para el análisis se cruzó los ingresos con la inflación.

#### Tablero de control

Los insights provenientes del análisis exploratorio de los datos se vuelcan a dicho dashboard. En pos de ello, se contruyen gráficas y diversos KPIs que hay considerar para la consecuente toma de decisiones. Las hojas utilizadas son: 

- `Hogar (se muestra la cantidad de accesos a internet por hogar)`
- `Dial_BAf (se enfoca en la cantidad de accesos a Dial up)`
- `Tecnología (se enfoca en la tecnología de fibra óptica)`
- `Velocidad (se visualizan la velocidad media de bajada por provincia)`
- `Ingresos (se muestra la tendencia en los ingresos comparado con la inflación)`
- `Conclusiones (se detallan conclusiones y recomendaciones)`

## Instalación

1. Clona este repositorio:
   ```sh
   git clone https://github.com/JosueMonte/analisis-telecomunicaciones
   ```

2. Instala los paquetes requeridos en el archivo llamado:
   ```sh
   requirements.txt
   ```

3. Para visualizar el dashboard será necesario intalar Power BI desktop:
   ```sh
   Microsoft Store: Power BI Desktop
   ```

## Estructura del repositorio

- `eda.ipynb`: Se realiza el análisis exploratorio del archivo de internet proveniente del dataset de Enacom.
- `dashboard.pbix`: Confección del tablero de control para la toma de decisiones.
- `/dataset/`: Carpeta donde se alojan los archivos exportados del eda.ipynb

## KPIs del dashboard

- `Accesos por hogar`: Se plantea un objetivo para el próximo trimestre de aumentar un 2 % la conectividad por provincia. Como análisis base se considera que esta medida tenderá a 100 accesos por hogar.
- `Accesos a Dial-up`: Se plantea el objetivo para el próximo trimestre de que este valor llegue a 0 y todas las tecnologías usen Banda Ancha. Es cierto que en algunas provincias puede ser difícil, pero no imposible.
- `Accesos a fibra óptica`: Se plantea el objetivo para el próximo trimestre de que este valor aumente un 15 % para cada provincia. El foco radica en que la fibra óptica tiene que ser la principal tecnología instalada en el pais.
- `Velocidad media de bajada en Mbps`: Se plantea un objetivo para el próximo trimestre de que este valor aumente un 15 % en cada provincia. El análisis plantea que, en la búsqueda de ser un pais desarrollado, la velocidad media de bajada debería rondar los 1000 Mbps.
- `Ingresos (miles de pesos)`: Se plantea un objetivo para el próximo trimestre de que este valor incremente un 15 % a nivel pais. El análisis busca que los ingresos aumenten respecto a la inflación. Se considera que la inflación para el próximo trimestre rondará el 10-12 %.

## Consideraciones para los KPIs

Estos objetivos son considerando la tendencia hasta el segundo trimestre del año 2024. Los próximo deben ser ajustados conforme van evolucionando los datos.

## Recomendaciones






