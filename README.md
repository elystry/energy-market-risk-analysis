# Automated Risk Analysis – Energy Retail Market (Gewerbekunden)

## Business Context (Energiewirtschaftlicher Hintergrund)
Ziel dieses Projekts war es, das unprofitable Portfolio (Negative Margen) im Gewerbekunden-Bereich (1.200 Industriekunden) zu identifizieren und für das Vertriebs-Controlling aufzubereiten.

## Methodik
* Systematische Formatfehler beim Import korrigiert und 40 fehlende Verbräuche ("Verbrauch_kWh") mittels mathematischer Interpolation (Spalten-Mittelwert) bereinigt, um das Gesamtvolumen nicht zu verzerren.
* Berechnung des Netto-Spreads ("Tarif_Cent_kWh" vs. "Netz_und_Einkauf_Cent_kWh") und Errechnung des monatlichen Deckungsbeitrags ("Marge_Euro") pro Lieferstelle.
* Automatisierte Erstellung eines Excel-Reports für das Vertriebs-Management, inkl. farblicher Alarmierung der Top-Verlustbringer für anstehende Portfolio-Bereinigungen oder Nachverhandlungen.

## Tech Stack
* Python
* Pandas
* NumPy
* Jupyter Notebook
* Excel Reporting
