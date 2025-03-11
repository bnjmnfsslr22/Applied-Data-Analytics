# Applied-Data-Analytics

## Inhaltsverzeichnis:

- [1. Python Basics](#python-1---basics)
- [2. Daten einlesen und indexieren](#python-2---daten-einlesen-und-indexieren)
- [3. Grundlagen der Datenaufbereitung](#python-3---datenaufbereitung)
- [4. Datenanalyse und Zeitreihen](#python-4---zeitreihenanalyse-am-beispiel-von-stromverbrauchs--und-produktionsdaten)
- [5. Entscheidungsbaum](#python-5---entscheidungsbaum-am-beispiel-von-prognosemodell-für-den-energieverbrauch)
- [6. Neuronales Netz](#python-6----neuronales-netz-zur-vorhersage-von-energieverbrauchsdaten)

---

## Python 1 - Basics

**Beschreibung:** Dieses Notebook deckt grundlegende Aspekte von Jupyter Notebooks und Python ab.

- **Jupyter Notebook Zellen:** Das Ausführen von Zellen und die Unterscheidung zwischen Text und Code.
- **Die Print Funktion:** Demonstration der print-Funktion und String-Interpolation in Python.
- **Kommentare in Python:** Einzeilige und mehrzeilige Kommentare.
- **Operatoren und if/else Abfragen:** Einführung in Bedingungsanweisungen und Logik.
- **Funktionen:** Erstellen und Verwenden benutzerdefinierter Funktionen.
- **Bibliotheken:** Einbindung von Bibliotheken und Zugriff auf ihre Methoden.

---

## Python 2 - Daten einlesen und indexieren

**Beschreibung:** In diesem Notebook werde ich fortgeschrittene Grundlagen behandeln, insbesondere die Datenverarbeitung und -manipulation mit Pandas.

- **Bibliothek pandas einbinden:** Einbindung der Bibliothek und erste Schritte.
- **Daten einlesen:** Demonstration des Einlesens von CSV-Dateien mit pandas.
- **Erste Datenexploration:** Anzeigen von Kopf- und Fußzeilen, zufällige Datensatzstichproben und Untersuchung der Datentypen.
- **Indexierung:** Greifen Sie mit Zeilen- und Spaltennummer und mit dem Zeitstempel auf den Datensatz zu.
- **Zeitstempel als Index:** Verwendung von Zeitstempeln als Indizes für effizientes Indexieren und Filtern von Daten.

---

## Python 3 - Datenaufbereitung

**Beschreibung:** Dieses Notebook veranschaulicht die Datenaufbereitung in Python, insbesondere:
- Zusammenführen von Daten aus zwei CSV-Dateien.
- Umgang mit fehlenden Werten (NaN).
- Angleichen von Zeitreihen unterschiedlicher Frequenzen auf eine gemeinsame Frequenz.

  - **Bibliotheken Importieren:** Einführung in verschiedene Bibliotheken wie pandas, numpy, matplotlib und seaborn. Einbindung von Google Colab für Laufwerkszugriff.
  - **Daten Einlesen:** Daten aus zwei unterschiedlichen Quellen lesen und die Dimensionen der Datensätze überprüfen.
  - **Umgang mit fehlenden Werten:** Untersuchung auf NaNs und verschiedene Methoden zur Behandlung dieser Werte: Entfernen und Interpolieren (linear und quadratisch).
  - **Zeitstempel als Index setzen:** Umwandlung des Zeitstempels in ein datetime-Format und Setzen dieses als Index für effizientes Arbeiten mit den Daten.
  - **Zusammenführen von Datensätzen:** Verschiedene Ansätze zur Vereinigung zweier Datensätze mit unterschiedlichen Frequenzen: Verwendung gemeinsamer Indizes oder Resampling.

---

## Python 4 - Zeitreihenanalyse am Beispiel von Stromverbrauchs- und Produktionsdaten

**Beschreibung:** Dieses Notebook konzentriert sich auf die Analyse von Zeitreihen, wobei Stromverbrauchs- und Produktionsdaten als Fallbeispiel dienen.

- **Datenimport und -vorbereitung:** 
  - Einlesen der Daten über pandas aus Google Drive.
  - Überprüfung und Handhabung fehlender Werte (NaNs).
  - Transformation der Datumsspalte zu einem Zeitstempel und Festlegung als Index.
  - Ableitung neuer Features wie Jahr, Monat und Wochentag.

- **Statistische Analyse:** 
  - Erzeugung einer Korrelationsmatrix und ihre visuelle Darstellung.
  - Exploration der Daten anhand von bestimmten Zeitstempeln und Zeiträumen.

- **Visualisierung:** 
  - Verwendung von matplotlib und seaborn zur Erstellung verschiedener Diagrammtypen: Linien-, Balken- und Heatmap-Diagramme.

---

## Python 5 - Entscheidungsbaum am Beispiel von Prognosemodell für den Energieverbrauch

**Beschreibung:** Dieses Notebook erklärt die Verwendung von Entscheidungsbäumen zur Vorhersage des Energieverbrauchs.

- **Datenpräparation:** 
  - Einlesen der Daten, Prüfen auf NaNs und Umwandeln von Datenformaten.
  - Ableitung neuer Features und Festlegen der Zielvariable.
  - Aufteilung der Daten in Trainings- und Testsets.

- **Modellbildung und -evaluation:** 
  - Erstellung eines Entscheidungsbaummodells mit scikit-learn.
  - Anpassung des Modells an die Trainingsdaten.
  - Vorhersage und Bewertung der Modellleistung anhand des Testsets.
  - Visualisierung der Ergebnisse und des Entscheidungsbaums.

---

## Python 6 - Neuronales Netz zur Vorhersage von Energieverbrauchsdaten

**Beschreibung:** In diesem Notebook verwende ich ein neuronales Netz zur Vorhersage von Energieverbrauchsdaten.

- **Datenpräparation:** 
  - Einlesen der Daten und vorbereitende Schritte wie beim Entscheidungsbaum-Notebook.
  - Normalisierung der Feature-Daten zur Verbesserung der Modellleistung.

- **Modellerstellung und -training:** 
  - Definition der Netzwerkarchitektur.
  - Kompilierung des Modells mit einem geeigneten Optimierer und Verlustfunktion.
  - Training des Modells mit den Trainingsdaten und Validierung mit den Testdaten.

- **Modellbewertung:** 
  - Bewertung der Modellleistung anhand von Verlust- und Genauigkeitsmetriken.
  - Visualisierung der Trainings- und Validierungsverluste zur Beurteilung der Überanpassung (overfitting).

- **Vorhersage und Visualisierung:** 
  - Durchführung von Vorhersagen mit dem trainierten Modell.
  - Visualisierung der Vorhersageergebnisse im Vergleich zu den tatsächlichen Daten.

---
