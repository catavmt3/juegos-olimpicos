# 120 años de Juegos Olímpicos
### Análisis histórico 1896–2016

Especialización en Ciencia de Datos e Inteligencia Artificial · UTEC – MIT · 2025–2026  
**Equipo:** Catalina Vaz Martins · Florencia Barrios · Diego Della Nave

---

## Descripción

Análisis exploratorio sobre 120 años de historia olímpica, desde los primeros Juegos de Atenas (1896) hasta Río de Janeiro (2016). El proyecto combina una evaluación exhaustiva de la calidad del dataset con un análisis orientado a responder preguntas clave sobre participación, rendimiento y evolución de los Juegos.

## Contenido

El notebook `juegos_olimpicos.ipynb` está organizado en las siguientes secciones:

1. **Carga y exploración inicial** — estructura del dataset, tipos de datos, estadísticos descriptivos
2. **Calidad de datos** — evaluación de completitud, validez, precisión, consistencia, unicidad e integridad
3. **Limpieza** — tratamiento de nulos, duplicados y conversión de tipos
4. **Análisis de participación** — ediciones por temporada, países con presencia continua e interrumpida
5. **Presencia y representación** — evolución de atletas por país, crecimiento de la participación femenina
6. **Disciplinas** — deportes históricos, evolución del número de eventos
7. **Medallero** — ranking por país, análisis por tipo de medalla, efecto de localía
8. **Perfil de atletas** — relación entre edad, altura, peso y rendimiento por deporte

## Resultados destacados

- **271.116 registros** · **15 variables** · **1.385 duplicados** identificados y eliminados
- La participación femenina pasó de prácticamente nula a representar casi la mitad del total
- Se identificaron y validaron datos atípicos extremos (atleta de 10 años, atleta de 97 años) contra fuentes oficiales
- Los países anfitriones muestran una tendencia a mejorar su rendimiento en el medallero
- Las variables de altura y peso presentan patrones diferenciados según deporte

## Stack

```
Python · Pandas · NumPy · Matplotlib · Seaborn
```

## Fuente de datos

120 Years of Olympic History: Athletes and Results  
Compilado por Randi H. Griffin a partir de [sports-reference.com](https://www.sports-reference.com/)  
Disponible en [Kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
