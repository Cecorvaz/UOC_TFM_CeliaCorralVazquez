# UOC_TFM_CeliaCorralVazquez
Repositorio de códigos utilizados para la elaboración del Trabajo de Fin de Máster (TFM) realizado por Celia Corral-Vázquez para el máster de Bioinformática y Bioestadística de la UOC.

Aquí se encuentran los scripts (formato Rmarkdown) utilizados para el análisis de los datos single-cell RNA-seq provenientes de células mononucleares CD45+ de lámina propia de intestino delgado de ratón. Se intergaron y analizaron seis muestras provenientes de dos cepas de ratones:

* Ratones C57BL/6 wildtype (N = 3)
* Ratones C57BL/6 IgA-KO (N = 3)

En total, este repositorio contiene la siguiente información:

Carpeta principal:

* Archivo XXXXX.rmd: código en formato R markdown del análisis inicial de controles de calidad, filtrado y las pruebas de integración de las muestras.
* Archivo XXXXX.html: informe del análisis inicial de controles de calidad, filtrado y las pruebas de integración de las muestras.
* Archivo XXXXX.rmd: código en formato R markdown del análisis de clustering y anotación de los clusters y subclusters.
* Archivo XXXXX.html: informe del análisis de clustering y anotación de los clusters y subclusters.
* Archivo XXXXX.rmd: código en formato R markdown de la descripción general de todos los superclusters y subclusters.
* Archivo XXXXX.html: informe de la descripción general de todos los superclusters y subclusters.
* Archivo XXXXX.rmd: código en formato R markdown del análisis de comparación entre ratones WT y IgA-KO.
* Archivo XXXXX.html: informe del análisis de comparación entre ratones WT y IgA-KO.

Subcarpeta "Datos":
  
* Archivo XXXX.rds: objeto Seurat con el atlas completo, integrado y anotado de las diferentes poblaciones y subpoblaciones celulares. Contiene también los metadatos correspondientes a la identificación de muesrta (Sample_id), la cepa de ratones (Strain), los superclusters (Clusters_main_def) y los subclusters (Clusters_subclusters_def).
* Archivo XXXX.rds: objeto Seurat con el atlas integrado y anotado del supercluster de células B. Contiene los mismos metadatos que el atlas completo.
* Archivo XXXX.rds: objeto Seurat con el atlas integrado y anotado del supercluster de células T, ILC y NK. Contiene los mismos metadatos que el atlas completo.
* Archivo XXXX.rds: objeto Seurat con el atlas integrado y anotado del supercluster de células mieloides. Contiene los mismos metadatos que el atlas completo.
* Archivo cellmarkers.xlsx: archivo excel con los marcadores de poblaciones celulares usados para comprobar la anotación de los clusters.

Subcarpeta "Resultados":
  
* Archivo XXXX.xlsx: archivo excel con los marcadores significativos correspondientes a cada subcluster.
* Archivo XXXX.xlsx: archivo excel con los resultados del análisis de sobrerrepresentación (ORA) de términos de Gene Ontology de cada subcluster.
* Archivo XXXX.xlsx: archivo excel con los genes diferencialmente expresados en cada subcluster (comparación IgAKO - WT).
* Archivo XXXX.xlsx: archivo excel con los resultados del Gene Set Enrichment Analysis (GSEA) de términos de Gene Ontology de los genes diferencialmente expresados en cada subcluster (comparación IgAKO - WT).

  
