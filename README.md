#Binary Classification of Machine Failures
Nombre: Laura Cristina Diaz Osorio.
C.C: 1018351214
Programa de matricula: Ingenieria Industrial (virtual)
los datos fueron tomados de kaggle competitions, se creo una copia en drive a la cual se accede desde colab con el sig codigo:

from google.colab import drive
drive.mount('/content/drive')
import pandas as pd
from google.colab import drive
ruta= '/content/drive/My Drive/Entrega 1 AI/train.csv'

df = pd.read_csv(ruta)
Primero se da acceso al drive con el codigo import drive, seguido se importa la libreria pandas
la cual nos va a permitir leer a el archivo con el dataframe para su uso.

link DataFrame:https://www.kaggle.com/competitions/playground-series-s3e17/overview
