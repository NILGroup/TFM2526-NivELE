# TFM2526-NivELE
Participación en tarea NivELE Iberlef 2026. TFM Raquel Jimeno Valdepeñas.

Este repositiorio contiene los notebooks y los resultados de las pruebas realizadas para la tarea NivELE pertenenciente a la competición de IberLEF 2026.

# Estructura del repositorio

* [notebooks/](notebooks): Todas las pruebas realizadas
  *   [PrimerasAproximaciones](notebooks/1_PrimerasAproximaciones_RaquelJV_15_04.ipynb)
  *   [Division_dataset_corpusELE](notebooks/2_Division_dataset_corpusELE.ipynb)
  *   [FineTuning_MrBert_RaquelJV](notebooks/3_FineTuning_Bert_RaquelJV.ipynb)
  *   [FineTuning_BETO_RaquelJV](notebooks/4_FineTuning_BETO_RaquelJV.ipynb)
  *   [Zero_shot_Mistral_7B_RaquelJV](notebooks/5_Zero_shot_Mistral_7B_RaquelJV.ipynb)
  *   [Few_shot_Mistral_7B_RaquelJV](notebooks/6_Few_shot_Mistral_7B_RaquelJV.ipynb)
    
* [prompts/](prompts): 
  *   [zero_shot_prompt.txt](prompts/zero_shot_prompt.txt)
  *   [few_shot_prompt.txt](prompts/few_shot_prompt.txt)

* [submissions/](submissions): Resultados enviados a la competición
  *   [predictions_MrBERT.csv](submissions/predictions.csv)
  *   [predictionsBETO.csv](submissions/predictions2.csv)
  *   [predictionsBETO.csv](submissions/predictions3.csv)
  *   [predictionsMistral_zero_shot.csv](submissions/predictionsMistral.csv)
  *   [submissionMistral_few_shot.csv](submissions/submissionMistral.csv)

El entrenamiento y evaluación de los modelos fue realizado con el conjunto de datos "[FJC/corpusELE.csv](https://huggingface.co/datasets/FJC/corpusELE.csv)" con los archivos del CAES (Corpus de Aprendices de ELE) del Instituto Cervantes.
