TourMZA – Asistente Inteligente para Planificar Visitas a Bodegas en Mendoza
README – Proyecto Final
Curso: IA – Entretejiendo Imaginación y Algoritmos

Este repositorio contiene el desarrollo del Proyecto Final, cuyo objetivo es aplicar modelos de Inteligencia Artificial (texto-texto y texto-imagen) para resolver una problemática real mediante ingeniería de prompts.




Proyecto Final
1. Nombre del proyecto

TourMZA: Asistente Inteligente para Planificar Visitas a Bodegas en Mendoza

Resumen

TourMZA es una Proof of Concept (POC) basada en Inteligencia Artificial que busca resolver la dificultad que enfrentan turistas y visitantes al planificar recorridos por bodegas en Mendoza. Mediante el uso de modelos de IA texto-texto y texto-imagen, el proyecto centraliza información dispersa, genera itinerarios personalizados y ofrece visualizaciones claras de las experiencias disponibles.

La solución utiliza técnicas de Fast Prompting para optimizar resultados, reducir iteraciones y demostrar cómo la ingeniería de prompts puede aplicarse a un problema real del turismo enológico, mejorando la experiencia del usuario y facilitando la toma de decisiones.

2. Introducción

Mendoza es reconocida internacionalmente como una de las capitales del vino. Cada año recibe miles de turistas que buscan recorrer bodegas y vivir experiencias enogastronómicas únicas. Sin embargo, la planificación de estos recorridos suele ser compleja debido a la dispersión de información, la falta de claridad en horarios, requisitos de reserva y la sobreoferta de opciones.

Este proyecto propone el desarrollo de una Proof of Concept (POC) basada en Inteligencia Artificial que combine modelos texto-texto y texto-imagen, utilizando técnicas de Fast Prompting, para facilitar la creación de itinerarios personalizados de visitas a bodegas en Mendoza.

3. Problemática identificada

Los turistas y visitantes locales tienen dificultades para:

Encontrar información centralizada y confiable sobre bodegas.

Optimizar recorridos según tiempo disponible y preferencias.

Comprender diferencias entre experiencias (degustación, gourmet, premium, etc.).

Visualizar recorridos y propuestas de manera clara.

Esto genera frustración, pérdida de tiempo y decisiones improvisadas que afectan la experiencia turística.

4. Propuesta de solución

Se propone TourMZA, un asistente inteligente que:

Genera itinerarios personalizados mediante prompts texto-texto.

Clasifica bodegas según tipo de experiencia, precios y horarios.

Optimiza recorridos en función del tiempo disponible.

Genera imágenes ilustrativas de recorridos y bodegas mediante prompts texto-imagen.

La solución se apoya en:

Modelo texto-texto: ChatGPT (OpenAI).

Modelo texto-imagen: Nightcafe (alternativa gratuita a DALL·E).

5. Desarrollo de la POC (Proof of Concept)

La POC se implementa en una Jupyter Notebook, combinando texto explicativo, prompts y resultados simulados.

5.1 Prompts Texto-Texto
Prompt 1 – Clasificación de bodegas
Actúa como guía turístico de Mendoza. Clasifica esta lista de bodegas en Luján de Cuyo
(Catena Zapata, Bodega Norton, Luigi Bosca, Susana Balbo, Durigutti Family Winemakers,
Achaval Ferrer, Casarena, Kaiken Wines, Lagarde, Septima) según tipo de experiencia
(degustación, gourmet, premium, aventura), rango de precios (bajo, medio, alto)
y horarios disponibles (9 a 17 hs, con reserva previa). Devuelve el resultado en una tabla clara.

Justificación: permite sintetizar información dispersa y presentarla de forma estructurada.

Prompt 2 – Generación de itinerario
Crea un itinerario de bodegas en Luján de Cuyo para un turista con 6 horas disponibles.
Incluye horarios estimados, recomendaciones de transporte, experiencia sugerida y nivel
de dificultad. Prioriza Catena Zapata, Luigi Bosca y Susana Balbo.

Justificación: optimiza tiempos y reduce la complejidad de planificación.

Prompt 3 – Optimización por preferencias
Propón tres itinerarios alternativos para un viajero que prioriza experiencias gourmet
y vistas panorámicas. Justifica cada opción usando bodegas de Luján de Cuyo
como Bodega Norton, Casarena y Lagarde.

Justificación: demuestra personalización avanzada y uso eficiente del prompt.

5.2 Prompts Texto-Imagen
Prompt 4 – Mapa ilustrado del recorrido
Illustrated flat-style map of a wine tour through Luján de Cuyo, Mendoza,
with vineyards, tasting icons, Andes mountains in the background,
minimalist and clean UI style.

Objetivo: visualizar el recorrido de forma clara y atractiva.

Prompt 5 – Tarjeta visual de bodega
Minimalist postcard illustration of a modern Mendoza winery,
with vineyards, Andes mountains, neutral color palette,
soft shadows and UI-friendly design.

Objetivo: generar piezas visuales reutilizables en interfaces o presentaciones.

6. Optimización de prompts (Fast Prompting)

Prompts claros y específicos.

Uso de roles (“Actúa como guía turístico”).

Restricción de variables (horarios, zona geográfica).

Outputs estructurados (tablas, listas, justificaciones).

Esto reduce iteraciones y mejora la calidad de resultados.

7. Viabilidad del proyecto
7.1 Viabilidad técnica

Uso de herramientas accesibles y gratuitas.

No requiere programación avanzada.

Implementación sencilla en Jupyter Notebook.

7.2 Viabilidad temporal

Alcance acotado (Luján de Cuyo).

Desarrollo posible en corto plazo.

Ideal para una POC académica.

7.3 Justificación del enfoque

Problema real y frecuente.

Aplicación directa de contenidos del curso.

Integración de IA con diseño UX/UI.

8. Objetivos del proyecto

Generar itinerarios personalizados según tiempo, presupuesto y preferencias.

Centralizar información relevante sobre bodegas de Mendoza.

Optimizar recorridos y tiempos de traslado.

Crear imágenes ilustrativas de recorridos y bodegas mediante IA.

Mejorar la experiencia del usuario y reducir la frustración en la planificación.

9. Metodología

El proyecto se desarrolla mediante una metodología exploratoria y práctica, centrada en la experimentación con prompts. En primer lugar, se analiza la problemática y se definen los requerimientos del usuario. Luego, se diseñan prompts texto-texto para clasificación, generación y optimización de itinerarios, y prompts texto-imagen para la creación de visuales ilustrativos.

La implementación se documenta en una Jupyter Notebook, combinando texto explicativo, prompts y resultados. Finalmente, se evalúa la calidad de los outputs obtenidos y se ajustan los prompts aplicando técnicas de Fast Prompting para mejorar precisión y eficiencia.

10. Herramientas y tecnologías

ChatGPT (OpenAI): generación de texto, clasificación y creación de itinerarios.

Nightcafe: generación de imágenes a partir de prompts texto-imagen.

Jupyter Notebook: documentación y presentación de la POC.

GitHub: repositorio para entrega y versionado del proyecto.

Figma (opcional): prototipado visual de interfaces.

11. Conclusión

TourMZA demuestra cómo la Inteligencia Artificial, aplicada mediante ingeniería de prompts, puede resolver una problemática real del turismo enológico. La Proof of Concept valida el uso combinado de modelos texto-texto y texto-imagen para centralizar información, generar itinerarios personalizados y mejorar la experiencia del usuario.# TourMZA
