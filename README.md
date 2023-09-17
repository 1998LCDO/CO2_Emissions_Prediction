Predict CO2 Emissions in Rwanda

Intengrantes: 


-Laura Cristina Diaz Osorio.

C.C: 1018351214

Programa de matricula: Ingenieria Industrial (virtual)

-Juan Felipe ...

C.c: 

Programa de matricula: Ingenieria de sistemas 


los datos fueron tomados de kaggle competitions, para visualizarlos archivos, se va a cargar los datos desde Kaggle directamente en Google Colab y luego visualizarlos con Pandas:
from google.colab import files
files.upload()

-Primero se  Instala la API de Kaggle.
!pip install kaggle

-Se mueve el archivo JSON de autenticación a la ubicación correcta.
!mkdir -p ~/.kaggle
!mv kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json

-Se descargan los datos de la competición "Playground Series - S3E20"
!kaggle competitions download -c playground-series-s3e20

-Procedemos a descomprimir el archivo zip descargado.
!unzip playground-series-s3e20.zip

Y por ultimo se lee el archivo de entrenamiento en un DataFrame de Pandas, para proceder con la visualizacion de los datos.
import pandas as pd
df = pd.read_csv('train.csv')
df.head()
