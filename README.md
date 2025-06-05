# Admin.Tiendas-del-Sr.Juan
Primer Desafío  DATASCIENCE_Admin.Tiendas del Sr.Juan
By: Martinez Garcia Diego Eduardo - Data Science Student from Alura Latam
# Alura Store - Análisis Comparativo de Tiendas

## Propósito del Proyecto

Este proyecto realiza un análisis comparativo entre cuatro tiendas diferentes para apoyar la toma de decisiones estratégicas del Sr. Juan, quien busca identificar cuál tienda vender para invertir en un nuevo negocio. A través de métricas clave como facturación, ventas por categoría, calificaciones, productos más y menos vendidos, y costos de envío promedio, se evalúa la eficiencia y rentabilidad de cada tienda.

---

## Estructura del Proyecto

El proyecto está organizado en los siguientes archivos y carpetas:

- `analisis_tiendas.ipynb`  
  Notebook principal donde se realiza todo el análisis de datos, generación de gráficos y elaboración de conclusiones.

- `datos/`  
  Carpeta que contiene los archivos CSV o datasets con información de las ventas, productos, precios y costos de envío por tienda.

- `funciones.py`  
  Archivo con funciones reutilizables para cálculo de métricas, generación de gráficos y procesamiento de datos.

- `README.md`  
  Documentación del proyecto.

---

## Ejemplos de Gráficos e Insights

- **Gráficos de pastel** que muestran el top 5 de productos más vendidos por tienda, facilitando la visualización rápida de productos con mayor rotación.
  
- **Gráficos de dispersión** que comparan el precio de los productos con el costo de envío, permitiendo identificar posibles ineficiencias en la logística.

- Insights importantes:
  - La Tienda 1, aunque tiene la facturación más alta, presenta el mayor costo de envío promedio y la calificación más baja, indicando menor eficiencia operativa.
  - La Tienda 4 tiene la facturación más baja pero también el costo de envío más bajo, mostrando un perfil más económico aunque con menor volumen.
  - Tiendas 2 y 3 muestran un balance más favorable entre ingresos, costos y satisfacción del cliente.

---

## Cómo Ejecutar el Notebook

1. Clona este repositorio o descarga los archivos en tu equipo.

2. Asegúrate de tener Python instalado (recomendado Python 3.7+).

3. Instala las librerías necesarias (si no las tienes):

   ```bash
   pip install pandas matplotlib
