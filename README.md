# 🧠 Alura Store – Análisis de Ventas y Satisfacción del Cliente

Este proyecto forma parte del *Challenge de Alura Latam*, orientado al fortalecimiento de competencias en **análisis de datos con Python**.  
El objetivo principal es **extraer, analizar y visualizar información clave** sobre las ventas, los productos, las categorías y la satisfacción del cliente en múltiples tiendas de la plataforma **Alura Store**.

---

## 🚀 Objetivo del Proyecto

El propósito de este análisis es desarrollar una comprensión integral del comportamiento comercial de las tiendas participantes, identificando:
- Los productos más y menos vendidos.
- La valoración media de los clientes por tienda.
- El costo de envío promedio.
- La distribución de categorías más populares.
- Los indicadores de ingresos y satisfacción global.

La finalidad es **transformar los datos en conocimiento accionable**, aplicando técnicas de *data analysis* y *data visualization*.

---

## 🧩 Estructura del Proyecto

El análisis se desarrolla paso a paso dentro de **Google Colab**, utilizando un flujo de trabajo reproducible.  
A continuación se detalla la estructura lógica:

1. **Carga de Datos**  
   - Importación del dataset original en formato `.csv`.
   - Inspección inicial, limpieza de valores faltantes (`NaN`) y normalización de columnas.

2. **Análisis Exploratorio (EDA)**  
   - Identificación de patrones de venta y comportamiento del cliente.  
   - Cálculo de métricas descriptivas por tienda.

3. **Análisis Específicos**
   - Ventas por categoría de producto.  
   - Calificación promedio por tienda.  
   - Productos más y menos vendidos.  
   - Costo de envío promedio.

4. **Visualización de Resultados**
   - Gráficos de barras, líneas y circulares con `Matplotlib`.  
   - Representación clara y comparativa de los indicadores clave.

---

## 🧮 Tecnologías y Librerías Utilizadas

- **Python 3.12**
- **Pandas** → manipulación y análisis de datos tabulares  
- **Matplotlib / Seaborn** → visualización de datos  
- **NumPy** → operaciones numéricas  
- **Google Colab** → entorno interactivo para análisis reproducible  

---

## 📊 Principales Hallazgos

- Las tiendas muestran **variaciones significativas en los ingresos totales**, evidenciando diferencias estratégicas en ventas y eficiencia operativa.  
- La **categoría “Muebles”** fue la más vendida en todas las tiendas, consolidando su dominio comercial.  
- Las calificaciones promedio rondan los **4.0 puntos**, reflejando un alto nivel de satisfacción del cliente.  
- Se observa una **tendencia descendente en los costos de envío promedio**, lo que podría indicar optimización logística.  

---

## 🧭 Cómo Ejecutar el Proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/David16021/Alura_Store.git
