# TFM2526-NivELE
Participación en tarea NivELE Iberlef 2026. TFM Raquel Jimeno Valdepeñas.

Este repositiorio contiene los notebooks y los resultados de las pruebas realizadas para la tarea NivELE pertenenciente a la competición de IberLEF 2026.

# Estructura del repositorio

* `notebooks/`: Todas las pruebas realizadas
  * `1_PrimerasAproximaciones_RaquelJV_15_04.ipynb`
  * `2_Division_dataset_corpusELE.ipynb`
  * `3_FineTuning_Bert_RaquelJV.ipynb`
  * `4_FineTuning_BETO_RaquelJV.ipynb`
  * `5_Zero_shot_Mistral_7B_RaquelJV.ipynb`
  * `6_Few_shot_Mistral_7B_RaquelJV.ipynb`

* `prompts/`: Prompts utilizados en los experimentos
  * `zero_shot_prompt.txt`
  * `few_shot_prompt.txt`

* `submissions/`: Resultados enviados a la competición
  * `predictions.csv`: submission del fine tuning de MrBERT
  * `predictions2.csv`: submission del fine tuning de BETO
  * `predictions3.csv`: submission del fine tuning de BETO
  * `predictionsMistral.csv`: submission Mistral con zero-shot
  * `submissionMistral.csv`: submission Mistral con few-shot

El entrenamiento y evaluación de los modelos fue realizado con el conjunto de datos [FJC/corpusELE.csv](https://huggingface.co/datasets/FJC/corpusELE.csv) basado en los archivos del CAES (Corpus de Aprendices de ELE) del Instituto Cervantes.
