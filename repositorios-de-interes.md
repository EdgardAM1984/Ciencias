# Repositorios de interés

Lista de repositorios de GitHub revisados el 12 de octubre de 2026, con una descripción breve de cada uno y su posible utilidad para proyectos de insumos biológicos, biodiversidad y agricultura. La descripción se basa en el README y la estructura de cada repositorio; no se ejecutó ni probó el código.

## Resumen

| # | Repositorio | Tipo | Qué es | Utilidad para el trabajo | Observaciones |
|---|-------------|------|--------|--------------------------|---------------|
| 1 | [AGROSAVIA-EXTERNOS/AgRSCol](https://github.com/AGROSAVIA-EXTERNOS/AgRSCol) | Código y ejemplos | Piloto de AGROSAVIA (Colombia) para agrupar de forma no supervisada los píxeles de imágenes satelitales multiespectrales y caracterizar suelos agrícolas. Zona de ejemplo: centro de investigación Tibaitatá. | Ejemplo sencillo de cómo obtener imágenes Landsat y Sentinel de un predio y agruparlas por características espectrales. Útil para estudios de suelo y uso de la tierra. | Los métodos son generales, pero los datos de ejemplo son de Colombia. Incluye cuadernos Jupyter de documentación. |
| 2 | [microsoft/farmvibes-ai](https://github.com/microsoft/farmvibes-ai) | Plataforma | Marco para construir modelos de aprendizaje automático que fusionan datos geoespaciales (satélite, radar, dron, clima, elevación) para agricultura y sostenibilidad. | Flujos de trabajo y cuadernos de ejemplo (cultivos, prácticas agrícolas, huella de carbono, microclima, bosques). Referencia para propuestas con teledetección. | Varios conjuntos de datos y ejemplos están orientados a Estados Unidos. Su uso completo requiere infraestructura (clúster). |
| 3 | [brycejohnston/awesome-agriculture](https://github.com/brycejohnston/awesome-agriculture) | Lista de recursos | Lista curada de herramientas y datos abiertos para agricultura: robótica, clima, modelado de cultivos, conjuntos de datos, SIG, IoT, aprendizaje automático y teledetección. | Punto de partida para encontrar fuentes de datos y herramientas que respalden propuestas Corfo y FIA. | Es una lista general; muchas fuentes son de Estados Unidos y hay que filtrar las útiles para Chile. |
| 4 | [farmOS/farmOS](https://github.com/farmOS/farmOS) | Aplicación web | Plataforma abierta (Drupal, licencia GPL 2.0) para gestión agrícola, planificación y registros: activos, bitácoras, inventario, ubicaciones, mapas, importación y exportación de datos. | Referencia para estructurar trazabilidad por lote o predio y el registro de muestreos. Ejemplo de plataforma abierta para citar en propuestas. | Pensada para operar una explotación agrícola, no para análisis científico. Se puede instalar con Docker. |
| 5 | [trimstray/the-book-of-secret-knowledge](https://github.com/trimstray/the-book-of-secret-knowledge) | Lista de recursos | Colección grande de manuales, hojas de referencia, comandos de una línea y herramientas de terminal, redes y seguridad. | Apoyo general si se trabaja con servidores, terminal de Linux o automatización. | No tiene contenido de agricultura ni biología. |
| 6 | [sindresorhus/awesome](https://github.com/sindresorhus/awesome) | Índice de listas | Índice principal de las listas "awesome" de GitHub, organizado por temas. | Sirve para descubrir más repositorios de interés (ver la sección siguiente). | Es solo un índice de enlaces. |

## Enlaces útiles encontrados en el índice "awesome"

Listas temáticas del índice de `sindresorhus/awesome` que pueden ser relevantes, según el título y la descripción que aparecen allí:

| Tema | Lista | Descripción en el índice |
|------|-------|--------------------------|
| Agricultura | [awesome-agriculture](https://github.com/brycejohnston/awesome-agriculture) | Tecnología de código abierto para agricultura y jardinería |
| Bioinformática | [Awesome-Bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics) | Recursos de bioinformática |
| Visualización biológica | [awesome-biological-visualizations](https://github.com/keller-mark/awesome-biological-visualizations) | Visualización interactiva de datos biológicos en la web |
| Fenotipos biológicos | [awesome-cytodata](https://github.com/cytodata/awesome-cytodata) | Perfilado de fenotipos biológicos a partir de imágenes |
| Ciencia ciudadana | [citizen-science](https://github.com/dylanrees/citizen-science) | Para científicos comunitarios y no institucionales |
| SIG en la web | [awesome-frontend-gis](https://github.com/joewdavies/awesome-frontend-gis) | Sistemas de información geográfica para navegadores |
| GeoJSON | [awesome-geojson](https://github.com/tmcw/awesome-geojson) | Recursos sobre GeoJSON |
| Tierra y clima | [awesome-earth](https://github.com/philsturgeon/awesome-earth) | Recursos para enfrentar la crisis climática |
| Ciencia de datos | [awesome-datascience](https://github.com/academic/awesome-datascience) | Ciencia de datos y aprendizaje automático |
## Repositorios agregados (24 de octubre de 2026)

Seleccionados para cubrir lo que faltaba en la lista: análisis de microbioma de suelo (para validar bioinsumos), biodiversidad predial y corredores, y balance hídrico (para BioMulch). Se revisó el README de cada uno y la fecha de su último commit; no se ejecutó ni probó el código.

| # | Repositorio | Tipo | Qué es | Utilidad para el trabajo | Observaciones |
|---|-------------|------|--------|--------------------------|---------------|
| 7 | [benjjneb/dada2](https://github.com/benjjneb/dada2) | Paquete R (Bioconductor) | Inferencia exacta de variantes (ASV) desde secuenciación de amplicones 16S/ITS. | Procesar las lecturas de muestras de suelo y rizósfera antes y después de aplicar un bioinsumo; verificar si la cepa inoculada se establece. | Estándar en la literatura. Último commit: julio de 2026. |
| 8 | [qiime2/qiime2](https://github.com/qiime2/qiime2) | Plataforma | Marco para análisis de microbioma por amplicones (QIIME 2, ahora llamado "rachis"). | Flujo completo: calidad, taxonomía, diversidad alfa y beta, gráficos. Alternativa en Python/línea de comandos a dada2 + phyloseq. | El proyecto está migrando su nombre y sitio a rachis.org. |
| 9 | [joey711/phyloseq](https://github.com/joey711/phyloseq) | Paquete R | Manejo, análisis y gráficos de datos de comunidades microbianas (tablas de ASV, taxonomía, metadatos). | Comparar tratamientos de ensayos de campo (testigo vs. bioinsumo) con gráficos listos para informes y propuestas. | Actualizaciones poco frecuentes (último commit: febrero de 2026), pero muy usado. |
| 10 | [picrust/picrust2](https://github.com/picrust/picrust2) | Herramienta | Predice funciones metabólicas de una comunidad a partir de datos 16S. | Estimar cambios en funciones del suelo (ciclo de N, P, etc.) sin pagar metagenómica completa. | Es una predicción, no una medición; conviene validarla con ensayos enzimáticos. |
| 11 | [UMNFuN/FUNGuild](https://github.com/UMNFuN/FUNGuild) | Script y base de datos | Asigna gremios ecológicos a hongos (patógenos, saprótrofos, micorrícicos) desde tablas de taxonomía. | Seguir la proporción de hongos patógenos vs. benéficos en ensayos con Trichoderma o en evaluaciones de salud de suelo. | Sin actualizaciones desde diciembre de 2023. |
| 12 | [vegandevs/vegan](https://github.com/vegandevs/vegan) | Paquete R | Índices de diversidad, ordenación (NMDS, PCA, RDA) y pruebas estadísticas (PERMANOVA) para ecología de comunidades. | Evaluaciones de biodiversidad predial (flora, artrópodos, aves) y comparación de corredores biológicos vs. zonas sin intervención. | Muy activo (último commit: octubre de 2026). |
| 13 | [scikit-bio/scikit-bio](https://github.com/scikit-bio/scikit-bio) | Paquete Python | Estructuras de datos y algoritmos de bioinformática, incluidos índices de diversidad y distancias. | Equivalente en Python a parte de vegan, útil para automatizar informes de biodiversidad. | Licencia BSD. Muy activo. |
| 14 | [pyinat/pyinaturalist](https://github.com/pyinat/pyinaturalist) | Paquete Python | Cliente de la API de iNaturalist. | Descargar observaciones de especies nativas cerca de un predio para armar listas de especies esperadas y elegir flora para corredores. | Los datos de ciencia ciudadana tienen sesgos de muestreo (caminos, ciudades). |
| 15 | [gbif/pygbif](https://github.com/gbif/pygbif) | Paquete Python | Cliente de la API de GBIF (registros de ocurrencia de especies). | Complementa iNaturalist con datos de herbarios, museos e inventarios; útil para respaldar la línea base de biodiversidad en propuestas. | Equivalente en R: [ropensci/rgbif](https://github.com/ropensci/rgbif). |
| 16 | [gee-community/geemap](https://github.com/gee-community/geemap) | Paquete Python | Análisis y visualización interactiva con Google Earth Engine. | Series de tiempo de NDVI/humedad por predio para monitorear corredores, daño por lluvias o efecto de BioMulch a escala de campo; más liviano que farmvibes-ai. | Requiere una cuenta de Google Earth Engine (gratuita para uso no comercial y de investigación). |
| 17 | [aquacropos/aquacrop](https://github.com/aquacropos/aquacrop) | Paquete Python | Versión en Python del modelo suelo-cultivo-agua AquaCrop (FAO). | Simular cuánta agua de riego ahorraría BioMulch al cambiar la retención de agua del suelo, antes de pilotear en campo. | Requiere calibrar suelo y cultivo con datos locales. |


## Pendiente

- Agregar los demás repositorios guardados como favoritos en GitHub.
- Evaluar qué fuentes de datos de estos repositorios tienen cobertura en Chile.
- Probar dada2 + phyloseq + FUNGuild con un set de muestras real de un ensayo de bioinsumo.
- Calibrar AquaCrop para un cultivo y suelo objetivo de BioMulch.
