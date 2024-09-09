# 🚴 Adventure Works Cycles - Data Analysis with Power BI

Este proyecto consiste en un análisis integral del rendimiento de ventas de **Adventure Works Cycles** (AWC) utilizando Power BI. El objetivo principal es proporcionar insights clave sobre ingresos, costos, rentabilidad y distribución geográfica de clientes mediante un dashboard interactivo que facilita la toma de decisiones basadas en datos.

## 🗂 Estructura del Proyecto

El proyecto está organizado en cuatro avances, cada uno con sus respectivos archivos `.pbix` y documentación:

- **Avance 1**: Conexión y limpieza de datos.
- **Avance 2**: Construcción del modelo de datos relacional y mockup en PowerPoint.
- **Avance 3**: Creación de medidas DAX y columnas calculadas.
- **Avance 4**: Desarrollo del dashboard final y documentación del proyecto.

### 📁 Carpetas:
- **Avances**: Contiene los archivos `.pbix` correspondientes al progreso del proyecto en cada fase.
  - `Avance_1.pbix`
  - `Avance_2.pbix`
  - `Avance_3.pbix`
  - `Avance_4.pbix`
  
- **Mockup**: Incluye el archivo del mockup en PowerPoint.
  - `Mockup Informe PI M3.pptx`
  
- **Proyecto Final**: Contiene el archivo final con el dashboard completo.
  - `Proyecto Integrador M3 Completo.pbix`
  
- **Informe**: Documento que detalla el desarrollo del proyecto.
  - `DA_Roman_Hernan_informePIM3.docx`


## 🔑 Características Principales

- **Conexión y Limpieza de Datos**: Se utilizó la base de datos de **AdventureWorksDW2019**, seleccionando solo las tablas relevantes para el análisis y eliminando columnas innecesarias para optimizar el modelo.
  
- **Modelo Relacional**: Se construyó un modelo estrellado, con relaciones entre las tablas de dimensiones y hechos como `FactInternetSales`, `DimCustomer`, `DimProduct`, entre otras.

- **Medidas DAX**: Se crearon medidas calculadas para:
  - Ingresos totales y su variación anual.
  - Utilidad bruta y neta.
  - Costo de los bienes vendidos (COGS) y su variación.
  - Distribución de ingresos por cliente y país.
  
- **Dashboard Interactivo**: El informe final incluye múltiples visualizaciones como gráficos de líneas, columnas, mapas y medidores para mostrar:
  - Tendencias de ventas mensuales.
  - Distribución geográfica de clientes.
  - Rentabilidad por categoría de producto.
  - Comparación de ingresos y costos operacionales.

## 📊 Insights Principales

1. **Ingresos por País**: El mercado de Estados Unidos lidera tanto en ingresos como en cantidad de clientes.
2. **Tendencias Estacionales**: Los ingresos alcanzan su punto máximo en noviembre y diciembre debido a la temporada navideña.
3. **Rentabilidad por Segmento**: La categoría de **Bikes** genera los mayores ingresos, aunque con altos costos operacionales.
4. **Costos Operacionales**: El ratio de COGS es elevado, lo que sugiere que la empresa podría beneficiarse de optimizaciones en la cadena de suministro.

## 🛠 Herramientas Utilizadas

- **Power BI**: Para la creación del modelo de datos, medidas DAX y visualizaciones interactivas.
- **SQL Server**: Para la conexión y restauración de la base de datos de AdventureWorks.
- **PowerPoint, Figma, Canva**: Utilizados para el diseño del mockup del dashboard.
- **DAX**: Lenguaje utilizado para la creación de medidas y columnas calculadas.

## 📧 Contacto

Autor: Roman Hernan Rufino  
Email: hernanroman25@gmail.com  
Cohorte: DA_PT01  

---

¡Gracias por revisar este proyecto! 🎉