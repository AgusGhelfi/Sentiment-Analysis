# Sentiment-Analysis
Procesamiento de lenguaje natural

A través de este trabajo se buscaba poder integrar nociones y conocimientos sobre NLP vistas en el módulo, para generar un modelo de machine learning. El objetivo fue construir un clasificador el cual 
pueda predecir si una revisión realizada por un usuario es positiva o negativa (buena o mala). Para ello, utilizó un conjunto de datos que pertenece a la plataforma Yelp. Esta, posee una red de usuarios, 
los cuales realizan opiniones sobre lugares nocturnos, espacios culturales, locales comerciales, entre otros.

Se comenzó con el análisis de features, las mismas son:
				●  business_id: identificador del negocio al que se está realizando la review.
        ●  cool: cantidad de votos por haber sido una review “cool”.
        ●  date: fecha de realización de la revisión.
        ●  funny: cantidad de votos para una revisión “divertida”.
        ●  review_id: identificador único de revisión (ofuscado).
        ●  stars: cantidad de estrellas otorgadas por el usuario en referencia a la review.
        ●  text: revisión realizada por el usuario sobre un determinado negocio.
        ●  useful: cantidad de votos recibido por los usuarios a los cuales le resultó útil la revisión.
        ● user_id: id del usuario en la plataforma (ofuscado).

Como se puede observar no existe una variante target por lo cual uno de los desafíos era definir la misma basandose en las features del dataset. Anteriormente se valido que los tipos de datos de las 
features después de importarse correspondan con su valor intrínseco. S e procedió a hacer una exploración de los outliers y a realizar gráficos que se consideraron pertinente para entender la 
naturaleza del problema.

Por último se llevaron a cabo diversos modelos los cuales se evaluaron utilizando las siguientes métricas:
 				●  Precision.
        ●  Recall.
	      ●  F1-score.
	      ●  Análisis de AUC ROC.
 
