# Natural language processing for hate speech detection

## Descripción del proyecto
Este proyecto utiliza SpaCy y técnicas de Procesamiento de Lenguaje Natural (NLP) para analizar comentarios con y sin odio. 
Se aplican reconocimiento de entidades (NER), lematización y análisis morfológico para identificar diferencias en la estructura lingüística y detectar tendencias en el discurso de odio.


## Objetivos
- Analizar un corpus de comentarios para identificar diferencias entre mensajes con y sin odio.
- Aplicar reconocimiento de entidades nombradas con SpaCy para detectar patrones en el uso de nombres de personas, lugares y organizaciones.
- Evaluar la distribución de palabras en función de su género y número.
- Extraer los lemas más frecuentes en cada tipo de comentario y comparar su uso.
- Determinar si existen tendencias lingüísticas que permitan predecir la presencia de odio en un mensaje.


## Flujo de trabajo
- Carga y exploración del corpus → Limpieza de datos, detección de valores nulos y análisis inicial.
- Análisis de palabras y oraciones → Conteo de palabras, oraciones y estructuras gramaticales.
- Detección de Entidades NER → Identificación y análisis de nombres de personas, organizaciones y ubicaciones.
- Lematización y eliminación de stopwords → Extracción de la raíz de las palabras y eliminación de términos irrelevantes.
- Análisis de tendencias lingüísticas → Comparación entre comentarios con y sin odio.


## Próximas mejoras

- Implementar modelos de clasificación automática para predecir si un comentario contiene odio.
- Incluir análisis de sentimiento para evaluar la carga emocional de los mensajes.
- Mejorar la visualización de resultados con gráficos interactivos.
