# Fernbedienung
Eine Infrarotfernbedienung zur Ansteuerung von Arduino Mikrocontrollern verwenden.

Mit Hilfe eines Infrarotempfängers kann das Arduinoboard die Befehle einer Infrarotfernbedienung auswerten. Die Daten werden dabei in Form von Infrarotlicht von der Fernbedienung zum Empfänger gesendet. Da unser Auge dieses Licht nicht wahrnehmen kann, können wir dieses Licht nicht sehen. Mit einem kleinen Trick kann man jedoch testen, ob bspw. eine Fernbedienung ein Infrarotsignal sendet. Dazu nimmt man eine Digitalkamera (zum Beispiel die vom Smartphone) und betrachtet über das Display die Infrarotdiode. Wenn nun die Fernbedienung betätigt wird, kann man die Infrarotdiode leuchten sehen. Das liegt daran, dass die Sensoren von Digitalkameras das Infrarotlicht wahrnehmen und darstellen können. Das Licht flackert leicht, da die Infrarotdiode sehr schnell an- und aus geht. Dahinter verbirgt sich ein ganz bestimmter Rhythmus, anhand dessen der Infrarotempfänger später auswerten kann, welche Taste an der Fernbedienung gedrückt wurde.

Material: Arduino / Breadboard / Kabel / Infrarotsensor VS1838B / Infrarotfernbedienung

Pin S – Pin D11
Mittlerer Pin – 5V
Pin –  –> GND

Für die Programmierung wird die Library „IRremote“ von Ken Shirriff in der Version 2.2.3 benötigt. Die passende Version muss im Bibliotheksverwalter vor der Installation ausgewählt werden, da ansonsten die aktuellste Version installiert wird. Die Befehle in unserer Anleitung basieren jedoch auf die Version 2.2.3. Die Programmbibliothek kann im Bibliotheksverwalter mit dem Suchbegriff „irremote“ gefunden und installiert werden.

Eine Anleitung zur Installation einer Bibliothek über den Bibliotheksverwalter befindet sich im Theorieteil zu unseren Anleitungen. Dieser Sketch ist eine leichte Abwandlung des Sketches „IRrecvDemo“, welcher sich nach Installation der Library in der Arduino Software unter den Beispielen finden lässt.


Weitere Infos unter: https://funduino.de/
