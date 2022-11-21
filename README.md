# LULCC_RF
Este código **clasifica la cobertura de suelos** de un área del departamento de Ancash utilizando técnicas de Machine Learning, específicamente el algoritmo de **Random Forest**. 
Para ello utiliza los paquetes `rasterio` `dbfread` `pandas` `scikeo.mla` para realizar la clasificación, los paquetes `scikeo.plot` `matplotlib` `matplotlib.pyplot` para las visualizaciones y el paquete `scikeo.writeRaster` para descargar el raster clasificado.  

Adicionalmente, como datos de entrada el código requiere de una **imagen satelital** del área de interés con las bandas e índices a usar y un dbf de las **áreas de entrenamiento**. Los datos utilizados pueden descargarse [aquí] (https://drive.google.com/drive/folders/13quvTij64_KZ-hOga1PRDX_q2uzfWyh1?usp=share_link) 


### *Créditos*
Este repositorio forma parte del curso de Análisis Espacial de la especialidad de [Geografía y Medio Ambiente de la Pontificia Universidad Católica del Perú] (https://www.pucp.edu.pe/carrera/geografia-y-medio-ambiente/)

### *Integrantes del Grupo*
- Flor Castillo
- Fabio García 
- Valeria Falla  