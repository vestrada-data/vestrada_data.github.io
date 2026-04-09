
![BannerLK](https://github.com/user-attachments/assets/958cf942-028d-4085-b80b-77ec408a2289)

# Acerca de mí  
 
Apasionada por transformar datos crudos en decisiones estratégicas. Mi enfoque combina la ingeniería de sistemas con el análisis exploratorio de datos (EDA) para optimizar procesos operativos.

***Habilidades tecnológicas*** <br>
- Análisis y gestión de datos utilizando Excel / SQL / Python <br>
- Visualización de datos y narración de historias usando Google Sheets / Excel 

***Habilidades blandas*** <br>
- Pensamiento analítico| Resolución de problemas| Comunicación con stakeholders | Trabajo colaborativo | Orientación a resultados | 
- Organización | Atención al detalle | Optimización de Procesos<br>

# Proyectos seleccionados

## 1. Análisis de Movilidad vs. Desarrollo Económico (PIB)
Este proyecto analiza la relación entre el Producto Interno Bruto (PIB) y los indicadores de movilidad, específicamente el retraso en minutos, para identificar cómo el desarrollo económico impacta, o se ve impactado por la eficiencia en el transporte.

###  Herramientas Utilizadas
![Python](https://img.shields.io/badge/PYTHON-00599C?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/PANDAS-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NUMPY-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/MATPLOTLIB-11557C?style=for-the-badge&logo=python&logoColor=white)

### Metodología
 Cruzar datos de tráfico con indicadores económicos de la OECD usando Python y Pandas.

### Hallazgos Principales 
<br>
<p align="center">
 Gráfico: Distribución de retrasos en movilidad (Minutos)<br>
 <img width="420" height="376" alt="boxplot" src="https://github.com/user-attachments/assets/4bcd6f40-0a1b-4710-9228-623cb1988225" />
</p> 
Existe un valor atípico (outlier) extremo que supera los 2500 minutos.Esto sugiere que, aunque la mayoría de las ciudades tienen retrasos moderados, algunas experimentan crisis de movilidad críticas que disparan el promedio general.<br>

<br>
<p align="center">
<img width="646" height="317" alt="grafica" src="https://github.com/user-attachments/assets/f2d05b4c-9d80-4775-b030-52449c2e18ae" />
</p>
La mayoría de las ciudades se concentran en un rango de PIB de entre 8,000 y 15,000 USD.Existen ciudades con alto PIB y alta congestión vehicular, así como ciudades con menor PIB pero distintos niveles de tráfico. <br>
<br>
<p align="center">
 <img width="550" height="357" alt="Histograma" src="https://github.com/user-attachments/assets/93f24446-151c-4ef1-af32-038bce214e13" />
</p>
La gráfica revela que no hay una  relación directa entre el PIB per cápita y la congestión vehicular. Un PIB alto no garantiza necesariamente una movilidad eficiente ni genera siempre caos vial. Destacan ciudades como Lima y Ciudad de México, donde hay altos niveles de congestión vehicular pero un PIB per cápita que no es de los más altos, lo que sugiere que la congestión no depende únicamente del nivel económico, sino de factores como infraestructura, planeación urbana y transporte público. <br>
 <br>

[![Proyecto](https://img.shields.io/badge/PROYECTO COMPLETO-VER_AQUÍ-blue?style=for-the-badge)]([[https://tu-link-aqui.com](https://github.com/vestrada-data/data-analytics/blob/main/mobility_economy_project.ipynb)] 


## 2. Análisis de embudo y retención para e-commerce
Análisis de datos de órdenes, productos y marketing para evaluar la rentabilidad y desempeño financiero por país.<br>
Este análisis permite identificar puntos de abandono dentro del embudo de conversión y detectar oportunidades para mejorar la experiencia de compra y optimizar la tasa de conversión.

## ⦿ Herramientas Utilizadas
![SQL](https://img.shields.io/badge/SQL-00758F?style=for-the-badge&logo=postgresql&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-34A853?style=for-the-badge&logo=google-sheets&logoColor=white)

### ⦿ Habilidades tecnológicas
SQL (JOINs, limpieza y transformación de datos)
KPIs financieros
Análisis de datos
Data Cleaning
Análisis de KPIs
Data Visualization
Data Storytelling   

### ⦿ Metodología
1. Construir embudos multietapa en SQL usando CTEs.
2. Calcular tasas de conversión entre pasos y detectar caídas.
3. Analizar la retención de usuarios por cohortes.
4. Simular mejoras en conversión o retención.
5. Validar resultados y comunicar hallazgos ejecutivos.
   
### ⦿ Hallazgos Principales 
<p align="center">
<img width="821" height="350" alt="tasa_conversion" src="https://github.com/user-attachments/assets/b1e37b28-f810-40fe-a573-95c7aff7517b" />
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
<img width="832" height="385" alt="tasa_por_pais" src="https://github.com/user-attachments/assets/d1140a74-2899-45c3-8479-95b715aa6cf9" />
  <p/>
En todos los mercados, la etapa select_item presenta tasas cercanas o superiores al 75%, sin embargo las diferencias y la  disminución en el avance hacia etapas finales del proceso de compra,  podrían reflejar factores como preferencias de pago, logística, precios o experiencia del usuario en cada mercado.  Hay variaciones entre mercados, con Uruguay como mejor desempeño y Paraguay sin compras.
<p align="center">
<img width="763" height="338" alt="tasa_retencion" src="https://github.com/user-attachments/assets/8fcdaa0e-89c5-4743-a1ef-24b218f500c6" />
<p/>
Las cohortes muestran una retención D7 entre  80–85%, sobresaliendo 2025-03.  Esto sugiere un alto nivel de interés inicial,  pero con caída significativa ( <4%) hacia D28(2025-08). Se sugiere utilizar estrategias con un enfoque localizado, considerando factores específicos de cada mercado como métodos de pago, costos de envío o preferencias de compra.
<p align="center">
<img width="758" height="409" alt="tasa_retencion2" src="https://github.com/user-attachments/assets/b816a35a-9f13-42c1-816a-b73fd2ce73db" />
<p/>
Identifiqué estabilidad en retención hasta julio, con una caída atípica en agosto, sugiriendo posibles cambios recientes en producto, adquisición o calidad de usuarios.

Los resultados indican que las principales oportunidades de optimización se encuentran en reducir la fricción entre la vista del producto y la decisión de compra, así como en implementar estrategias que aumenten la  recurrencia de usuarios después de la primera interacción.  Asi como evaluar categoría del producto, dispositivo y tiempo de navegación para identificar los factores que influyen en el abandono en esta etapa.



