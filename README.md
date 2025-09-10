# Evaluación automática de resúmenes en base a cinco criterios: Coherencia, Fluidez, Relevancia, Consistencia y 5W1H con modelos de lenguaje de gran tamaño

Con el fin de investigar la evaluación automática de resúmenes, en este trabajo se entrenan cinco modelos Mistral 7B independientes utilizando fine-tuning, utilizando la técnica de LoRA (Low-Rank-Adaptation), 
para que actúen como evaluadores automáticos emulando el juicio
humano a través de cinco dimensiones de calidad: coherencia, consistencia, fluidez, relevancia
y 5W1H. Para ello, se ha utilizado el conjunto de datos BASSE con un total de 2,040 resúmenes
en castellano evaluados por humanos. 

Los siguientes enlaces llevan a los cuadernos de Kaggle donde se han entrenado los modelos: 

<br>
<br>



**ANÁLISIS EXPLORATORIO DE LOS DATOS:** 
- https://www.kaggle.com/code/leireszc/an-lisis-exploratorio-de-los-datos

<br>
<br>



**COHERENCE**
 
  - Coherence sin aumento de datos: https://www.kaggle.com/code/leireszc/coherence-tfg-leire-sin-data-aumentation
  - Coherence con aumento de datos utilizando undersampling y oversampling aleatorio: https://www.kaggle.com/code/leireszc/coherence-tfg-leire-oversampling-undersampling
  - Aumento de datos con sinónimos: https://www.kaggle.com/code/bernisaez/data-aumentation-coherence
  - Coherence con aumento de datos utilizando sustitución por sinónimos: https://www.kaggle.com/code/bernisaez/coherence-con-sinonimos

<br>
<br>



**FLUENCY**
- Fluency sin aumento de datos: https://www.kaggle.com/code/bernisaez/fluency-leire-sin-data-aumentation
- Fluency con aumento de datos utilizando undersampling y oversampling aleatorio: https://www.kaggle.com/code/bernisaez/fluency-tfg-leire-oversampling-undersampling
- Aumento de datos con sustitución de sinónimos: https://www.kaggle.com/code/bernisaez/data-aumentation-fluency
- Fluency con aumento de datos utilizando el dataset aumentado con sustitución de sinónimos: https://www.kaggle.com/code/bernisaez/fluency-tfg-leire-eda
- Aumento de datos con sustitución de sinónimos experimental: https://www.kaggle.com/code/bernisaez/fluency-data-aumentation-con-eda-sin-ukn
- 5W1H con aumento de datos utilizando el dataset aumentado con sustitución de sinónimos experimental: https://www.kaggle.com/code/bernisaez/fluency-tfg-leire-eda-2


<br>
<br>

 
**5W1H**
- 5W1H sin aumento de datos: https://www.kaggle.com/code/leireszc/5w1h-tfg-sin-data-aumentation
- 5W1H con aumento de datos utilizando undersampling y oversampling aleatorio: https://www.kaggle.com/code/leireszc/5w1h-tfg-oversampling-undersampling
- Aumento de datos con BackTranslation: https://www.kaggle.com/code/leireszc/data-aumentation-backtranslation-5w1h
- 5W1H con aumento de datos utilizando el dataset aumentado con Back-Translation: https://www.kaggle.com/code/leireszc/5w1h-tfg-oversampling-backtranslatio
- Aumento de datos con sustitución de sinónimos: https://www.kaggle.com/code/bernisaez/data-aumentation-5w1h-sin-nimos
- 5W1H con aumento de datos utilizando el dataset aumentado con sustitución de sinónimos: https://www.kaggle.com/code/leireszc/5w1h-tfg-leire-sin-nimos

  
<br>
<br>


**CONSISTENCY**
- Consistency sin aumento de datos: https://www.kaggle.com/code/saraglzb/consistency-sin-data-aumentation
- Consistency con aumento de datos utilizando undersampling y oversampling aleatorio: https://www.kaggle.com/code/saraglzb/consistency-under-oversampling

<br>
<br>


**RELEVANCE**
- Relevance sin aumento de datos: https://www.kaggle.com/code/leireszc/relevance-sin-data-aumentation
- Relevance con aumento de datos utilizando undersampling y oversampling aleatorio: https://www.kaggle.com/code/leireszc/relevance-oversampling-undersampling


