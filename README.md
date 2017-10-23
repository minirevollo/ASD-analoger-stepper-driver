##  ASD - Analoger Stepper Driver  ##

Der analoge Stepper Driver dient dazu einen Stepper Motor ohne Microcontroller zu bewegen.... analog durch Drehung.

... aus der Serie: braucht kein Mensch, wollte ich aber unbedingt bauen.
![](https://github.com/minirevollo/ASD-analoger-stepper-driver/blob/master/IMG_20171012_211659.jpg)


# Design #

3D Design mit Google SketchUP. Platinendesign mit Inkscape.
![](https://github.com/minirevollo/ASD-analoger-stepper-driver/blob/master/ADS%20Analoger%20Stepper%20Driver%201.jpg)
# Produktion #

3D Druck auf einem Craftbot.

Platinenfräsung mit einer Othermill

Endmontage im www.erfindergarden.de

# Funktion #

Über die Kugelkontakte werden die beiden Spulen des Steppermotors mit der Platine verbunden. Folgendes Schema wird dabei verwendet:

![](https://github.com/minirevollo/ASD-analoger-stepper-driver/blob/master/ASD%20Ansteuerung.png)

Die Äußere Bahn hat Kontakt zum Ground der Stromquelle und die innere Bahn hat Kontakt zum VCC. Zwischen diesen beiden dauerhaft kontaktierten Bahnen verläuft die Abtastung. Abwechselnd GND - Isolierabstand (rot) - VCC.

![](https://github.com/minirevollo/ASD-analoger-stepper-driver/blob/master/ASD%20AnalogerStepperDriver.svg)

