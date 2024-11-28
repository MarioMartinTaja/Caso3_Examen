La ciudad de Nueva York, es una de las ciudades más visitadas del mundo. Hay muchos anuncios de Airbnb en la ciudad de Nueva York para satisfacer la alta demanda de alojamiento temporal para viajeros, que puede durar desde unas pocas noches hasta muchos meses. En este proyecto, analizaremos más de cerca el mercado de Airbnb de Nueva York combinando datos de varios tipos de archivos como .csv, .tsv y .xlsx.

Recuerde que los archivos CSV, TSV y Excel son tres formatos comunes para almacenar datos. Tiene a su disposición [tres archivos](https://tajamar365.sharepoint.com/:f:/s/3405-MasterIA2024-2025/EoXMgjAJLLNJqWDyKDig8kABSUkpWj_HGQjl267qNnHS9g?e=foxjFc) que contienen datos sobre los anuncios de Airbnb de 2019:  

- `airbnb_price.csv `: Este es un archivo CSV que contiene datos sobre precios y ubicaciones de anuncios de Airbnb.  
  1. `listing_id`: identificador único del anuncio  
  2. `price`: precio del anuncio por noche en USD  
  3. `nbhood_full`: nombre del distrito y del barrio donde se encuentra el anuncio  
    

- `airbnb_room_type.xlsx`: Este es un archivo Excel que contiene datos sobre las descripciones de los anuncios de Airbnb y los tipos de habitaciones.  
  1. `listing_id`: identificador único del anuncio  
  2. `description`: descripción del anuncio     
  3. `room_type`: Airbnb tiene tres tipos de habitaciones: habitaciones compartidas, habitaciones privadas y casas o apartamentos completos 


- `airbnb_last_review.tsv`: Este es un archivo TSV que contiene datos sobre los nombres de los anfitriones de Airbnb y las fechas de revisión.  
  1. `listing_id`: identificador único del anuncio  
  2. `host_name`:  nombre del anfitrión del anuncio  
  3. `last_review`: echa en la que se revisó el anuncio por última vez
 
Como consultor que trabaja para una empresa inmobiliaria emergente, ha recopilado datos de anuncios de Airbnb de varias fuentes para investigar el mercado de alquileres a corto plazo en Nueva York. Analizará estos datos para brindar información sobre habitaciones privadas a la empresa inmobiliaria.
 
¿Cuáles son las fechas de las primeras y las últimas reseñas? Almacene estos valores como dos variables independientes con los nombres que prefiera.
- ¿Cuántos de los anuncios son habitaciones privadas? Guárdelo en cualquier variable.
- ¿Cuál es el precio promedio de los anuncios? Redondee a los dos decimales más cercanos y guárdelo en una variable.
- Combine las nuevas variables en un DataFrame llamado review_dates con cuatro columnas en el siguiente orden: first_reviewed, last_reviewed, nb_private_rooms y avg_price. El DataFrame solo debe contener una fila de valores.
