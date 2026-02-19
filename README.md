# Prophet_banco_bienestar
Para activar el (venv) en windows: **venv\Scripts\Activate**
Actuaizaciones en la rama **geralt-dev**. Desde main con **git switch geralt-dev**







**Nota:** Siempre que utilice un conjunto de datos con NeuralProphet, debe ser un marco de datos de pandas con el siguiente formato y propiedades:

* La columna de series de tiempo debe llamarse “ds” y contener valores de fecha y hora.

* La columna de valor debe llamarse “y” y contener valores flotantes.

El pronóstico se compone de los siguientes componentes: tendencia, estacionalidad anual y semanal. Estos se combinan para crear el pronóstico.








### Comentarios:
**1)** dataset fit=predict
**2)** 
    n_forecasts=30
    n_lags=21
    Eso implica que el modelo está intentando predecir 30 días adelante usando 21 días atras...

**Propuesta:** 
Predicción de liquidez diaria

Con horizonte 1–7 días (operativo)

O 14 días (planeación logística)


