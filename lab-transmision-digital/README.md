# Laboratorio de Transmisión digital

Clase teórico-práctica de los fundamentos de la transmisión digital

## Probar online

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/brivadeneira/appmode/master?filepath=LaboratorioTransmisionDigital.ipynb)

Click para probar en vivo sin instalar nada, esto te direcciona a una *"app"*.

Incluye:

* Apunte de cátedra.
* Presentación.
* Recursos didácticos.

![](img/muestreo.gif)

![](img/cuantificacion.gif)

Se exponen y simulan conceptos de transmisión digital:

* Muestreo
* Cuantización
* Modulación por pulsos
  * PAM
  * PDM/PWM
  * PPM
  * PCM

> Clase impartida en la cátedra de Introducción a la Ing. en Telecomunicaciones I de la Fac. de Ingeniería en la Universidad Nacional de Río Cuarto.

## Instalación


```
pip install appmode
jupyter nbextension     enable --py --sys-prefix appmode
jupyter serverextension enable --py --sys-prefix appmode
```
