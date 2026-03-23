# gerardorioscr-sprint7-final-project

Proyecto: Análisis de Clientes - ConnectaTel

Objetivo del Proyecto
El objetivo de este proyecto es analizar el comportamiento de los clientes de ConnectaTel para identificar patrones de uso, segmentar usuarios y generar recomendaciones que ayuden a mejorar la oferta de planes y la toma de decisiones del negocio.

Se busca responder preguntas clave como:
- ¿Cómo se comportan los clientes según su edad y nivel de uso?
- ¿Qué segmentos generan mayor valor?
- ¿Existen patrones de uso atípicos (outliers)?
- ¿Qué mejoras se pueden implementar en los planes actuales?


Datasets Utilizados
El análisis se basa en los siguientes datasets:

plans.csv → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
users.csv → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
usage.csv → detalle del uso real de los servicios (llamadas y mensajes)


---

Etapas del Análisis

1. Exploración Inicial 
- Revisión de estructura de los datos
- Identificación de valores nulos
- Detección de posibles errores o inconsistencias

2. Limpieza de Datos
- Conversión de tipos de datos (fechas, numéricos)
- Manejo de valores nulos
- Eliminación o tratamiento de outliers
- Corrección de valores atípicos o sentinels

3. Transformación de Datos
- Creación de nuevas variables (features)
- Agrupación por usuario
- Cálculo de métricas de uso (llamadas, mensajes, datos)

4. Análisis Exploratorio
- Segmentación por edad
- Segmentación por nivel de uso
- Identificación de patrones de comportamiento
- Análisis de distribución de variables

5. Generación de Insights
- Identificación de segmentos clave
- Detección de usuarios de alto valor
- Análisis de outliers y su impacto
- Recomendaciones para el negocio

---

Cómo Ejecutar el Notebook

Opción 1: Google Colab (Recomendado)
1. Ve a: https://colab.research.google.com/
2. Haz clic en **"Subir"**
3. Selecciona el archivo:
4. 4. Asegúrate de subir también los datasets en la misma sesión
5. Ejecuta las celdas en orden

---

Opción 2: Jupyter Notebook (Local)
1. Instala dependencias:
2. pandas numpy matplotlib seaborn
