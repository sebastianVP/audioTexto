# Taller Deep Learning: Audio a texto y deteccion del hablante
# OBJETIVO DE ESTE REPOSITORIO
1. Transformar audio de un video  o grabacion a texto.
2. A través de Deep Learning se indentificará el idioma del audio para luego ser transformado a texto.
3. Además, se busca identificar a que persona pertenece el audio a traves de la diarizacion((proceso para detectar en qué momento habla cada interlocutor).
# RECOMENDACIONES
Utilizar un video de corta duracion para tener una respuesta en el menor tiempo posible.
# LIBRERIAS A UTILIZAR
* pytube
* pydub
* Resemblyzer
* spectralcluster
* git+https://github.com/openai/whisper.git
* jiwer
# INSTALACION LIBRERIA
* transformers plotly pysentimiento sentence_transformers
# INSTALACION DEL MODELO DE SPACY
* spacy download es_core_news_md
* pip install accelerate -U
* pip install transformers[torch]
# PRIMERA PASO  DE ESTE PROYECTO
* Corregir la libreria pytube
