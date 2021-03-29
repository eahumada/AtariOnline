# LOGO SPA

Atari XL Logo Espanol Online (SIN AUDIO)

Comandos de Ejemplo:

PRIMITIVAS

Muestra todas los comandos soportados por logo

AV :pasos

Avanza la tortuga "n" pasos

DE :grados

Gira la tortuga "n" grados.

Ejemplo:
CR MENOS :N
- 138
FIN

CR AZUL
PONNL 1 PONLC 1 82
HAZ "X -138
HAZ "Y 31
PONR 90
REPITE 90 [SL PONXY LIS :X :Y LA AV 90 HAZ "Y :Y + 1]



HOW-TO:

# 1. Agregar un programa ATR al emular.

Por ejemplo, para agregar un programa ATR al emulador:

CAT LOGOSPA.ATR >> A8E.data

Luego agregar las siguientes lineas en A8E.js :

'''
// Linea 247
new DataRequest(7310944, 7444080, 0, 0).open('GET', '/data/logospa.atr');
'''

'''
// Linea 387
DataRequest.prototype.requests["/data/logospa.atr"].onload();
'''

Hay que ir incrementadnos los números de bytes según el peso del archivo ATR.

