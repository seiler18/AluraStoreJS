# 🛍️ Alura Store - Análisis de Rendimiento de Tiendas

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
alura-store/
├── AluraStoreLatam.ipynb              # Cuaderno con el análisis de datos
├── base-de-datos-challenge1-latam/    # Archivos CSV con la data de las 4 tiendas
├── venv/                              # Entorno virtual de Python (no se sube al repo)
├── .gitignore                         # Archivo que define qué ignorar en Git
└── README.md                          # Documentación del proyecto
```

## 📈 Ejemplos de Gráficos e Insights

> ⚠️ Estos ejemplos se completarán a medida que avancemos con el análisis.

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
