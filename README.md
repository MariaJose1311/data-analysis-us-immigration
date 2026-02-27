# Análisis Exploratorio de Datos (EDA): Proceso de Visas PERM en EE. UU.

## 1. Contexto de Negocio

Este proyecto simula un caso de estudio para **"InmigraData Solutions"**, una firma de abogados de inmigración que asesora a empresas estadounidenses en el patrocinio de trabajadores extranjeros para la residencia permanente (Green Card) a través del proceso PERM.

El proceso es largo, costoso y complejo, y los clientes de la firma necesitan respuestas basadas en datos a preguntas como:
*   ¿Qué posibilidades de éxito tiene nuestro caso?
*   ¿Qué perfiles profesionales son los más demandados?
*   ¿Qué empresas son las más activas y cómo nos comparamos?

## 2. Objetivo del Proyecto

El objetivo principal es realizar un **Análisis Exploratorio de Datos (EDA)** exhaustivo sobre el histórico de casos PERM para descubrir patrones, tendencias y factores clave de éxito. Los insights obtenidos se traducirán en recomendaciones estratégicas para que la firma pueda asesorar a sus clientes de manera más efectiva.

## 3. Dataset

El análisis se basa en el dataset **"US PERM Visas"** de Kaggle, que contiene aproximadamente 374,000 registros de solicitudes de visa PERM con 154 características por caso.

- **Fuente:** [US PERM Visas en Kaggle](https://www.kaggle.com/datasets/jboysen/us-perm-visas/data)

## 4. Metodología y Pasos del Análisis

El proyecto se desarrolló siguiendo un flujo de trabajo estructurado para garantizar la calidad y relevancia de los hallazgos.

### a. Limpieza y Preprocesamiento de Datos
*   **Manejo de Nulos:** Se eliminaron más de 30 columnas con un alto porcentaje de valores nulos (>90%) que no aportaban valor al análisis.
*   **Integridad de Datos:** Se descartaron filas donde faltaban datos esenciales como el estado del caso, el nombre de la empresa o el puesto de trabajo.
*   **Transformación de Tipos:** Se convirtieron las columnas de fecha a formato `datetime` para análisis de tendencias y se limpió y convirtió la columna de salario a formato numérico para análisis cuantitativo.

### b. Análisis Exploratorio de Datos (EDA)
Se realizaron una serie de análisis para responder a las preguntas clave del negocio:
1.  **Distribución de Resultados:** ¿Cuál es la tasa de éxito general de los casos?
2.  **Tendencias Temporales:** ¿Cómo ha evolucionado el volumen de casos a lo largo de los años?
3.  **Análisis de Empleadores:** ¿Qué compañías son las más activas en el patrocinio de visas?
4.  **Análisis de Perfiles:** ¿Qué puestos de trabajo y países de origen son los más comunes?
5.  **Análisis de Salarios:** ¿Existe una correlación entre el salario ofrecido y el resultado del caso? Se manejaron los outliers salariales para una visualización más clara.

## 5. Hallazgos Clave y Visualizaciones

### 1. Tasa de Éxito General
La gran mayoría de los casos presentados son **'Certified' (Aprobados)**, lo que sugiere que los casos bien preparados tienen una alta probabilidad de éxito.

### 2. Principales Empresas Patrocinadoras
Gigantes del sector tecnológico y grandes firmas de consultoría dominan el panorama, siendo los mayores impulsores de la inmigración de alta cualificación.

### 3. Puestos de Trabajo Más Demandados
Los roles de **ingeniería de software** representan la categoría más grande con diferencia, destacando la enorme demanda de talento tecnológico en EE. UU.

### 4. Salario y Tasa de Aprobación
El análisis muestra que la mediana salarial de los casos **'Certified' es notablemente superior** a la de los casos 'Denied'. Esto sugiere que las posiciones mejor remuneradas, que a menudo se corresponden con roles de mayor cualificación y casos mejor documentados, tienen más probabilidades de ser aprobadas.

## 6. Conclusiones y Recomendaciones Estratégicas

Basado en los hallazgos, se proponen las siguientes recomendaciones para "InmigraData Solutions":

*   **Foco en el Sector Tecnológico:** Especializar los servicios y el marketing de la firma para atraer a empresas tecnológicas, ya que son el principal motor del mercado PERM.
*   **Asesoramiento Salarial Estratégico:** Aconsejar a los clientes que un salario competitivo y bien justificado no solo atrae mejor talento, sino que podría estar correlacionado positivamente con el éxito del caso.
*   **Especialización por Perfil:** Desarrollar un profundo conocimiento en la evaluación de perfiles de ingeniería de software, especialmente de candidatos provenientes de India, que representan el mayor volumen de solicitudes.

## 7. Tecnologías Utilizadas
*   Python
*   Pandas
*   NumPy
*   Matplotlib
*   Seaborn
*   Google Colab
*   Kaggle API

## 8. Cómo Ejecutar el Proyecto
1.  Clonar este repositorio.
2.  Ejecutar el Jupyter Notebook (`perm_visa_analysis.ipynb`) para replicar el análisis.


🧑‍💻 Autor

    Nombre: Maria Jose Suarez
    Contacto: https://www.linkedin.com/in/suarezmariajose/
