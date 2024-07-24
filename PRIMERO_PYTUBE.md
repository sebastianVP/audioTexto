# PRIMER PASO- CORRIGIENDO LIBRERIA pytube
Nuestra referencia es el siguiente link:

[Link de referencia](https://www.youtube.com/watch?v=Or7aNnrLF6s)

Vamos a tratar de probar la libreria pytube de 2 formas:
1. La primera sera añadiendo unas lineas de código en el script de pruebas. Es decir instalemos primero pytube y luego tratemos de probar los programas añadiendo estas lineas de código.
   
```
from pytube. innertube import _default_clients

_default_clients[ "ANDROID"][ "context"]["client"]["clientVersion"] = "19.08.35"
_default_clients["IOS"]["context"]["client"]["clientVersion"] = "19.08.35"
_default_clients[ "ANDROID_EMBED"][ "context"][ "client"]["clientVersion"] = "19.08.35"
_default_clients[ "IOS_EMBED"][ "context"]["client"]["clientVersion"] = "19.08.35"
_default_clients["IOS_MUSIC"][ "context"]["client"]["clientVersion"] = "6.41"
_default_clients[ "ANDROID_MUSIC"] = _default_clients[ "ANDROID_CREATOR" ]
```
Copiaremos el link de del colab para tener un registro de pruebas.

https://colab.research.google.com/drive/1ZOOxoPQsUDXlixW4-yOR8A5cCYx2VCw1?usp=sharing

2. Este paso es el que hemos probado y verificado. Para esto se requiere descargar un repositorio, ojo en esta instalacion vamos a trabajar con un repositorio github y un cuaderno de colab, para esto:

https://colab.research.google.com/drive/1vjjBWtfy_1GnPUhUFpF4zTXQts06DksU#scrollTo=X5GQ3oUOOX_u

3. En el 3er cuaderno tenemos las conclusiones de uso, para una solucion completa se recomienda la instalacion del repositorio y la modificacion del cipher.py y las lineas del innertube.

https://colab.research.google.com/drive/1NCjVJYtplK6366XeHsCpaoOtoCgTkSJu?usp=sharing

