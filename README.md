# :bar_chart: **Análisis de Sentimiento de Campañas de ZARA**

## Generador de Comentarios Simulados en Varios Idiomas
Este proyecto utiliza Python y Pandas para generar comentarios simulados en diferentes idiomas (inglés, español, italiano y francés) sobre campañas de la marca Zara. Los comentarios están categorizados en tres tipos: positivos, negativos y neutros.
## Contenido del Repositorio
- `data_notebook.ipynb`: Código Python que genera los comentarios simulados y los organiza en DataFrames de Pandas.
- `README.md`: Este archivo, que proporciona información sobre el proyecto.
- `data.csv`: Archivo CSV que contiene los comentarios simulados generados por el script.
## Requisitos
- Python 3.x
- Pandas
- Langdetect

## Explicación
El archivo CSV generado (comentarios.csv) tiene las siguientes columnas:
- Comentario: El texto del comentario generado.
Nombre_Campana: El nombre de la campaña asociada al comentario.
- Nombre_Usuario: El nombre de usuario simulado que hizo el comentario.
- Sentimiento: El tipo de sentimiento del comentario (positivo, negativo o neutro).
- Idioma: El idioma detectado del comentario (inglés, español, italiano, francés).


Aquí puedes ver un extracto del archivo comentarios.csv:

| Comentario                                              | Nombre_Campana      | Nombre_Usuario | Sentimiento | Idioma |
|---------------------------------------------------------|---------------------|----------------|-------------|--------|
| La nouvelle collection de Zara est absolument magnifique ! | Collection Magnifique | Fashionista123 | Positivo    | Français  |
| J'ai été vraiment déçu(e) par la nouvelle collection de Zara. Mauvaise qualité et trop cher. | Collection Décevante | FashionCritic | Négatif    | Français  |
| L'ultima campagna di Zara va bene, niente di speciale.  | Campagna Accettabile | NeutralObserver | Neutro      | Italiano |
| I can't believe we are living in a time where Zara works better on their campaigns than some BIG fashion houses. | Zara Campaign Excellence | TrendSetter77 | Positivo    | Inglés   |

## :bar_chart: **Power BI Dashboard**
El resultado del análisis se muestra en Power BI.


### :incoming_envelope: **Información de contacto**
Si teneis alguna duda, no dudeis en contactar conmigo! (elenaluquereyes@gmail.com)