# AluraStore
Challege Alura Store
## Propósito del análisis realizado
Este análisis tiene como objetivo explorar los factores que afectan la cancelación de clientes (churn) en una plataforma de ventas en línea. Utilizando técnicas de limpieza de datos, análisis exploratorio y modelos predictivos, el propósito es identificar patrones que conducen a la evasión de clientes y proponer estrategias efectivas para mejorar la retención.

## Estructura del proyecto y organización de los archivos
Este repositorio contiene los siguientes archivos:

- **`AluraStoreLatam-Andres_1_8_25.ipynb`**: Cuaderno de Jupyter con el análisis de datos completo, desde la carga y limpieza de datos hasta la creación de modelos predictivos y visualización de resultados.
- **`README.md`**: Este archivo de documentación que explica el propósito del análisis, cómo ejecutar el cuaderno, y ejemplos de los gráficos e insights obtenidos.

Los archivos están organizados de manera que se pueden ejecutar de forma secuencial para obtener los resultados completos del análisis.

## Ejemplos de gráficos e insights obtenidos
Durante el análisis, se generaron diversos gráficos que visualizan patrones clave en los datos. Algunos de los gráficos incluidos en el cuaderno son:

- **Distribución de ventas por categoría**: Un gráfico de barras que muestra las categorías de productos con mayores ventas, ayudando a identificar las más populares.
- **Tendencias de cancelación de clientes**: Un gráfico de líneas que muestra cómo varían las tasas de cancelación de clientes a lo largo del tiempo, destacando posibles picos o caídas.
- **Impacto de la actividad del cliente en la cancelación**: Un gráfico de dispersión que relaciona la actividad de los usuarios en la plataforma con la probabilidad de cancelación.

Estos gráficos proporcionan una visualización clara de los comportamientos de los clientes y ayudan a identificar las áreas que necesitan ser optimizadas para mejorar la retención.

## Instrucciones para ejecutar el notebook
Para ejecutar este análisis en tu propio entorno, sigue estos pasos:

1. **Instalación de dependencias**:
   Asegúrate de tener las siguientes librerías instaladas en tu entorno de Python:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

2. **Abrir el notebook**:
Si usas Google Colab, sube el archivo .ipynb y ejecútalo directamente en la plataforma.
Si usas Jupyter Notebook o JupyterLab en tu máquina local, abre el archivo .ipynb y ejecuta las celdas en orden.

3. **Carga de datos**:
El notebook asume que los datos están en el formato adecuado y ubicados correctamente. Si es necesario, ajusta las rutas de los archivos dentro del código para reflejar la ubicación correcta de los datos en tu sistema.

4. **Ejecución**:
Ejecuta las celdas del notebook de arriba hacia abajo. El cuaderno generará resultados e insights, incluidos gráficos y modelos predictivos, a medida que vayas avanzando.
