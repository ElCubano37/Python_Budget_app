# Python_Budget_app
Lern Projekt für mich selber


Datei Struktur:

finance_manager/
│
├── finance_manager/          # Hauptpaket (Python-Logik)
│   ├── __init__.py
│   ├── main.py               # Einstiegspunkt (CLI oder GUI Starter)
│   ├── data/                 # Datenbank oder CSV-Dateien
│   │   └── transactions.db
│   ├── models/               # Klassen für Einnahmen, Ausgaben, Kategorien
│   │   └── transaction.py
│   ├── services/             # Logik: Berechnungen, Reports
│   │   └── report_service.py
│   ├── utils/                # Hilfsfunktionen (z. B. Dateihandling)
│   │   └── file_handler.py
│   └── visualizations/       # Diagramme & Plots
│       └── charts.py
│
├── tests/                    # Unit Tests
│   └── test_transaction.py
│
├── requirements.txt          # Abhängigkeiten
├── pyproject.toml            # falls du Poetry nutzen willst
├── README.md                 # Projektdokumentation
└── .gitignore
