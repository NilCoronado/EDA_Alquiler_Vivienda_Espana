# Guion del Vídeo — EDA Alquiler Vivienda España
## Duración total: 7 minutos

---

## REPARTO DE TIEMPO

| Bloque | Quién | Duración | Contenido |
|--------|-------|----------|-----------|
| Intro y presentación | Nil Coronado | 1 min 30 seg | Problema, dataset, hipótesis |
| Análisis y gráficos | Enrique Algarra | 3 min 30 seg | Los 8 gráficos |
| Conclusiones y cierre | Lucía Vetrano | 2 min | Hallazgos, hipótesis, reflexión |

---

## BLOQUE 1 — Nil Coronado (0:00 – 1:30)

### Introducción y contexto (0:00 – 0:45)

> "Hola, somos [nombres] y hoy os presentamos nuestro análisis exploratorio sobre el precio del alquiler en España.
>
> El alquiler se ha convertido en uno de los problemas más urgentes para millones de personas en España. En los últimos años los precios no han parado de subir, y cada vez es más difícil para una familia media permitirse vivir de alquiler en muchas ciudades.
>
> Pero más allá de los titulares, queríamos entender qué dicen los datos reales. ¿Dónde es más caro alquilar? ¿Ha subido siempre igual? ¿Influye el tipo de vivienda? Esas son las preguntas que nos hicimos al empezar este proyecto."

---

### Dataset e hipótesis (0:45 – 1:30)

> "Para responderlas usamos el dataset oficial de la Referencia del Precio del Alquiler de Vivienda, publicado por el Ministerio de Vivienda en datos.gob.es. Cubre todos los municipios de España con datos anuales entre 2011 y 2024, lo que nos da una visión histórica muy completa.
>
> Antes de analizar nada, planteamos cuatro hipótesis:
>
> H1: las grandes ciudades como Madrid y Barcelona serían las más caras.
> H2: existiría una desigualdad territorial clara entre comunidades.
> H3: el precio habría subido progresivamente con los años.
> Y H4: el tipo de vivienda influiría en el precio.
>
> ¿Cuántas se cumplen? Ahora lo vemos."

---

## BLOQUE 2 — Enrique Algarra (1:30 – 5:00)

### Gráfico 1 — Distribución de precios (1:30 – 1:55)

> "Empezamos con la distribución del índice de precio en España. Como podéis ver, la distribución está claramente sesgada hacia la derecha. La mayoría de municipios tienen un índice entre 200 y 500, con el pico en torno a 300. Pero hay una cola larga de valores muy altos que llegan a 2.000, correspondientes a zonas con precios extremos.
>
> Esto ya nos dice algo importante: España tiene un mercado muy heterogéneo."

---

### Gráfico 2 — Evolución temporal (1:55 – 2:20)

> "Este gráfico es clave para entender la hipótesis H3. Aquí vemos la evolución del índice entre 2011 y 2024. Caída durante la crisis hasta el mínimo de 2015, recuperación gradual hasta 2019, y después una aceleración muy pronunciada hasta 2024, donde alcanzamos el máximo histórico.
>
> H3 confirmada: los precios en 2024 son los más altos de toda la serie."

---

### Gráfico 3 — Ranking de provincias (2:20 – 2:50)

> "Y aquí llega la sorpresa del proyecto. Si teníais en mente que Madrid o Barcelona liderarían este ranking, os equivocabais.
>
> Las provincias más caras de España son Bizkaia, con un índice de alrededor de 640, y Gipuzkoa, con 600. Madrid y Barcelona están en el quinto y sexto puesto, con unos 510. También destaca Málaga, que irrumpe en el top 10 reflejando la presión del turismo y la demanda extranjera.
>
> La hipótesis H1 solo se cumple parcialmente: las grandes ciudades son caras, pero no son las más caras."

---

### Gráfico 4 — Desigualdad territorial (2:50 – 3:15)

> "Este boxplot muestra la distribución del precio para cada provincia. Fijaos en la diferencia entre los extremos: provincias del interior como Teruel, Ávila o Badajoz tienen cajas muy compactas y bajas. Madrid y Barcelona, en cambio, tienen una dispersión enorme con outliers que superan 2.000.
>
> H2 confirmada: la desigualdad territorial en España es enorme, y dentro de las grandes provincias también existe una desigualdad interna muy significativa."

---

### Gráficos 5 y 6 — Tipo de vivienda (3:15 – 3:45)

> "Pasamos al tipo de vivienda. El boxplot muestra que colectiva y unifamiliar tienen medianas similares, pero la unifamiliar presenta una dispersión mucho mayor, con outliers que alcanzan 2.200.
>
> Y en la evolución temporal vemos que ambas siguen la misma curva, pero la unifamiliar cae más en crisis y sube más en expansión. El gap entre las dos se amplía claramente desde 2019.
>
> H4 confirmada con matiz: el tipo de vivienda sí influye, pero más en los extremos altos del mercado que en los valores típicos."

---

### Gráficos 7 y 8 — Correlación y scatterplot (3:45 – 5:00)

> "Por último, el heatmap de correlación nos muestra algo muy revelador. La correlación entre el año y el precio es solo de 0,19. Es positiva, pero baja.
>
> Y el scatterplot lo confirma visualmente: los puntos de vivienda colectiva en azul forman una banda estrecha y estable en todos los años, mientras que la unifamiliar en naranja tiene una dispersión vertical enorme que crece hacia 2024.
>
> La conclusión estadística es clara: el tiempo no es lo que más explica el precio. Lo que más importa es dónde está la vivienda."

---

## BLOQUE 3 — Lucía Vetrano (5:00 – 7:00)

### Validación de hipótesis (5:00 – 5:45)

> "Muy bien, volvemos con los resultados de nuestras cuatro hipótesis.
>
> H1, sobre las grandes ciudades: parcialmente confirmada. Madrid y Barcelona están entre las más caras, pero el País Vasco las supera claramente. Ese fue nuestro hallazgo más inesperado.
>
> H2, sobre la desigualdad territorial: confirmada. La brecha entre las provincias más caras y las más baratas es de más del triple.
>
> H3, sobre la subida de precios: confirmada. 2024 es el año con el índice más alto de toda la serie histórica.
>
> Y H4, sobre el tipo de vivienda: confirmada con matiz. La unifamiliar es más cara y más volátil, especialmente en el segmento premium."

---

### Conclusión final (5:45 – 6:40)

> "Si tuviéramos que resumir este análisis en tres ideas:
>
> Primera: el alquiler en España está en máximos históricos. La aceleración entre 2020 y 2024 es la más intensa que hemos visto en 13 años de datos, y no hay señales de que vaya a frenarse.
>
> Segunda: el problema no es solo de Madrid y Barcelona. Hay un relato instalado en el debate público que sitúa el problema de la vivienda únicamente en las grandes metrópolis. Pero los datos dicen que Bizkaia y el País Vasco tienen los alquileres más altos del país. El problema es más amplio y más distribuido de lo que pensamos.
>
> Tercera: la desigualdad territorial es enorme. Hay una España donde alquilar es asequible y otra donde es prácticamente inaccesible para una familia de renta media. Y esa brecha no ha hecho más que crecer."

---

### Cierre (6:40 – 7:00)

> "Este ha sido nuestro análisis exploratorio del precio del alquiler en España. Los datos, el código y todos los gráficos están disponibles en nuestro repositorio de GitHub, enlazado en la descripción.
>
> Muchas gracias por vuestra atención."

---

