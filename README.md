# Procesamiento del lenguaje natural con tweets de desastres. 

Descargar y subir los siguientes archivos train.csv test.csv para los datos a entrenar desde acá: 
[Kaggle Data](https://www.kaggle.com/competitions/nlp-getting-started/data)

Tener en cuenta a la hora de leer los csv del drive cargarlos desde la carpeta correcta, en nuestro caso de esta manera:

```python
    df_train = pd.read_csv("/content/drive/MyDrive/Colab Notebooks/Deep Learning/Proyecto/disaster_train.csv")
    df_test = pd.read_csv("/content/drive/MyDrive/Colab Notebooks/Deep Learning/Proyecto/disaster_test.csv")
```

Ser paciente, el entrenamiento de los modelos puede ser demorado(3h-4h)