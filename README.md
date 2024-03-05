
<p align=center>
  <img src="Imagenes/Portada.png" alt="alt text" width="800" style="display: block; margin: auto;"/>
  

  <h1
<p align=center>
  <h1 align="center">EQUIPO DE TRABAJO </h1>
<p align=center>
  <img src="Imagenes/Equipo.png" alt="alt text" width="600" style="display: block; margin: auto;"/> </h1>
<p align=center>
  <h1 align="center">ESQUEMA GENERAL DEL PROYECTO </h1>
<p align=center>
<img src="Imagenes/ESQUEMA DE TRABAJO negro.png" alt="alt text" width="600" style="display: block; margin: auto;"/>

<hr>  

## **Descripción y Contexto**

Guayaba es una plataforma web diseñada para brindar servicios de gráficos de análisis técnico a traders e inversores en el mercado financiero mediante una amplia base de datos. Permite incorporar indicadores, analizar tendencias y visualizar métricas de cualquier activo financiero, accesible a usuarios novatos como a integraciones en brokers, exchanges y fondos de inversión.

<p align=center>
<img src="Imagenes/Logo.jpg" alt="alt text" width="300" style="display: block; margin: auto;"/>

 **Análisis Técnico Avanzado:**

- Gráficos interactivos y herramientas de análisis técnico.
- Indicadores personalizables para un análisis detallado.

 **Datos en Tiempo Real:**

- Precio en tiempo real de una variedad de activos financieros.
- Actualizaciones instantáneas para una toma de decisiones oportuna.

**Análisis Fundamental Integral:**

- Datos históricos y métricas de diferentes monedas y ecosistemas bursátiles.
- Cobertura completa de acciones, bonos, índices, criptomonedas, forex, etc.

**Portfolios Personalizados:**

- Seguimiento de activos en la moneda local del usuario.
- Conversión automática a las tasas de cambio más relevantes.

**Solicitud de Análisis Personalizado:**

- Los usuarios pueden solicitar análisis detallados de activos específicos.
- Resúmenes entregables a través de paneles interactivos.

**Integración mediante APIs:**

- Permite conectar con usuarios avanzados para el seguimiento de precios.
- Brinda la posibilidad de incorporar a la web de un bróker, exchange o listador de precios.

## **Paquetes de Servicios**

Se pretende ofrecer distintos paquetes para satisfacer las necesidades de los usuarios:
  
**Gratuito:**
- Acceso básico a las herramientas de análisis técnico.
- Datos en tiempo real limitados.
  
**Premium:**
- Funcionalidades avanzadas de análisis técnico y fundamental.
- Datos en tiempo real completos.
- Creación y gestión de portfolios.

## **Ubicación**

Diseñado y desarrollado en Argentina, Guayaba permite adoptar las cotizaciones de activos locales e incorporar las variables circunstanciales de la macroeconomía.

## **Datasets**

Se trabajó con pares BTC-USD, GLD-USD y S&P500PX-USD. Los archivos iniciales se descargaron en formato CSV desde la página de [Yahoo Finanzas](https://es.finance.yahoo.com/) y estan disponibles en la carpeta Data Cruda del repositorio.

📄 BTC-USD_Yahoo.csv   📄 GLD-USD_Yahoo.csv   📄 S&P500SPX-USD_Yahoo.csv

Los archivos contienen las columnas: Date, Open, High, Low, Close, Adj Close, Volume.

## **Tecnologías Utilizadas**

<a href="#"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python Badge" style="border-radius: 10px; background-color: #FFD700"></a>
<a href="#"><img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy Badge" style="border-radius: 15px; background-color: #FF6347"></a>
<a href="#"><img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas Badge" style="border-radius: 20px; background-color: #00CED1"></a>
<a href="#"><img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn Badge" style="border-radius: 25px; background-color: #FF1493"></a>
<a href="#"><img src="https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib Badge" style="border-radius: 30px; background-color: #7FFF00"></a>
<a href="#"><img src="https://img.shields.io/badge/Seaborn-013243?style=for-the-badge&logo=seaborn&logoColor=white" alt="Seaborn Badge" style="border-radius: 35px; background-color: #8A2BE2"></a>
<a href="#"><img src="https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white" alt="Excel Badge" style="border-radius: 45px; background-color: #00FF7F"></a>
<a href="#"><img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=power-bi&logoColor=white" alt="Power BI Badge" style="border-radius: 50px; background-color: #FFA500"></a>
<a href="#"><img src="https://img.shields.io/badge/Machine%20Learning-FFA500?style=for-the-badge&logo=machine-learning&logoColor=white" alt="Machine Learning Badge" style="border-radius: 50px; background-color: #FFA500"></a>



## **Análisis Exploratorio de los Datos (EDA) y Extracción, Transformación y Carga (ETL)**

Se analizó la estructura de los datasets, cantidad de filas y columnas, tipos de datos, datos nulos, duplicados, relacion entre los mismos, variables descriptivas, etc. Los archivos resultantes se exportaron y guardaron en formato CSV.

<p align=center>
<img src="Imagenes/Dispersion.png" alt="alt text" width="500" style="display: block; margin: auto;"/>

</p>

<p align=center>
<img src="Imagenes/Price.png" alt="alt text" width="500" style="display: block; margin: auto;"/>

</p>

El EDA y ETL realizados se puede consultar en el repositorio.

</p>

## **Visualización de los Resultados (Power BI)**

Con la creación de un dashboard de Power BI se realizó el análisis integral y visualización de los datos. Con una interfaz intuitiva y capacidades avanzadas de análisis, esta herramienta facilita la creación de paneles interactivos y visualizaciones para la toma de decisiones informadas y colaboración en tiempo real. 

## **Modelo de Machine Learning**

Con el uso de modelos de Machine Learning se desarrolló un modelo predictivo mediante el análisis de datos históricos, el mismo permite prever tendencias futuras y mejorar la toma de decisiones empresariales, automatizar procesos, identificar patrones y mejorar la eficiencia operativa. 

Contexto del proyecto: El proyecto simula un entorno real de trabajo en el departamento de Data de una empresa, lo que sugiere que el objetivo es aplicar técnicas de análisis de datos para obtener información útil para la toma de decisiones.

## **Pagina Web y Móvil**

La web de Guayaba fue creada con la aplicación *Durable*, en formatos desktop, tablet y móvil. También contiene links a los dashboards y perfiles del equipo.
[Link ](https://guayaba.mydurable.com/es)

## **Conclusiones**

Se trabajó con tres pares de datos financieros: BTC-USD, GLD-USD y S&P500SPX-USD descargados desde Yahoo Finanzas. Se utilizaron diversas tecnologías y herramientas, incluyendo Python, NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn, Excel, Power BI y Machine Learning para llevar a cabo el proyecto y realizar un análisis exhaustivo de los datasets para comprender su estructura, calidad y relaciones entre variables. 

Se utilizó Power BI para crear visualizaciones interactivas y paneles informativos que faciliten la interpretación de los datos y la toma de decisiones y se desarrolló un modelo predictivo utilizando técnicas de Machine Learning para prever tendencias futuras y mejorar la toma de decisiones empresariales. 

## **Recomendaciones**




Implementar un ciclo de retroalimentación continua para mejorar la efectividad del modelo predictivo y las visualizaciones realizando ajustes y mejoras en función de los comentarios recibidos, las nuevas tendencias en los datos y los cambios en el entorno empresarial. 

Explorar la incorporación de más fuentes de datos para enriquecer aún más el análisis y mejorar la precisión del modelo predictivo. La inclusión de datos adicionales, como indicadores económicos, datos de redes sociales o información demográfica, podría proporcionar una visión más completa y perspicaz de los factores que afectan a las tendencias financieras. 

## **Contactos:**

<span style="font-size: 18px;">Lorena Paola Satori</span><br>
<a href="https://www.linkedin.com/in/lorena-paola-sartori-177316115?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">
    <img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" style="width: 110px;">
</a>
<a href="https://github.com/Anonimus201990" target="_blank">
    <img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white" alt="GitHub" style="width: 110px;">
</a>

<span style="font-size: 18px;">Nicolas Encina Tutuy</span><br>
<a href="https://www.linkedin.com/in/nicolas-encina-tutuy-310a5036/" target="_blank">
    <img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" style="width: 110px;">
</a>
<a href="https://github.com/nicoencinatutuy" target="_blank">
    <img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white" alt="GitHub" style="width: 110px;">
</a>

<span style="font-size: 18px;">Daniela Arvelo</span><br>
<a href="https://www.linkedin.com/in/daniela-arvelo/" target="_blank">
    <img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" style="width: 110px;">
</a>
<a href="https://github.com/tu_usuario" target="_blank">
    <img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white" alt="GitHub" style="width: 110px;">
</a>

<span style="font-size: 18px;">Duniet Marrero García</span><br>
<a href="https://www.linkedin.com/in/duniet-marrero-garcia-7a246aa1" target="_blank">
    <img src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" style="width: 110px;">
</a>
<a href="https://github.com/dunietmg" target="_blank">
    <img src="https://img.shields.io/badge/github%20-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white" alt="GitHub" style="width: 110px;">
</a>






