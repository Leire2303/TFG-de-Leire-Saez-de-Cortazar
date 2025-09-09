# Evaluación automática de resúmenes en base a cinco criterios: Coherencia, Fluidez, Relevancia, Consistencia y 5W1H con modelos de lenguaje de gran tamaño

Con el fin de investigar la evaluación automática de resúmenes, en este trabajo se entrenan cinco modelos Mistral 7B independientes utilizando fine-tuning, utilizando la técnica de LoRA (Low-Rank-Adaptation), 
para que actúen como evaluadores automáticos emulando el juicio
humano a través de cinco dimensiones de calidad: coherencia, consistencia, fluidez, relevancia
y 5W1H. Para ello, se ha utilizado el conjunto de datos BASSE con un total de 2,040 resúmenes
en castellano evaluados por humanos. 

Los siguientes enlaces llevan a los cuadernos de Kaggle donde se han entrenado los modelos: 

**ANÁLISIS EXPLORATORIO DE LOS DATOS:** 
- https://www.kaggle.com/code/leireszc/an-lisis-exploratorio-de-los-datos


**COHERENCE**
 
  - Coherence sin aumento de datos: https://www.kaggle.com/code/leireszc/coherence-tfg-leire-sin-data-aumentation
  - Coherence con aumento de datos utilizando undersampling y oversampling aleatorio: https://www.kaggle.com/code/leireszc/coherence-tfg-leire-oversampling-undersampling
  - Aumento de datos con sinónimos: https://www.kaggle.com/code/bernisaez/data-aumentation-coherence
  - Coherence con aumento de datos utilizando sustitución por sinónimos: https://www.kaggle.com/code/bernisaez/coherence-con-sinonimos


