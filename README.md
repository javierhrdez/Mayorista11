# Sistema de reomedacion Mayorista11

## Problema 

Mayorista11, la distribuidora de productos líder en el mercado, busca optimizar sus recomendaciones de productos a comercios locales. El objetivo es impulsar las ventas sugiriendo productos que un comercio aún no ha comprado, pero que son populares entre comercios similares en su área geográfica (comuna, district en inglés).

## Descripción solución:

- data/transactions.csv:  Historial de transacciones: Contiene información sobre las compras realizadas por cada comercio, incluyendo el ID del comercio, el ID del producto y la cantidad comprada. Archivo transactions.csv.
- data/commerces.csv: Incluye el ID del comercio y su comuna. 
- data/products.csv Información de productos: Puede incluir detalles como categoría, marca, precio, etc. Ar

- MAYORISTAS11.ipynb : Jupyter notebook implementado solución
- Reporte.docx : Reporte con resultados y conclusiones en formato Word.
- Reporte.pdf : Reporte con resultados y conclusiones en formato PDF

- recomedaciones_colaborativas.xlsx : Output con recomendaciones de modelo colaborativo de Vecinos Cercanos.
- recomedaciones_pagerank.xlsx : Output con recomendaciones de modelos PageRank.

## Ejecución :

Todo el código necesario para correr el recomendados está contenido en el Jupyter Notebook MAYORISTAS11.ipynb . La ejecución de este notebook generará recomedaciones_colaborativas.xlsx y recomedaciones_pagerank.xlsx


