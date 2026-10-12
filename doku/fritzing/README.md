# Fritzing-Grafiken

Die Breadboard-Grafiken für die Anschlussfolie wurden mit Fritzing exportiert
und anschließend in der LaTeX-Folie beschriftet und verdrahtet.

- `esp32-breadboard.svg` / `.pdf`: ESP32S-HiLetgo, Bauteilautor Stephen Lilley
- `dht11-module-breadboard.svg` / `.pdf`: KY-015 DHT11-Modul,
  Bauteilautor arduinomodules.info

Ausgangspunkt war das Fritzing-Projekt
[`ESP32S_DHT11.fzz`](https://github.com/brucetsao/Fritzing/blob/master/%E9%9B%BB%E8%B7%AF%E8%A8%AD%E8%A8%88/ESP32/ESP32S_DHT11.fzz).
Der Export erfolgte mit dem offiziellen Fritzing-Entwicklungsbuild `CD-625`
aus den [Fritzing-Releases](https://github.com/fritzing/fritzing-app/releases).

Workshop-Belegung:

| ESP32 | DHT11-Modul |
|---|---|
| 3V3 | + / VCC |
| GPIO4 | S / DATA |
| GND | - / GND |

Das verwendete DHT11-Modul besitzt den Pull-up-Widerstand bereits auf der
Sensorplatine.
