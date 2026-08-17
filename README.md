# sprint7-final-project
Análisis del comportamiento de usuarios por segemento de edad y nivel de uso de los planes de telefonia

**Objetivo**

Identificar patrones de uso, comportamientos atípicos y comprender que segmentos de clientes muestran necesidades diferenciales.

**Datasets Utilizados**

- plans.csv : planes actuales, precios de planes y minutos, GB incluidos y costos extras.
- users_latam.csv : información de los clientes, como edad, ciudad, planes, fechas de registro.
- usage.csv : detalle de uso real en llamadas y mensajes.

**Etapas de Análsis**

- Exploración y estructura de datesets.
- Identificación de problemas de calidad de los datos.
- Detección de valores invalidos y sentinels.
- Estandarización de fechas.
- Limpieza básica de datos.
- Corregir sentinels y fechas imposibles.
- Resumenes estadistico.
- Visualización de distribución e identificación de outliers.
- Segmentación de clientes por edad y nivel de uso.
- Insights 

**Como ejecutar el notebook**

Desde el siguiente boton dando clic para ir al notebook

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/cccano/sprint7-final-project/blob/main/Proyect_Telecom_S7.ipynb)

**Guia de reproducción**

En el notebook queda guardado en una carpeta datasets el conjunto de archivos csv que son necesarios para realizar el análisis.
solo tienes que direccionarte a colab desde el boton que abre el notebook, importar pandas ejecutar pd.read.csv()para que esten activos.

