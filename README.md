# 01-App_Diccionario


Esta app muestra el significado de la palabra que ingresemos, no importa si escribimos en mayúsculas o minúsculas el .lower se encarga de transformar todo en minúsculas, si colocamos una frase mal escrita hará una predicción gracias a una librería estándar que ocuparemos llamada Difflib

Ejemplo
import difflib from difflib
import SequenceMatcher

SecuenceMatcher(None,"rainn","rain").ratio() 0.8888888888888888

Como resultado nos muestra un número que representa la similitud en proporción de 0 a 1 Lo que necesitamos ahora es comparar todo nuestro diccionario y para esto usaremos otra función llamada get_close_matches
