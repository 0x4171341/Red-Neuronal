# Red-Neuronal
* _Red_ _neuronal_  que realiza análisis y prediccion de patrones 
* Este programa carga y preprocesa los datos de un archivo, entrena un modelo de clasificación utilizando el algoritmo de bosque aleatorio
* Realiza análisis sobre los datos y predice los números más probables de salir. Los resultados se muestran en patrones de 5 numeros


* **pandas**: para el manejo de datos en forma de DataFrames.
* **numpy**: para operaciones numéricas.
* **sklearn.ensemble.RandomForestClassifier**: para entrenar un modelo de clasificación de bosque aleatorio.
* **sklearn.model_selection.train_test_split**: para dividir los datos en conjuntos de entrenamiento y prueba.


- **train_model**(): utiliza el algoritmo de bosque aleatorio para entrenar un modelo de clasificación.
- **analyze_repeated_numbers**(): calcula los números más repetidos para una hora y fecha específicas.
- **predict_probable_numbers**(): utiliza el modelo entrenado para predecir los números.
- **print_predictions**(): imprime los resultados del análisis y las predicciones.
- **run_forecast**(): realiza el preprocesamiento de los datos, entrena el modelo, realiza el análisis y las predicciones
