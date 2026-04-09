# vestrada_data.github.io

# Acerca de mí 

Apasionada por transformar datos crudos en decisiones estratégicas. Mi enfoque combina la ingeniería de sistemas con el análisis exploratorio de datos (EDA) para optimizar procesos operativos.

***Habilidades tecnológicas***<br>
Análisis y gestión de datos utilizando Excel / SQL / Python <br>
Visualización de datos y narración de historias usando Google Shehet / Excel 

***Habilidades blandas***<br>
⦿ Análisis de datos <br>
⦿ Resolución de problemas <br>
⦿ Comunicación con stakeholders <br>
⦿ Trabajo en equipo <br>
⦿ Orientación a resultados <br>
⦿ Organización <br>
⦿ Atención al detalle <br>
⦿ Optimización de Procesos<br>

# Proyectos seleccionados

## 1️⃣  Análisis de Movilidad vs. Desarrollo Económico (PIB)
Este proyecto analiza la relación entre el Producto Interno Bruto (PIB) y los indicadores de movilidad, específicamente el retraso en minutos, para identificar cómo el desarrollo económico impacta, o se ve impactado por la eficiencia en el transporte.
<p align="center">
<img width="393" height="288" alt="banner_proyecto" src="https://github.com/user-attachments/assets/82fbcbe7-f648-42c0-8f29-c818c92f3a0b" /p>

### Herramientas Utilizadas
![Python](https://img.shields.io/badge/PYTHON-00599C?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/PANDAS-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NUMPY-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/MATPLOTLIB-11557C?style=for-the-badge&logo=python&logoColor=white)

### Metodología
Cruzar datos de tráfico con indicadores económicos de la OECD usando Python y Pandas.

### Hallazgos Principales 
<p align="center">
  Gráfico: Distribución de retrasos en movilidad (Minutos)
<img width="546" height="217" alt="grafica" src="https://github.com/user-attachments/assets/f2d05b4c-9d80-4775-b030-52449c2e18ae" />
</p>
No se encontro relación directa entre el PIB per cápita y la congestión vehicular. 
<p align="center">
 Gráfico: Distribución de retrasos en movilidad (Minutos)<br>
 <img width="320" height="276" alt="boxplot" src="https://github.com/user-attachments/assets/4bcd6f40-0a1b-4710-9228-623cb1988225" />
</p> 
Existen ciudades con alto PIB y alta congestión vehicular, así como ciudades con menor PIB pero distintos niveles de tráfico. 
<p align="center">
 <img width="550" height="357" alt="Histograma" src="https://github.com/user-attachments/assets/93f24446-151c-4ef1-af32-038bce214e13" />
</p>
Destacan ciudades como Lima y Ciudad de México, donde hay altos niveles de congestión vehicular pero un PIB per cápita que no es de los más altos, lo que sugiere que la congestión no depende únicamente del nivel económico, sino de factores como infraestructura, planeación urbana y transporte público. 

### Resultado
Identifiqué la correlación directa entre el retraso por congestión y la caída en el desempeño económico urbano.

Explora más detalles del proyecto en [Notebook](https://github.com/vestrada-data/data-analytics/blob/main/mobility_economy_project.ipynb)

2️⃣Análisis de embudo y retención para e-commerce
Análisis de datos de órdenes, productos y marketing para evaluar la rentabilidad y desempeño financiero por país.
Este análisis permite identificar puntos de abandono dentro del embudo de conversión y detectar oportunidades para mejorar la experiencia de compra y optimizar la tasa de conversión.

##  Herramientas Utilizadas
![SQL](https://img.shields.io/badge/SQL-00758F?style=for-the-badge&logo=postgresql&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)


### •	Habilidades tecnológicas
SQL (JOINs, limpieza y transformación de datos)
Excel / Google Sheets, KPIs financieros
Análisis de datos
Data Cleaning
Análisis de KPIs
Data Visualization
Data Storytelling   

### Metodología
1. Construir embudos multietapa en SQL usando CTEs.
2. Calcular tasas de conversión entre pasos y detectar caídas.
3. Analizar la retención de usuarios por cohortes.
4. Simular mejoras en conversión o retención.
5. Validar resultados y comunicar hallazgos ejecutivos.
   
### Hallazgos Principales 
<p align="center">
<img width="579" height="309" alt="tasa_conversion" src="https://github.com/user-attachments/assets/0ac9c289-d943-4296-9b46-2543faee490e" />
<p/>
La conversión total del funnel es de 1.25%, lo que indica que solo 1 de cada 100 usuarios completa una compra.<br>
La mayor caída ocurre en la parte alta del funnel:<br>
Solo el 11.0% de los usuarios que visualizan un producto lo agregan al carrito.<br>
A partir del carrito, el funnel muestra una disminución progresiva y sostenida:<br>
4.0% inicia checkout<br>
2.4% agrega información de envío<br>
2.05% llega a pago<br>
1.25% finaliza la compra<br>
<p align="center">
<img width="783" height="330" alt="tasa_por_pais" src="https://github.com/user-attachments/assets/b046921f-fb06-4925-adb0-850224bc089d" />
  <p/>
En todos los mercados, la etapa select_item presenta tasas cercanas o superiores al 75%, sin embargo las diferencias y la  disminución en el avance hacia etapas finales del proceso de compra,  podrían reflejar factores como preferencias de pago, logística, precios o experiencia del usuario en cada mercado.  Se sugiere revisar especificamente situación en Paraguay ya que no se completa  el  proceso de compra.
<p align="center">
<img width="449" height="223" alt="tasa_retencion" src="https://github.com/user-attachments/assets/b490589c-e637-4315-90d7-b312da8bd421" />
<p/>
Las cohortes muestran una retención D7 entre  80–85%, sobresaliento 2025-03.  Esto sugiere un alto nivel de interés inicial, pero la retención disminuye progresivamente hasta valor más bajo de 0.2% en 2025-08 D28. Se sugiere utilizar estrategias con un enfoque localizado, considerando factores específicos de cada mercado como métodos de pago, costos de envío o preferencias de compra.
<p align="center">
<img width="442" height="244" alt="tasa_retencion2" src="https://github.com/user-attachments/assets/e8c1b3e7-724c-4842-9934-7f676ee0c207" />
<p/>
Los resultados indican que las principales oportunidades de optimización se encuentran en reducir la fricción entre la vista del producto y la decisión de compra, así como en implementar estrategias que aumenten la  recurrencia de usuarios después de la primera interacción.  Asi como evaluar categoría del producto, dispositivo y tiempo de navegación para identificar los factores que influyen en el abandono en esta etapa.

  
Con los calculos de KPIs clave (ingresos, utilidad, margen y ROI), identifiqué a EE. UU. como el mercado principal, concentrando el 34.7% de las ganancias. 


