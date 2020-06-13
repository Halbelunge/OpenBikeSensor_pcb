# OpenBikeSensor_pcb

## Versionen

Aktuelle Version ist das "OpenBikeSensor_pcb_flippedPower_b.pro".

Aktueller Branch: "Mit_Verpolschutz"

Master-Branch war der ausgehende. Danach wurde die 2x15 Federleistenversion davon abgeleitet. Diese hat die Möglichkeit gewinkelte THT-Buchsenleiste als SMD-Leiste zu nutzen (für den Notfall). Darauf aufbauend wurde im default-Branch dann ein Verpolungsschutz für den Akku hinzugefügt.
## Bugs / Todo:

- ~~Maße des MT3608 noch nicht final. Lochabstände nicht aus Abbildungen sicher erkennbar. SEPIC statt Buck nötig! Daher LM2596 daher nicht einfach verwendbar!~~
- ~~LM2596 Board noch mit im PCB. Wird erst entfernt wenn Maße des MT3608 final~~
- LM285 sitzt "bescheiden" vielleicht noch einen besseren Platz finden

Weitere Beschreibung folgt demnächst.

## Gerber
Es gibt 2 Gerberfiles. Das mit dem Zusatz JLC besitzt den Marker für JLC damit diese ihren Produktionscode unter dem SEPIC Wandler platzieren. Dies ist für die Funktion des Boards natürlich nicht wichtig. Option muss bei JLC seit neustem in der Bestellung mit angegeben werden.


## 3D Modelle für Kicad und Gehäuse

Link zu den 3D Modellen für das pcb: https://github.com/Halbelunge/OpenBikeSensor_pcb_ext3Dmodels.git

Link zum Gehäuse: https://github.com/Halbelunge/OpenBikeSensor_pcb_case.git

Display Gehäuse von hier übernehmen: https://github.com/Friends-of-OpenBikeSensor/OpenBikeSensor3dPrintableCase
