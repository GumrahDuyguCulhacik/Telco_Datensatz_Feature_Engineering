# Projektziel
Ziel ist es, ein Machine-Learning-Modell zu entwickeln, das vorhersagen kann, welche Kunden das Unternehmen verlassen werden (Churn Prediction).

# Explorative Datenanalyse
Erste Analyse des Telco-Datensatzes zur Beschreibung der Merkmale und Datenstruktur

# Identifikation fehlender Werte
Imputation mittels verschiedener Methoden (z. B. Mittelwert, Modus, KNN)

# Ausreißeranalyse
Boxplot-basierte Prüfung auf Ausreißer

Ergebnis: Keine signifikanten Ausreißer im Datensatz festgestellt

# Feature Engineering & Preprocessing
Erstellung einer Kopie des bereinigten Datensatzes zur weiteren Verarbeitung

# Anwendung verschiedener Encoding-Methoden:
Label Encoding
One-Hot Encoding
Rare Encoding

# Anwendung verschiedener Standardisierungsverfahren:
Standard Scaling
Min-Max Scaling
Robust Scaling

Evaluation: Die Auswirkungen auf die Modellgüte (Accuracy Score) waren geringfügig

# Modellierung
Verwendung des RandomForestClassifier zur Modellierung der verschiedenen Versionen des Datensatzes
Vergleich der Modell-Performance: Keine signifikanten Unterschiede in der Accuracy
