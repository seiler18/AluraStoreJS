
<details>
<summary> Aprendiendo hacer ETL (2DO MODULO)</summary>

## NumPy

NumPy, una abreviatura de Numerical Python, es una biblioteca de código abierto de Python para computación científica, un campo de estudio que utiliza recursos computacionales para comprender y resolver problemas. Esta biblioteca permite trabajar con la manipulación de objetos array multidimensionales, así como con sus derivados, como matrices, secuencias y otros. Además de eso, también posee una amplia variedad de operaciones rápidas con los arrays, incluyendo operaciones matemáticas y lógicas, manipulación de formato, ordenación y selección, herramientas de estadística y cálculo, y mucho más.

## Pandas

Pandas es una biblioteca de código abierto en Python utilizada para el análisis de datos. Proporciona herramientas poderosas y fáciles de usar para la manipulación y análisis de datos en formatos de tablas, como CSV, Excel, SQL y muchos otros.

Con Pandas, podemos cargar datos desde diversas fuentes en un objeto llamado DataFrame, que es una tabla de datos similar a una hoja de cálculo de Excel. Luego, podemos trabajar con estos datos realizando operaciones como filtrar, ordenar, agregar y transformar.

La biblioteca Pandas es ampliamente utilizada en aplicaciones de ciencia de datos, aprendizaje automático, finanzas y análisis empresarial. Es una herramienta esencial para profesionales que trabajan con datos, como analistas de datos, científicos de datos e ingenieros de datos.

## Matplotlib
Matplotlib es una biblioteca de Python utilizada para crear visualizaciones gráficas de datos. Permite generar gráficos, diagramas y visualizaciones interactivas de manera sencilla y personalizable. Con Matplotlib, los usuarios pueden crear gráficos de líneas, barras, dispersión, histogramas y muchos otros tipos de visualizaciones.
Matplotlib es ampliamente utilizado en el ámbito de la ciencia de datos, análisis de datos y visualización de información. Proporciona una interfaz intuitiva y flexible para crear gráficos de alta calidad y personalizables, lo que facilita la comprensión y presentación de datos complejos.

## Seaborn
Seaborn es una biblioteca de visualización de datos basada en Matplotlib que proporciona una interfaz más sencilla y atractiva para crear gráficos estadísticos. Seaborn se centra en la visualización de datos estadísticos y ofrece una amplia gama de gráficos predefinidos, como gráficos de dispersión, gráficos de barras, gráficos de violín, mapas de calor y más.
Seaborn se integra fácilmente con Pandas, lo que permite crear visualizaciones directamente a partir de DataFrames. Además, Seaborn proporciona una serie de funciones para personalizar los gráficos, como la elección de paletas de colores, estilos de trazado y etiquetas.

##Pyplot
Pyplot es un módulo de Matplotlib que proporciona una interfaz similar a MATLAB para crear gráficos y visualizaciones de datos. Permite crear gráficos de manera sencilla y rápida, utilizando una sintaxis intuitiva y fácil de entender.
Pyplot ofrece una amplia gama de funciones para crear gráficos de líneas, barras, dispersión, histogramas y muchos otros tipos de visualizaciones. También permite personalizar los gráficos con etiquetas, títulos, leyendas y estilos de trazado.


</details>


---
<details>
<summary> Modelado de Datos con Python (1 ER MODULO)</summary>

### 🛍️ Alura Store - Análisis de Rendimiento de Tiendas

## Primer proyecto de analisis ocupando pandas,matplotlib,seaborn 

Este proyecto tiene como objetivo analizar el rendimiento de **cuatro tiendas** con el fin de ayudar al Sr. Juan a tomar una decisión estratégica: **vender la tienda con menor desempeño** para invertir en un nuevo negocio.

## 📌 Propósito del Análisis

A través de un estudio de datos de ventas, productos y clientes, este análisis busca identificar:

1. 📊 La **facturación total** de cada tienda.
2. 🏷️ Las **categorías más populares** en cada tienda.
3. ⭐ El **promedio de evaluación** de los clientes por tienda.
4. 📦 Los **productos más y menos vendidos** por tienda.
5. 🚚 El **costo promedio de envío** de cada tienda a sus clientes.

Con esta información, será posible tomar una decisión fundamentada sobre qué tienda vender.

## 📁 Estructura del Proyecto

```bash
AluraLatamCourse
    AluraStore/
    ├── AluraStoreLatam.ipynb              # Cuaderno con el análisis de datos
    ├── base-de-datos-challenge1-latam/    # Archivos CSV con la data de las 4 tiendas
    ├── venv/                              # Entorno virtual de Python (no se sube al repo)
    ├── .gitignore                         # Archivo que define qué ignorar en Git
README.md                          # Documentación del proyecto
```

## 📈 Ejemplos de Gráficos e Insights

- Gráfico de barras mostrando la facturación total por tienda.
- Gráfico circular con la proporción de ventas por categoría.
- Tabla con el promedio de evaluación por cliente agrupado por tienda.
- Ranking de productos más vendidos por tienda.

## ▶️ Cómo ejecutar el análisis (CON UBUNTU/DEBIAN)

1. Clona este repositorio:
   ```bash
   git clone https://github.com/seiler18/AluraStoreJS.git
   cd alura-store

2. Instala el paquete para crear entornos virtuales (si no lo tienes)
    ```bash
    sudo apt install python3.12-venv

3. (Opcional pero recomendado) Crea un entorno virtual:
    ```bash
    python3 -m venv venv
    source venv/bin/activate

4. Asegúrate de tener las librerías necesarias instaladas: 
    ```bash
    pip install pandas matplotlib seaborn ipykernel jupyter


# 📈 Informe Final de Análisis de Tiendas - Alura Store

## 🧭 Introducción

El objetivo de este análisis fue determinar cuál de las cuatro tiendas disponibles representa la mejor opción para que el Sr. Juan comercialice sus productos. Para esto, se realizaron estudios detallados de distintos factores clave: facturación total, categorías de productos más vendidos, calificación promedio de los clientes, productos más y menos vendidos, y el costo promedio de envío. A través de gráficos y análisis numéricos, se obtuvo una visión completa del desempeño de cada tienda.

---

## 📊 Desarrollo del Análisis

### 💰 Ingresos Totales

Los ingresos totales por tienda fueron los siguientes:

- **Tienda 1**: $1.150.880.400 CLP
- **Tienda 2**: $1.116.343.500 CLP
- **Tienda 3**: $1.098.019.600 CLP
- **Tienda 4**: $1.038.375.700 CLP

🔍 *Conclusión:* La **Tienda 1** lidera en facturación, con más de $1.150 millones de pesos, seguida por la Tienda 2.

---

### 🛒 Categorías Más Populares

Se analizaron las cinco categorías más vendidas por tienda:

- **Tienda 1**:
  - Muebles (465)
  - Electrónicos (448)
  - Juguetes (324)
  - Electrodomésticos (312)
  - Deportes y diversión (284)

- **Tienda 2**:
  - Muebles (442)
  - Electrónicos (422)
  - Juguetes (313)
  - Electrodomésticos (305)
  - Deportes y diversión (275)

- **Tienda 3**:
  - Muebles (499)
  - Electrónicos (451)
  - Juguetes (315)
  - Electrodomésticos (278)
  - Deportes y diversión (277)

- **Tienda 4**:
  - Muebles (480)
  - Electrónicos (451)
  - Juguetes (338)
  - Deportes y diversión (277)
  - Electrodomésticos (254)

🔍 *Conclusión:* Las categorías más fuertes en todas las tiendas son **Muebles** y **Electrónicos**, siendo **Tienda 3** la que más vendió en Muebles, y **Tienda 1** la más balanceada.

---

### ⭐ Calificación Promedio

Promedio de calificaciones dadas por los clientes:

- **Tienda 1**: 3.98
- **Tienda 2**: 4.04
- **Tienda 3**: 4.05
- **Tienda 4**: 4.00

🔍 *Conclusión:* **Tienda 3** obtiene la mejor calificación promedio por parte de los clientes, seguida muy de cerca por la Tienda 2.

---

### 🏆 Productos Más y Menos Vendidos

Resumen de los productos más populares y los menos vendidos:

- **Tienda 1**: 
  - 🔼 *Más vendido*: Microondas (60 ventas)
  - 🔽 *Menos vendido*: Auriculares con micrófono (33 ventas)

- **Tienda 2**:
  - 🔼 *Más vendido*: Iniciando en programación (65 ventas)
  - 🔽 *Menos vendido*: Juego de mesa (32 ventas)

- **Tienda 3**:
  - 🔼 *Más vendido*: Kit de bancas (57 ventas)
  - 🔽 *Menos vendido*: Bloques de construcción (35 ventas)

- **Tienda 4**:
  - 🔼 *Más vendido*: Cama box (62 ventas)
  - 🔽 *Menos vendido*: Guitarra eléctrica (33 ventas)

🔍 *Conclusión:* Todas las tiendas muestran buena rotación en productos de gran demanda, con diferencias mínimas entre sus top de ventas.

---

### 🚚 Costo Promedio de Envío

Costo de envío promedio por tienda:

- **Tienda 1**: $26.019 CLP
- **Tienda 2**: $25.216 CLP
- **Tienda 3**: $24.806 CLP
- **Tienda 4**: $23.459 CLP

🔍 *Conclusión:* La **Tienda 4** tiene el menor costo de envío promedio, lo cual puede representar un atractivo adicional para los clientes.

---

## ✅ Conclusión y Recomendación

Luego de considerar todos los factores analizados, se concluye que la mejor opción para el Sr. Juan es **la Tienda 1**. Esta tienda destaca por:

- Tener **la facturación más alta**, superando los $1.150 millones de CLP.
- Mantener un **balance sólido entre todas las categorías de productos**.
- Presentar un **alto volumen de ventas en múltiples productos populares**.
- Obtener una **muy buena calificación promedio de clientes (3.98)**, aunque no la más alta.
- Aunque su costo de envío es el más alto, este no parece afectar negativamente el volumen de ventas.

**Recomendación Final:**  
✅ El Sr. Juan debería vender sus productos en **Tienda 1**, ya que esta demuestra un rendimiento comercial robusto, liderazgo en ingresos y gran demanda de productos, lo que representa la mayor oportunidad de éxito para sus ventas.

---
</details>

---



