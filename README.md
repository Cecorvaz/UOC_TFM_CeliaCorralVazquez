# UOC_TFM_CeliaCorralVazquez
Repositorio de códigos utilizados para la elaboración del Trabajo de Fin de Máster (TFM) realizado por Celia Corral-Vázquez para el máster de Bioinformática y Bioestadística de la UOC.

Aquí se encuentran los scripts (formato Rmarkdown) utilizados para el análisis de los datos single-cell RNA-seq provenientes de células mononucleares CD45+ de lámina propia de intestino delgado de ratón. Se intergaron y analizaron seis muestras provenientes de dos cepas de ratones:

* Ratones C57BL/6 wildtype (N = 3)
* Ratones C57BL/6 IgA-KO (N = 3)

En total, este repositorio contiene la siguiente información:

Carpeta principal:

* Archivo 1_QQ.Rmd: código en formato R markdown del análisis inicial de controles de calidad, filtrado y las pruebas de integración de las muestras.
* Archivo 1_QQ.html: informe del análisis inicial de controles de calidad, filtrado y las pruebas de integración de las muestras.
* Archivo 2_Clustering.rmd: código en formato R markdown del análisis de clustering y anotación de los clusters y subclusters.
* Archivo 2_Clustering.html: informe del análisis de clustering y anotación de los clusters y subclusters.
* Archivo 3_Atlas_description.rmd: código en formato R markdown de la descripción general de todos los superclusters y subclusters.
* Archivo 3_Atlas_description.html: informe de la descripción general de todos los superclusters y subclusters.
* Archivo 4_StrainComp_IgAKO_vs_WT.rmd: código en formato R markdown del análisis de comparación entre ratones WT y IgA-KO.
* Archivo 4_StrainComp_IgAKO_vs_WT.html: informe del análisis de comparación entre ratones WT y IgA-KO.

Subcarpeta "Datos":
  
* Archivo WT_IgAKO_anotado.rds: objeto Seurat con el atlas completo, integrado y anotado de las diferentes poblaciones y subpoblaciones celulares. Contiene también los metadatos correspondientes a la identificación de muesrta (Sample_id), la cepa de ratones (Strain), los superclusters (Clusters_main_def) y los subclusters (Clusters_subclusters_def).
* Archivo WT_IgAKO_bcells.rds: objeto Seurat con el atlas integrado y anotado del supercluster de células B. Contiene los mismos metadatos que el atlas completo.
* Archivo WT_IgAKO_tcells.rds: objeto Seurat con el atlas integrado y anotado del supercluster de células T, ILC y NK. Contiene los mismos metadatos que el atlas completo.
* Archivo WT_IgAKO_mycells.rds: objeto Seurat con el atlas integrado y anotado del supercluster de células mieloides. Contiene los mismos metadatos que el atlas completo.
* Archivo cellmarkers.xlsx: archivo excel con los marcadores de poblaciones celulares usados para comprobar la anotación de los clusters.

Subcarpeta "Resultados":
  
* Archivo Markers_of_clusters.xlsx: Tabla Suplementaria 1. Archivo excel con los marcadores significativos correspondientes a cada subcluster.
* Archivo DE_genes_WT_IgAKO.xlsx: Tabla Suplementaria 2. Archivo excel con los genes diferencialmente expresados en cada subcluster (comparación IgAKO - WT).
* Archivo GSEA_GO_IgAKO_WT_bcells.xlsx: Tabla Suplementaria 3. Archivo excel con los resultados del Gene Set Enrichment Analysis (GSEA) de términos de Gene Ontology de los genes diferencialmente expresados en los subclusters de células B (comparación IgAKO - WT).
* Archivo GSEA_GO_IgAKO_WT_tcells.xlsx: Tabla Suplementaria 4. Archivo excel con los resultados del Gene Set Enrichment Analysis (GSEA) de términos de Gene Ontology de los genes diferencialmente expresados en los subclusters de células T (comparación IgAKO - WT).
* Archivo GSEA_GO_IgAKO_WT_mycells.xlsx: Tabla Suplementaria 5. Archivo excel con los resultados del Gene Set Enrichment Analysis (GSEA) de términos de Gene Ontology de los genes diferencialmente expresados en los subclusters de células mieloides (comparación IgAKO - WT).

  
