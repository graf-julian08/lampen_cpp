# Lampen C++ Steuerungssystem

## Übersicht
Das Projekt **lampen_cpp** ist ein in C++ entwickeltes Steuerungssystem für Beleuchtungselemente mit Anbindung an Sprachmodule und Dauerbetrieb im Kiosk-Modus.

## Projektstruktur & Architektur
- `CMakeLists.txt`: Konfigurationsdatei für das CMake-Build-System.
- `src/`: C++ Quellcode für Systemsteuerung und Peripherie-Anbindung.
- `start_system.sh`: Startskript zur Systeminitialisierung.

## Hauptfunktionalitäten
- **High-Performance C++**: Hardwarenahe Ausführung für geringe Latenzen.
- **Kiosk-Betrieb**: Ausgelegt für den kontinuierlichen Hintergrundbetrieb.
- **Schnittstellen-Anbindung**: Auswertung von Eingabesignalen zur Lampensteuerung.

## Ausführung & Nutzung
Die Kompilierung erfolgt über CMake mit `cmake -B build && cmake --build build`. Das Gesamtsystem kann über `./start_system.sh` gestartet werden.

## Lizenz
Dieses Projekt steht unter der MIT-Lizenz.
