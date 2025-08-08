<img src="https://www.aluracursos.com/assets/img/challenges/share-images/oracle.1750260032.png" alt="Oracle Challenge" width="720" />


# 📊 Análisis de Tiendas - Alura Store 
## Descripción del Proyecto

Este proyecto realiza un análisis de datos exhaustivo de las cuatro sucursales de la cadena "Alura Store" para ayudar a su propietario, el Sr. Juan, a tomar una decisión estratégica: identificar la tienda menos eficiente que podría venderse para financiar un nuevo emprendimiento. El análisis se basa en métricas clave como ingresos, ventas por categoría, reseñas de clientes y rendimiento logístico.

---

## 🔍 Objetivo del Proyecto

Ayudar al Sr. Juan a tomar una decisión informada sobre qué tienda de su cadena vender. Esto se logra a través de un análisis comparativo que considera los siguientes factores clave:
* Ingresos totales por tienda.
* Ventas por categoría de producto.
* Calificaciones promedio y satisfacción de los clientes.
* Rendimiento de productos individuales (más y menos vendidos).
* Costos de envío promedio.
* Patrones geográficos de ventas.
---

## Metodología

El análisis se estructuró en los siguientes pasos utilizando un Jupyter Notebook (`AluraStoreLatam.ipynb`) y las bibliotecas de Python para la ciencia de datos. Los pasos principales fueron:

1.  **Carga y Consolidación de Datos:** Se cargaron los datos de ventas de cuatro archivos `.csv` distintos, cada uno correspondiente a una tienda. Se consolidaron en un único DataFrame de `pandas` para facilitar el análisis comparativo.

2.  **Análisis de Ingresos:** Se calcularon los ingresos totales por tienda, identificando a la **Tienda 1** como la de mayor facturación y a la **Tienda 4** como la de menor, con una diferencia significativa respecto a las demás.

3.  **Ventas por Categoría:** Se analizó el volumen de ventas en cada categoría de producto. Se observó que "Muebles" y "Electrónicos" son las categorías más fuertes en todas las tiendas. Notablemente, la Tienda 4 mostró el rendimiento más bajo en la categoría de "Electrodomésticos".

4.  **Calificaciones de Clientes:** Se evaluó la satisfacción del cliente calculando la calificación promedio por tienda. Las **Tiendas 2 y 3** emergieron como las líderes en satisfacción, mientras que la Tienda 4 se ubicó entre las más bajas.

5.  **Costos de Envío:** Se analizó el costo de envío promedio. La Tienda 4 presentó el costo más bajo, una ventaja competitiva que, sin embargo, no se tradujo en un mayor volumen de ventas o ingresos.

6.  **Análisis Geográfico (Extra):** Utilizando las coordenadas de las compras, se realizó un análisis geográfico con `folium` y `matplotlib`. Se descubrió que las ventas de **todas las tiendas** se concentran fuertemente en grandes centros urbanos como Bogotá y Medellín. Este hallazgo fue crucial para determinar que el bajo rendimiento de la Tienda 4 no se debe a una mala ubicación, sino a una ineficiencia operativa interna.


## 🛠️ Herramientas Utilizadas

* **Lenguaje de Programación:** [Python](https://www.python.org/)
* **Bibliotecas:**
    * **[Pandas](https://pandas.pydata.org/):** Para la manipulación y análisis de datos.
    * **[Matplotlib](https://matplotlib.org/) y [Seaborn](https://seaborn.pydata.org/):** Para la creación de visualizaciones estáticas (barras, pasteles, dispersión).
    * **[Folium](https://python-visualization.github.io/folium/):** Para la generación de mapas geográficos interactivos (mapas de calor).
* **Entorno:** [Jupyter Notebook](https://jupyter.org/) y [Google Colab](https://colab.google/)
* **Control de versiones:** [GitHub](https://github.com/)
---

## 📈 Gráficos generados

Durante el análisis se incluyeron **visualizaciones clave**, como:

<table>
  <tr>
    <td width="50%" valign="top">
      <ul>
        <li>Barras de ingresos por tienda</li>
        <li>Línea de comparación de ingresos</li>
        <li>Barras apiladas de ventas por categoría</li>
        <li>Circular de distribución de categorías</li>
        <li>Barras de calificación promedio con línea de promedio global</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <ul>
        <li>Barras horizontales de productos más y menos vendidos</li>
        <li>Barras de costo promedio de envío</li>
        <li>Mapa de calor geográfico de ventas (Folium)</li>
        <li>Dispersión de ventas vs ubicación</li>
      </ul>
    </td>
  </tr>
</table>

<table style="width:100%; border:0;">
  <tr>
    <td style="width:33%; text-align:center;">
      <img src="https://github.com/user-attachments/assets/7caa811c-3b80-47a3-a06a-5c819ededb29" alt="Gráfico 1" style="max-width:100%;">
    </td>
    <td style="width:33%; text-align:center;">
      <img src="https://github.com/user-attachments/assets/3ed08809-b76b-4aa0-9afc-bc851571021a" alt="Gráfico 2" style="max-width:100%;">
    </td>
    <td style="width:33%; text-align:center;">
      <img src="https://github.com/user-attachments/assets/f518d76a-1f2a-4d65-a059-44c97260ec0f" alt="Gráfico 3" style="max-width:100%;">
    </td>
  </tr>
</table>


---

## ✅ Conclusión y Recomendación Final

Tras evaluar todos los indicadores de rendimiento, el análisis concluye con una recomendación clara:

**Recomendación: Vender la Tienda 4.**


### Justificación:

La decisión se fundamenta en la unión de múltiples factores que lo evidencian como la Tienda con el rendimiento más bajo y el menor potencial:

1.  **Bajos Ingresos y Rendimiento Financiero:** Es la tienda con los ingresos más bajos de la cadena, generando una brecha significativa que la posiciona como el eslabón financiero más débil.
2.  **Puntos Débiles:** Se observa una baja calificación de clientes y un desempeño débil en categorías clave como "Electrodomésticos", lo que refuerza la conclusión de que es la operación menos eficiente del grupo.
3.  **(Extra) Ineficiencia Operativa:** A pesar de tener acceso a los mismos mercados que las otras sucursales, su incapacidad para capitalizarlos demuestra un problema de rendimiento interno y no de localización.

La venta de la Tienda 4 representa la decisión estratégica más lógica para liberar capital y reinvertirlo en un proyecto con mayor potencial de crecimiento, mientras se conservan las sucursales más estables y rentables.

---

## Cómo Utilizar este Repositorio

1.  Clonar el repositorio en tu máquina local.
2.  Asegúrate de tener Python y las bibliotecas mencionadas (`pandas`, `matplotlib`, `seaborn`, `folium`) instaladas en tu entorno.
3.  Abre y ejecuta el archivo `AluraStoreLatam.ipynb` en un entorno de Jupyter Notebook para replicar el análisis completo. **Este archivo contiene el código, el análisis completo, los gráficos y el informe final del proyecto.**
   


❗ **Asegúrese de leer esto.**
> 💡 **Recordatorio:** El archivo `AluraStoreLatam.ipynb` no es solo un script; es el informe final interactivo que contiene toda la documentación y las conclusiones detalladas. Este README solo contiene un resumen ejecutivo.

<img width="720" height="350" alt="image" src="https://github.com/user-attachments/assets/0aa439b3-ef24-433e-8fa0-e62afd84ba06" />  

<img width="720" height="350" alt="image" src="https://github.com/user-attachments/assets/84b1126d-3008-4842-9e31-93b4fc19c184" />

---

## ✍️ Autor

- Desarrollado por: [Aaron Garcia]
- Contacto: [www.linkedin.com/in/aaron-martinez-garcia]

---

