# precios-competencia

Historial diario de precios publicados por la competencia de OMODA | JAECOO en Chile.

- `historial.csv`: una fila por fecha de revisión, modelo y versión (precio lista, bono marca, bono financiamiento y precio final, en CLP).
- Se actualiza automáticamente cada mañana leyendo la web de cada marca.
- Fuente actual: https://jetourchile.cl/w/dashing
- `fuentes.csv`: un modelo por fila (ID, marca, modelo, link de la web oficial).
- `segmentos.csv`: a qué segmento OMODA | JAECOO compite cada modelo (un modelo puede ir en varios).
