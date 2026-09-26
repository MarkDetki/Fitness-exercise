# Fitness Exercise

Ein Data-Science- und Data-Analytics-Projekt zur Analyse von Fitness- und Trainingsdaten mit Fokus auf Datenbereinigung, Explorative Datenanalyse, Feature Engineering und Modellierung.

## Überblick

Dieses Projekt untersucht die Beziehung zwischen Trainingsparametern wie Trainingsdauer, Puls, Maximalpuls und Kalorienverbrauch. Ziel ist es, Muster im Datensatz zu erkennen, die Qualität der Daten zu verbessern und eine modellbasierte Analyse zu entwickeln, die Einblicke in die Leistungs- und Energieausgaben von Trainingseinheiten liefert.

Die Analyse umfasst:
- Datenimport und erste Datenprüfung
- Explorative Datenanalyse (EDA)
- Bereinigung und Vorverarbeitung
- Feature Engineering
- Modelltraining und Evaluierung
- Export vorverarbeiteter und modellbereiter Datensätze

## Projektziel

Das Hauptziel des Projekts ist die Untersuchung, wie Faktoren wie:
- Trainingsdauer
- Puls
- Maximalpuls
- Kalorienverbrauch

mit einem Fitness- oder Trainingsprofil zusammenhängen. Damit eignet sich das Projekt gut für ein typisches Data-Science-Projekt, das von der Rohdatenanalyse bis zur Modellentwicklung reicht.

## Datensatz

Der Datensatz liegt im Ordner `data/` vor und enthält Informationen zu Fitness-Trainingssessions.

### Rohdaten
- Pfad: `data/raw/data.csv`
- Beispielspalten:
  - `Duration`
  - `Pulse`
  - `Maxpulse`
  - `Calories`

### Verarbeitete Daten
- Pfad: `data/processed/fitness_preprocessed.csv`
- Enthält bereinigte und vorverarbeitete Variablen sowie Kennzeichen für Ausreißer und Imputationen.

## Projektstruktur

```text
Fitness-exercise/
├── README.md
├── data/
│   ├── raw/
│   │   └── data.csv
│   └── processed/
│       └── fitness_preprocessed.csv
├── notebooks/
│   ├── data preparation/
│   │   └── data preparation.ipynb
│   ├── exploratory data analysis and preprocessing/
│   │   ├── exploratory data analysis and preprocessing.ipynb
│   │   └── fitness_model_ready.csv
│   ├── feature engineering/
│   │   └── feature engineering.ipynb
│   └── model training and evaluation/
│       └── model training and evaluation.ipynb
└── .git/
```

## Analyse-Workflow

1. Datenbeschaffung und erste Sichtung der Rohdaten
2. Bereinigung von fehlenden Werten und Identifikation von Ausreißern
3. Explorative Datenanalyse mit visuellen und statistischen Methoden
4. Feature Engineering zur Verbesserung der Modellqualität
5. Aufbereitung des Datensatzes für maschinelles Lernen
6. Modelltraining und Bewertung der Ergebnisse
7. Speicherung der verarbeiteten Daten als modellbereiter Datensatz

## Verwendete Technologien

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebooks

## Typische Fragen, die dieses Projekt beantwortet

- Welche Zusammenhänge bestehen zwischen Trainingsdauer, Puls und Kalorienverbrauch?
- Gibt es Ausreißer oder unvollständige Werte im Datensatz?
- Wie beeinflussen Merkmale den Energieverbrauch während eines Trainings?
- Welche Vorverarbeitungs- und Feature-Engineering-Schritte verbessern die Datenqualität?
- Wie lässt sich der Datensatz für maschinelles Lernen vorbereiten?

## Ablauf im Projekt

- Datenaufbereitung: Qualität der Datensätze prüfen und bereinigen
- EDA: Verteilungen, Korrelationen und Muster aufdecken
- Preprocessing: Standardisierung, Fehlerszenarien und Datenbereinigung
- Feature Engineering: Derivation neuer relevanter Merkmale
- Modellierung: Erstellung eines predictiven Datenszenarios
- Evaluation: Bewertung der Modellqualität und Modellleistung