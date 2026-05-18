# Automated Portfolio Risk Analysis

## Business Context

Ziel dieses Projekts ist es, ein unprofitables Gewerbekunden-Portfolio anhand negativer Margen zu identifizieren und für das Vertriebs- und Portfoliocontrolling aufzubereiten.

Analysiert werden 1.200 simulierte Gewerbekunden-Lieferstellen mit Verbrauchs-, Tarif- und Beschaffungskosteninformationen.

## Methodik

- Erstellung eines simulierten Gewerbekunden-Datensatzes mit 1.200 Lieferstellen
- Bereinigung systematischer Importfehler und Behandlung von 40 fehlenden Verbrauchswerten mittels Spaltenmittelwert
- Berechnung des Netto-Spreads je kWh sowie der monatlichen Marge in Euro pro Lieferstelle
- Identifikation und Sortierung aller Kunden mit negativer Marge
- Automatisierte Erstellung eines Excel-Reports für die Verlustkundenanalyse
- Visualisierung der Top-10-Verlustkunden
- Analyse der Verluste nach Branche und Monat
- Berechnung zentraler Kennzahlen wie Anzahl der Verlustkunden und gesamter Portfolioverlust

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Excel Reporting
