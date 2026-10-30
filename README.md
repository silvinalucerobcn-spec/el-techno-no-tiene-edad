# El techno no tiene edad 🎶

Análisis exploratorio de la escucha de electrónica y techno en España
por edad y sexo, comparando cinco ediciones entre 2010–2011 y 2024–2025.

## Motivación y objetivo

Mi afición al techno y la presencia de personas mayores de 40 años
en las fiestas a las que asisto despertaron mi curiosidad.

Este proyecto analiza la escucha de la categoría «Electrónica, tecno».
Los datos disponibles no permiten medir directamente la asistencia a fiestas.

## Fuente de datos

Ministerio de Cultura, CULTURABase.
Encuesta de Hábitos y Prácticas Culturales en España.

| Edición | Archivo |
|---|---|
| 2010–2011 | musica04.csv |
| 2014–2015 | musica00.csv |
| 2018–2019 | musica01.csv |
| 2021–2022 | musica3.csv |
| 2024–2025 | musica2.csv |

Tabla utilizada: «Personas que suelen escuchar música grabada al menos
una vez al trimestre según el género musical por sexo y edad».

## Herramientas

- Python y pandas para la preparación y el análisis.
- Matplotlib para las visualizaciones.
- Google Colab para el cuaderno.
- NotebookLM para preparar la presentación a partir del análisis.

## Preparación de los datos

Se reunieron 904 filas de cinco archivos CSV.
No se detectaron valores vacíos ni filas completamente duplicadas.

Se añadieron los periodos ausentes, se unificaron etiquetas equivalentes
y se separaron los totales de los porcentajes de géneros musicales.
Después se seleccionó «Electrónica, tecno» para analizar su evolución.

## Preguntas del análisis

1. ¿Cómo evoluciona la escucha según el grupo de edad?
2. ¿Qué grupos presentan mayor porcentaje de escucha en 2024–2025?
3. ¿Qué diferencias se observan entre hombres y mujeres?
4. ¿Dónde se sitúa electrónica y techno frente a otros géneros?

## Principales resultados

- Entre la primera y la última edición, el porcentaje aumenta en todos
  los grupos de edad analizados.
- En el grupo de 45–54 años pasa del 4,6 % al 15,9 %:
  un aumento de 11,3 puntos porcentuales.
- Entre las personas de 55 años en adelante pasa del 1,1 % al 6,5 %.
- En 2024–2025, el grupo de 25–34 años presenta el mayor porcentaje: 29,5 %.
- En esa edición, los porcentajes son del 21,8 % entre los hombres
  y del 12,2 % entre las mujeres.

## Cómo consultar y ejecutar el proyecto

Abre el archivo `.ipynb` para consultar el código y los resultados guardados.

Para ejecutarlo en Google Colab:
1. Abre el cuaderno mediante su enlace a Colab.
2. Sube los cinco CSV al panel Archivos de Colab, en `/content/`.
3. Conserva exactamente los nombres indicados en la tabla.
4. Ejecuta las celdas en orden, desde el principio.

La presentación en PDF está incluida en el repositorio.

## Limitaciones

- La categoría oficial agrupa electrónica y techno.
- Los intervalos de edad no permiten aislar exactamente a los mayores de 40.
- Los porcentajes no representan el reparto por edades del público.
- La pregunta admite respuestas múltiples: los porcentajes de los géneros
  no tienen que sumar 100 %.
- El análisis es descriptivo y no establece causas ni significación estadística.
- Un aumento de la escucha no demuestra un aumento de asistencia a fiestas.

## Autoría

Silvina Lucero.

Proyecto formativo realizado con apoyo de IA para comprender el código,
orientar el análisis y preparar la presentación.
