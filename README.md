# 📊 Análisis de Rentabilidad B2B - OfiCentro Perú (Power BI)

## 🎯 Contexto del Proyecto
OfiCentro Perú S.A.C. es un distribuidor mayorista B2B de suministros, tecnología y mobiliario de oficina. El desafío principal de la gerencia era la falta de visibilidad sobre la *rentabilidad real*. Las decisiones se basaban únicamente en el volumen de ingresos, lo que llevaba a priorizar productos de alta rotación pero bajo margen de ganancia.

*Objetivo:* Diseñar y desarrollar un dashboard de Business Intelligence en Power BI que permita a la gerencia cambiar su enfoque estratégico del "volumen de ventas" hacia la "rentabilidad real" (Margen Bruto), evaluando el desempeño de productos, clientes y fuerza de ventas.

## 🛠️ Herramientas y Habilidades Aplicadas
* *Power BI Desktop:* Desarrollo de visualizaciones e interactividad.
* *Modelado de Datos:* Diseño de modelo relacional (Esquema Copo de Nieve / Snowflake).
* *DAX (Data Analysis Expressions):* Creación de medidas calculadas y KPIs complejos.
* *Análisis de Negocios:* Transformación de requerimientos comerciales en métricas accionables.

## 🗄️ Modelo de Datos
Se construyó un modelo robusto de 10 tablas estructurado en esquema de copo de nieve, garantizando la eliminación de ambigüedades en las rutas de filtrado. 
* *1 Tabla de Hechos:* Hechos_Ordenes (almacena transacciones, precios, costos y cantidades).
* *9 Tablas de Dimensiones principales y sub-dimensiones:* Calendario, Clientes, Productos, Vendedores, Canal de Venta, Industrias, 
---
<img width="1212" height="744" alt="image" src="https://github.com/user-attachments/assets/816e4071-99a3-4dbe-865e-a53f5753bb2e" />
---
## 🚀 Páginas del Dashboard y Hallazgos

### 1. Resumen Ejecutivo de Rentabilidad
Vista de alto nivel para la gerencia. Permite evaluar la salud financiera general de la empresa.
* *Métricas clave:* Margen Bruto, Ingresos Totales, % de Margen y Costo Total.
* Incluye la evolución histórica del margen y una distribución geográfica de la rentabilidad a nivel nacional e internacional.

<img width="1283" height="719" alt="image" src="https://github.com/user-attachments/assets/ea232585-100a-40ce-ab3f-a61e1f405945" />

### 2. Análisis de Rentabilidad por Producto
Diseñado para el equipo de compras y producto, enfocándose en qué estamos vendiendo y cuánto nos deja.
* Permite identificar rápidamente las categorías estrella.
* Incluye un gráfico de dispersión (Scatter Plot) que correlaciona las unidades vendidas con el porcentaje de margen, permitiendo identificar productos de "alto esfuerzo y baja ganancia".

<img width="1278" height="718" alt="image" src="https://github.com/user-attachments/assets/91b14bb1-8b44-4da4-8342-2676dc79627b" />

### 3. Desempeño de la Fuerza de Ventas
Evalúa a los ejecutivos comerciales no solo por cuánto venden, sino por la calidad de su venta.
* *Métricas clave:* Ticket Promedio y Margen Bruto generado por vendedor.
* Permite visualizar el "mix de productos" que vende cada ejecutivo y cómo esto impacta en su rentabilidad final.

<img width="1280" height="721" alt="image" src="https://github.com/user-attachments/assets/7e1e63de-bdd6-49bf-9bc6-76694f204331" />

### 4. Análisis de Clientes y Mercados Estratégicos
Vista orientada al equipo de marketing comercial para entender dónde está concentrado el valor.
* Cruza la información del cliente con su industria y región.
* Permite segmentar por canales de adquisición (ej. E-commerce vs. Venta corporativa) y tamaño de la empresa.

<img width="1278" height="718" alt="image" src="https://github.com/user-attachments/assets/147ff75a-2441-491e-81e7-57b640baf501" />

### 5. Explorador de Detalles (Drillthrough)
Una tabla granular a nivel de registro que sirve como herramienta de auditoría para analizar transacciones individuales, fechas exactas y vendedores involucrados.

<img width="1278" height="721" alt="image" src="https://github.com/user-attachments/assets/0aa29b68-59cf-49c1-94a3-b58e06a27258" />

---
Proyecto desarrollado como portafolio personal para demostrar habilidades en análisis de datos, modelado relacional y visualización.
