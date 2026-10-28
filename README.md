# 📡 Arduino & Python Live Radar

Ein interaktives 2D-Radar-System, das mit einem Ultraschallsensor (HC-SR04) und einem Servo-Motor die Umgebung scannt (Sektor 10° bis 170°) und die Live-Daten über eine serielle Schnittstelle in Echtzeit an ein Python-Skript (Matplotlib) überträgt.

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Arduino](https://img.shields.io/badge/Arduino-C++-teal?style=flat&logo=arduino)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange?style=flat)

---

##  Features
- **Echtzeit-Visualisierung:** Polares Koordinatensystem (Radar-Ansicht) mit anpassbarem Sektor (10° bis 170°).
- **Farbverlauf (Color-Coding):** Hindernisse werden je nach Entfernung eingefärbt (näher = intensiver).
- **Live-Sweep-Linie:** Ein digitaler Radarstrahl zeigt die aktuelle Blickrichtung des Sensors an.
- **Performance-Optimiert:** Fließende Darstellung (~25 FPS) ohne Ruckeln oder Einfrieren dank optimierter Canvas-Updates.
- **Automatische Bereinigung:** Punkte werden beim erneuten Überfahren überschrieben, um "Geisterpunkte" zu vermeiden.

---

##  Benötigte Hardware
- Arduino (z. B. Uno, Nano oder ESP32)
- Ultraschallsensor **HC-SR04**
- Servo-Motor (z. B. SG90)
- Jumper-Kabel & Breadboard

## Kommende Verbesserungen
- **3D gedrucktes Case für den Ultraschall
- **Besseres Kabelmenegement
- **Dritte Dimension
