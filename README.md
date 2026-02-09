# Challenge-Alura-store

## Descripción del Proyecto
Este proyecto es parte del Challenge de Data Science de Alura Latam. El objetivo principal fue realizar un Análisis Exploratorio de Datos sobre cuatro datasets correspondientes a cuatro tiendas diferentes, para determinar su rendimiento comercial.

El "cliente" (ficticio), el Sr. Juan, necesitaba una recomendación basada en datos para decidir qué tienda vender, para poder invertir en otro negocio

## Tecnologías y Herramientas Utilizadas
El proyecto fue desarrollado íntegramente en Python utilizando el entorno de Google Colab.
Las librerías principales fueron:
* Pandas: Para la manipulación, limpieza y agregación de datos (DataFrames).
* Matplotlib: Para la generación de gráficos y visualización de datos.

## Funcionalidades y Pasos Realizados
Durante el desarrollo del análisis, realicé las siguientes tareas:

1.  Carga de Datos: Importación de 4 archivos CSV desde un repositorio remoto.
2.  *Limpieza de Datos:
    * Eliminación de columnas innecesarias (índices repetidos).
    * Conversión de tipos de datos (transformar precios y textos).
    * Manejo de strings para corregir descripciones de productos.
3.  **Análisis:
    * Cálculo de Facturación Total por tienda.
    * Análisis de Satisfacción del Cliente (promedio de calificaciones).
    * Identificación de productos Más y Menos vendidos.
    * Evaluación de costos de Envío Promedio.
4.  **Visualización:** Creación de un panel de gráficos para comparar las métricas solicitadas.

## Conclusión y Recomendación

**Vender la Tienda 4
* Es la tienda con la menor facturación acumulada de las cuatro.
* A pesar de tener los costos de envío (logísticos) más bajos, no logró traducir esa ventaja en un mayor volumen de ventas ni en una mejor satisfacción del cliente (su calificación es promedio-baja).
* Se considera el activo menos eficiente del grupo.
