Der Shot Dispenser Soll eine Zusammensetzung an Objekten sein die Dan Zusammen die Funktion haben:
## Funktionen:
#### Primär:
- Abstellplätze für die Shotgläser zu bieten
- Automatische Befüllung von Leeren Shotgläsern
#### Sekundär (Funktionen zum Ermöglichen von Primär):
- Erkennung von Besetzten Plätzen + ob diese Voll/leer sind
- Bewegung des Dispenser zu Erkannten Gläsern
- Flüssigkeitspumpen für den Alkohol 
#### Teritär (Funktionen zur Wartung/Instandhaltung)
- Flüssigkeitsschutz für E Komponenten
- Einfache Zersetzung und zusammenfügung für Reinigung und Wartung
- Pumpen Durchspühlungssystem

### Limitationen:
- Kosten
	->   Sparsammkeit Für Füllung der Gedruckten Komponenten
	->   Mögliche Nutzung von Möglichst wenig E Komponenten
- Komponenten Größe von Maximal 250x250x250 mm (Druck)
- Steuerung Erfolgt Durch ein Arduino Uno + Möglichem Shield
### Komponenten:
- 1x Stepper Motor 4xPins
- 1x Schalter  
- 1x Touch Button 1x pin
- 1x Knopf 1x pin
- 1x Arduino Uno/esp32
- 1x Power Supply/Akku
- min: 1x Fluid Pump max:4x Fluid Pump ?xpins
- Schläuche
- 12x Sensorik für Gläser 12xpins
- Kabel/Anschlüsse für Controller
#### Gedruckte Teile: 
- Bodenplatte
- Elektonik Gehäuse
- Drehgestell
- Drehturm + Dispenser

### Funktionen der Komponenten.
- Der Stepper Motor Wird Den Drehturm ansteuern und Somit den Dispenser zum Shotglas bewegen welches Befüllt werden Soll
- Der Schalter wird da sein Um die Spannungs zufuhr zu Schalten.
- Der Touch button wird benutzt um den Füll vorgang zu Starten.
- Der Knopf wird benötigt um den Stepper Zu Kalibrieren 
- Der Arduino/esp wird Die Ganzen Komponenten Kalibrieren
- Die Powersupply wird den Arduino Spannung Liefern.
- Die Fluid pump wird den Alkohol von den Flaschen in die Gläser befördern.
	Möglichkeit auf mehrere für das Mischen Verschiedener Getränke
- Schläuche die Die Flüssigkeit Transportieren
- Sensorik wird die Anwesenheit und Füllzustand der Gläser Kontrollieren
- Anschlüsse fürs  verbinden der Komponente mit den Kontroller

- Bodenplatte wo die Sensorik steckt und auch Abstellplatz für die Gläser dient.
- Das Gehäuse um die Elektronik zu Schützen vor zb Spritzwasser/Dreck/Gegenprall.
- Das Drehgestell Gibt die Drehbewegung an den Drehturm weiter und Fixiert diesen.
- Der Drehturm beinhält den Dispenser (Endziel der Schläuche) und Führt diesen zu der Gewünschten Position.


