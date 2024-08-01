# ML-House-Price-Prediction
In diesem Projekt wurde ein maschinelles Lernmodell entwickelt, um Immobilienpreise präzise vorherzusagen. Es umfasst umfassende Datenanalysen, Feature Engineering und die Anwendung mehrerer Regressionsmodelle zur Evaluierung der Leistung. 
Das Hauptziel besteht darin, ein maschinelles Lernmodell zu erstellen, das Hauspreise mit minimalem Fehler vorhersagt. Die Vorhersagen sollen anschließend auf der Plattform Kaggle hochgeladen werden, um an einem Wettbewerb teilzunehmen.

https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview/evaluation



### Schritte des Projekts:

#### 1. **Explorative Datenanalyse (EDA):**
   - **Daten Einlesen:** Die Trainings- und Testdaten werden eingelesen und zusammengeführt.
   - **Allgemeine Datenübersicht:** Überblick über die Form, Datentypen, fehlende Werte und statistische Kennzahlen der Daten.
   - **Kategorische und numerische Variablen:** Analyse der Verteilung und der Bedeutung von kategorischen und numerischen Variablen.
   - **Zielvariable:** Untersuchung der Verteilung der Zielvariable (Hauspreise) und ihrer Beziehung zu anderen Variablen.
   - **Korrelation:** Analyse der Korrelationen zwischen numerischen Variablen und Erstellung einer Korrelationsmatrix.

#### 2. **Feature Engineering:**
   - **Umgang mit Ausreißern:** Identifikation und Behandlung von Ausreißern, z.B. durch Begrenzung auf den Bereich des Interquartils.
   - **Fehlende Werte:** Analyse und Imputation fehlender Werte, entweder durch Median, Mittelwert oder spezifische Werte für kategorische Variablen.
   - **Rare Value Analysis:** Identifikation und Kodierung seltener Kategorien.
   - **Erstellung neuer Features:** Generierung neuer Merkmale, die potenziell wertvolle Informationen für das Modell enthalten könnten.

#### 3. **Datenvorverarbeitung:**
   - **Kodierung von Kategorien:** Anwendung von Label-Encoding für binäre Kategorien und One-Hot-Encoding für andere kategorische Variablen.
   - **Datenaufteilung:** Trennung der Daten in Trainings- und Testsets.

#### 4. **Modellbildung:**
   - **Modelltraining:** Verschiedene Regressionsmodelle werden trainiert, darunter:
     - **Lineare Regression (LR)**
     - **K-Nearest Neighbors (KNN)**
     - **Entscheidungsbaumregression (CART)**
     - **Random Forest (RF)**
     - **Gradient Boosting (GBM)**
     - **XGBoost**
     - **LightGBM**
   - **Modellbewertung:** Evaluierung der Modelle anhand der Root Mean Squared Error (RMSE) auf Basis der Kreuzvalidierung.

### Besondere Punkte:

- **Feature Engineering:** Der Schritt der Feature-Erstellung umfasst sowohl einfache Merkmale wie die Kombination von verschiedenen Flächen als auch komplexere Features wie die Interaktion zwischen verschiedenen Merkmalen.
- **Datenbereinigung:** Fehlende Werte und Ausreißer werden systematisch behandelt, um die Qualität der Daten für die Modellierung zu verbessern.
- **Modellvergleich:** Verschiedene Algorithmen werden getestet und deren Leistung verglichen, um das beste Modell für die Vorhersage der Hauspreise zu bestimmen.

### Ziel des Projekts:

Das finale Ziel ist es, ein Modell zu entwickeln, das auf den Testdaten von Kaggle angewendet wird, um die Hauspreise mit möglichst hoher Genauigkeit vorherzusagen. Die Ergebnisse werden auf Kaggle hochgeladen, um sich im Wettbewerb zu messen.
Das Projekt deckt alle wesentlichen Schritte von der Datenvorbereitung bis zur Modellbewertung ab, was es zu einer umfassenden Übung im Bereich der Datenwissenschaft und des maschinellen Lernens macht.
