# Caso Práctico - Provident

Se realizó un análisis exploratorio de los datos de ventas, el cual reveló que los productos y las regiones presentan comportamientos diferenciados. Estos hallazgos sugieren patrones de demanda y tendencias particulares que pueden influir en la planificación comercial y la toma de decisiones estratégicas.

<img src="imagenes/tendencia_global.png" alt="Tendencia Global" width="600">

## Regiones
La región Norte muestra el mayor volumen de ventas históricas.

<img src="imagenes/Ventas_Region.png" alt="Ventas por Región" width="500">
<img src="imagenes/Boxplots_Region.png" alt="Boxplot por Región" width="500">

## Productos
El producto A presenta un comportamiento más estable al revisar su distribución.

<img src="imagenes/Ventas_Productos.png" alt="Ventas por Producto" width="500">
<img src="imagenes/Boxplot_Productos.png" alt="Boxplot por Producto" width="500">

Durante el análisis exploratorio se identificaron diferencias significativas en el comportamiento de ventas según el producto y la región. Esto indica que las dinámicas de consumo no son homogéneas y que cada combinación producto-región podría requerir estrategias específicas de pronóstico y gestión.

El análisis de las series históricas muestra que productos y regiones presentan variaciones y tendencias distintas. Esto sugiere la necesidad de abordar cada segmento con modelos de pronóstico diferenciados, considerando factores locales en la planificación de ventas.

<img src="imagenes/PronosticoGlobalEstimacion.png" alt="Pronóstico Global" width="600">

Tras evaluar diferentes alternativas de modelado, se consideró que el modelo de **Holt-Winters** era el más adecuado para nuestro caso. Este modelo permite capturar tanto la tendencia como la estacionalidad de las series, ofreciendo pronósticos más consistentes y suavizados. Aunque se exploraron otros enfoques, las características de las series—como la variabilidad por producto y región y la presencia de patrones estacionales—hicieron que Holt-Winters proporcionara resultados más interpretables y confiables para la planificación de ventas.

Se observa que el pronóstico sigue la tendencia típica de disminución en enero y febrero, como ocurre cada año.

---

**Notebook de trabajo**  
Todo el análisis, los gráficos y los comentarios se encuentran en el notebook: [`CuadernoTrabajoCasoPractico.ipynb`](CuadernoTrabajoCasoPractico.ipynb)