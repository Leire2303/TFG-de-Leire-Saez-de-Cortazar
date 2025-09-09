# Evaluación automática de resúmenes en base a cinco criterios: Coherencia, Fluidez, Relevancia, Consistencia y 5W1H con modelos de lenguaje de gran tamaño

Con el fin de investigar la evaluación automática de resúmenes, en este trabajo se entrenan cinco modelos Mistral 7B independientes utilizando fine-tuning, utilizando la técnica de LoRA (Low-Rank-Adaptation), 
para que actúen como evaluadores automáticos emulando el juicio
humano a través de cinco dimensiones de calidad: coherencia, consistencia, fluidez, relevancia
y 5W1H. Una vez obtenidos los resultados, se han utilizado las métricas Spearman, Kendall Tau
y MAE. Para ello, se ha utilizado el conjunto de datos BASSE con un total de 2,040 resúmenes
en castellano evaluados por humanos.
