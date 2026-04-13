# 🌍 World Happiness Indikatoren

Ein umfassendes Datenanalyseprojekt, das den World Happiness Report-Datensatz erforscht und interaktive Visualisierungen sowie Einblicke bietet, was Länder glücklich macht.

## 📋 Projektübersicht

Dieses Projekt analysiert globale Glücklichkeitskennzahlen durch Untersuchung von Korrelationen zwischen Glücklichkeitswerten und verschiedenen sozioökonomischen Faktoren wie:
- BIP pro Kopf
- Lebenserwartung
- Soziale Unterstützung
- Freiheit
- Großzügigkeit
- Abwesenheit von Korruption

## 📁 Projektstruktur

```
HappinesIndicators/
├── README.md                          # Diese Datei
├── Datensatz/                         # Datenanalyse
│   ├── 2015.csv                       # World Happiness Daten für 2015
│   └── world_happiness_analyse.ipynb  # Interaktives Jupyter Notebook
└── Cleaning/                          # Datenbereinigung
    └── 2015.csv                       # Bereinigte/verarbeitete Daten
```

## 🚀 Erste Schritte

### Voraussetzungen
- Python 3.7+
- Jupyter Notebook oder JupyterLab

### Setup & Installation

1. **Repository klonen:**
   ```bash
   git clone <repository-url>
   cd HappinesIndicators
   ```

2. **Erforderliche Abhängigkeiten installieren:**
   ```bash
   pip install jupyter pandas plotly
   ```

3. **Jupyter Notebook starten:**
   ```bash
   jupyter notebook Datensatz/world_happiness_analyse.ipynb
   ```

4. **Alle Zellen ausführen** mit `Shift + Enter`, um die Analyse durchzuführen und interaktive Visualisierungen anzuzeigen

## 📊 Wichtigste Analysen & Visualisierungen

Das Notebook enthält mehrere interaktive Plotly-Visualisierungen:

1. **Ranking-Visualisierung** - Top 15 & Bottom 15 Länder nach Glücklichkeitswert
2. **BIP vs. Glücklichkeits-Korrelation** - Macht Geld glücklich?
   - Streudiagramm mit Trendlinie
   - Blasengröße stellt Lebenserwartung dar
3. **Korrelations-Heatmap** - Identifiziert Beziehungen zwischen allen Glücklichkeitsfaktoren
4. **Regionale Vergleiche** - Geografische Muster in Glücklichkeitskennzahlen

## 📈 Datenquelle

- **Quelle:** [Kaggle – World Happiness Report](https://www.kaggle.com/datasets/unsdsn/world-happiness)
- **Abdeckung:** Mehrjährige Daten (2015 und darüber hinaus)
- **Kennzahlen:** Umfassende sozioökonomische Indikatoren für 160+ Länder

## 🔍 Verwendung

1. Öffnen Sie das Jupyter Notebook im Ordner `Datensatz/`
2. Platzieren Sie Ihre CSV-Datendatei (z.B. `2015.csv`) im selben Verzeichnis
3. Führen Sie Zellen der Reihe nach aus, um:
   - Die Daten zu laden und zu erkunden
   - Interaktive Visualisierungen zu generieren
   - Korrelationen zwischen Glücklichkeitsfaktoren zu analysieren

## 🛠️ Anpassung

- **Datensätze wechseln:** Ersetzen Sie den CSV-Dateipfad im Notebook
- **Visualisierungen anpassen:** Ändern Sie Plotly-Parameter in den Code-Zellen
- **Neue Analysen hinzufügen:** Erweitern Sie bestehende Zellen oder erstellen Sie neue

## 📝 Hinweise

- Die Analyse wird in Deutsch in den Notebook-Kommentaren durchgeführt
- Datenbereinigungsverfahren sind im Ordner `Cleaning/` verfügbar
- Interaktive Diagramme ermöglichen Hover-Informationen, Zoomen und Filtern
