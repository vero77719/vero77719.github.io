Predicción de Ventas en Supermercados

El objetivo del trabajo es realizar un pronóstico de ventas de productos que se venden en Ecuador basándonos datos históricos utilizando técnicas de series temporales.

En el caso de los supermercados, una previsión más precisa puede reducir el desperdicio de alimentos relacionado con el exceso de existencias, mejorar la satisfacción del cliente, reducir costos operativos e ineficiencias y anticipar picos o cambios de demanda futura. 

El dataset cuanta con información sobre ventas de cientos de productos que se venden en las tiendas Favorita de Ecuador. El link del dataset es el siguiente: 
https://www.kaggle.com/competitions/store-sales-time-series-forecasting/data

Los datos de entrenamiento incluyen fechas diarias, información de la tienda y del producto, si el artículo estaba en promoción y las cifras de ventas.

Los archivos adicionales incluyen información complementaria que puede ser útil para crear modelos de forecasting, tales como precio del petróleo, ya que la economía ecuatoriana depende mucho de este comodity. Además, datos como los feriados y días festivos que pueden servir como features de los modelos.

Se evaluaron 9 modelos distintos: 4 baselines estadísticos (Naive Forecast, MA7, MA14 y MA30), 3 modelos de Machine Learning (Random Forest, XGBoost y LightGBM) y 2 modelos de series temporales (SARIMAX y LSTM). Todos los modelos fueron entrenados por separado para cada familia de productos.

Se trata del trabajo final de la Diplomatura en Ciencia de Datos de la UTN
