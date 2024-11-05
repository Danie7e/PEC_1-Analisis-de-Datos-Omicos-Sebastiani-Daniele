# Metadatos del Dataset "2024-fobitools-UseCase_1" para PEC1 de Análisis de Datos Ómicos

Con ste documento voy a describir los de datos utilizado en el análisis y las
variable contenida en los archivos.

## Archivos de Datos

- **features.csv**: Contiene las mediciones principales del análisis de metabolómica.
Contiene 45 columnas y 1541 filas.
    - **columnas**: Identificador único para cada muestra.
    - **filas**: Medición de cada metabolitos para las diferentes muestras.

- **metadatas.csv**: Incluye información adicional sobre cada muestra.
Contiene 3 columnas y 45 filas.
    - **columnas**: información sobre las muestras:
      - **ID**: Identificador que coincide con el archivo `features.csv`.
      - **Treatment**: Tratamiento con el cual se ha tratado la muestra
      (Cranberry, Apple, Baseline)
    - **filas**: muestras

- **metadatosNames.csv**: Describe el significado de algunas columnas.
Contiene 3 columnas y 1541 filas.
    - **Columna**: información sobre los metabolitos.
      - **names**: Nombre del matabolito
      - **PubChem**: Identificador PubChem del metabolito.
      - **KEGG**: Identificador KEGG del metabolito.
    - **filas**: Metabolitos.

## Información Adicional

- **Fuente de los Datos**: Los datos provienen del estudio con identificador ID: ST000291.
[Enlace estudio](https://www.metabolomicsworkbench.org/data/DRCCMetadata.php?Mode=Study&StudyID=ST000291)

Estas alguna información sobre el estudio:

- database_name = "2024-fobitools-UseCase_1",
- description = "The present study aimed to investigate overall metabolic changes caused by cranberry juice or apple juice consumption using a global LC-MS based metabolomics approach.",
- publication_title = "LC-MS Based Approaches to Investigate Metabolomic Differences in the Urine of Young Women after Drinking Cranberry Juice or Apple Juice",
- authors = "Liu Haiyan",
- publication_DOI = "doi: 10.21228/M8J590",
- institute = "University of Florida",
- department = "Food Science and Nutrition",
- Laboratory = "Gu",
- email = "haiyan66@ufl.edu"

- **Objetivo del Análisis**: 

Este dataset almacena datos de un estudio realizado sobre dieciocho estudiantes 
universitarias sanas, de entre 21 y 29 años, con un IMC normal de 18.5 a 25 que
fueron divididas en grupos y que se le pidio de consumir jugo de arándano o 
jugo de manzana durante un periodo establecido. En un momento dado se le pidió
volver a la clínica para proporcionar una muestra de orina en ayunas y analizar
los metabolitos. Después de un período de lavado de dos semanas, las participantes
cambiaron al régimen alternativo y repitieron el protocolo.
Tres partecipantes fueron excluidas y se quedarno 15 estudiantes.
El estudio porpone estudiar la diferencia de metabolitos encontrados en las 
muestras de urina proporcionadas.