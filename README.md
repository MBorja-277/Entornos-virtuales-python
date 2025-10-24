# Entornos-virtuales-python
Se presentaron problemas en una de las instalaciones de las librerias concretamente la libreria dash, para solucionar ese error fue necesario hacer una instalación de la libreria aparte con: !pip install dash. Una vez instalada la libreria ya podríamos usar el código sin problema, después comprobamos la instalación de las librerias, import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import plotly.express as px
import bokeh
import dash

print("Confirmaci´on: Todas las bibliotecas se importaron correctamente.")

 # Verificaci´on adicional para Colab para confirmar la ruta
if 'google.colab' in sys.modules:
 print(f"\nVerificando ruta de Pandas en Colab...")
 print(pandas.__file__)

Ya por ultimo comprobamos que librerias fueron instaladas con el siguiente código: !pip freeze
