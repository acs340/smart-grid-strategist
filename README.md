# Smart Grid Strategist (SGS)

## Beschreibung

SGS (Smart Grid Strategist) ist eine Anwendung, die im Rahmen der Bachelorarbeit mit dem Titel "Effizientes Energiemanagement in deutschen Haushalten: Potenzialanalyse durch Integration von Smart-Meter-Daten und maschinellem Lernen im Kontext dynamischer Tarifmodelle" entwickelt wurde. Diese Anwendung bietet einen umfassenden Überblick über den Stromverbrauch in Haushalten und ermöglicht es den Benutzern, ihr individuelles Stromverbrauchsverhalten zu verstehen und Einspar- und Optimierungsmöglichkeiten zu identifizieren.

<h1 align="center">
  <img src="./Bilder/App-Module.png" alt="App-Module.png">
</h1>

## Eigenschaften

- **Simulator:** Die Anwendung verfügt über einen Simulator, der drei Kategorien von Endverbrauchern umfasst: Consumer, Prosumer und Flexumer. Jede Kategorie hat spezifische Merkmale, die es ermöglichen, ihr Verhalten in verschiedenen Szenarien zu simulieren.
- **Analysegrafiken:** Die Ergebnisse der Simulationen werden in klaren und visuellen Grafiken präsentiert, um die Analyse der komplexen Beziehungen zwischen den Variablen zu erleichtern.
- **Machine Learning-Vorhersagen:** Es werden maschinelles Lernen verwendet, um das Verhalten der simulierten Variablen vorherzusagen und mögliche Trends für das laufende Jahr aufzuzeigen.
## Verwendung

**1. Simulator:** Wählen Sie den Typ des Endverbrauchers aus und passen Sie die Parameter bei Bedarf an, wie z. B. den jährlichen Stromverbrauch, den aktuellen Tarif, die Kapazität der Solarenergieerzeugung usw. Klicken Sie dann auf die Schaltfläche "Simulieren", um die Ergebnisse anzuzeigen.  
**2. Analyse:** Erkunden Sie die generierten Grafiken, um den Stromverbrauch, die Stromerzeugung, die Energiepreise und mehr besser zu verstehen.
## Installation

1. Klone dieses Repository: `git clone https://github.com/acs340/smart-grid-strategist.git`
2. Installiere die Abhängigkeiten: `pip install -r requirements.txt`
3. Starte die Anwendung: `python app.py`
## Verwendete Technologien

- Python
- Dash (Framework zur Erstellung interaktiver Web-Benutzeroberflächen)
- Plotly (Bibliothek zur Erstellung interaktiver Grafiken)
## Autor

Mario Emanuel Fernández

## Lizenz

Dieses Projekt steht unter der `AFL-3.0`-Lizenz.
