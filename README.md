# INFO279 - Tarea 1

Este repositorio contiene el cuadernillo jupyter de la tarea 1 de la asignatura INFO279

<aside>
💡

Para esta tarea se hizo uso de los datos proporcionados por el profesor en el drive del curso

- train_data.csv
- dataset_agosto2024.csv

Estos no están en el repositorio debido a su peso por lo que deberá añadirlos a la carpeta raíz del proyecto por su cuenta

</aside>

## Cuadernillo

Para ejecutar el cuadernillo es necesario tener instaladas las dependencias necesarias en el kernel, luego ejecutar todo el cuadernillo. Este entrenara un modelo de clasificación de noticias, además dara como output un csv con 100 noticias aleatorias entregando

```python
{
  'id_news': Id de la noticia evaluada
  'event': El evento de la noticia
  'category': La categoria entregada por el modelo previamente entrenado
  'address': Donde ocurrio la noticia (Si es que se pudo extraer)
  'latitud': Latitud de la direccion
  'longitud': Longitud de la direccion
}
```

<aside>
💡

Además se hace uso de dos csv adicionales que contienen las comunas del país y los países del mundo, con el fin de crear una función que extraiga la dirección de manera mas precisa.

</aside>
