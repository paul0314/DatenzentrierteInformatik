# Datenzentrierte Informatik

Häufiger werden Covid-Daten zur Analyse und Visualisierung benutzt. Diese werden stets aus der Datei time_series_covid19_confirmed_global.csv von der Webseite data.humdata.org/dataset/novel-coronavirus-2019-ncov-cases entnommen.

Überblick:

Blatt 2:

Aufgabe 3: 
**Angleichung einer Gompertz Funktion an die Covid Daten** vom 27.01.2020 bis 13.04.2020 mittels der Methode kleinster Quadrate (erstes Kennenlernen des Datensatzes)

Aufgabe 4: 
Vergleich verschiedener PolyFit Ansätze (Auffrischung grundlegender Kenntnisse)


Blatt 3:

Aufgabe 1: 
Konditionszahlen von Matrizen (kleine Wiederholung)

Aufgabe 2: 
Einfache lineare Regression (Auffrischung grundlegender Kenntnisse)

Aufgabe 3 bis 6: 
Arbeit auf dem bekannten Iris-Flower-Datensatz (iris.csv). Dann wird gemäß Fisher eine lineare Diskriminanzanalyse durchgeführt (**LDA Klassifikator**), um die Parameter für einen binären linearen Klassifikator zu trainieren. Anschließend wird der Klassifikator auf unabhängigen Testdaten geprüft und schließlich werden unterschiedliche Projektionsmatrizen genutzt, um die Daten zu visualisieren und zu erkennen, welche Daten sich linear seperieren lassen und welche nicht, um die Testergebnisse zu interpretieren.


Blatt4:

Aufgabe 1: 
Plotten der Covid Daten und Implementierung eines centered moving averages für eine Zeitdauer von 7 Tagen. Erneut wird je eine Gompertz-Funktion an einen Zeitraum angepasst, basierend auf den moving average Daten. Schließlich wird ein **Mischmodell aus zwei Gompertz-Funktionen** auf den gesamten Zeitraum angeglichen, um ein Modell für die gesamten Covid-Daten zu erhalten.

Aufgabe 2: 
Diese Aufgabe beschäftigt sich mit der **Einbettung von Strings in einen euklidischen Vektorraum**. Genauer werden für diese Einbettung n-Gramme genutzt (Ein 2-Gramm von "homer" wäre ["ho", "om", "me", "er"]). Aus diesen n-Grammen wird eine zentrierte Kern-Matrix berechnet. Nun kann die Idee der Principal Component Analysis genutzt werden (**PCA**). Zunächst werden die Eigenwerte der Kern-Matrix bestimmt (in matU), um damit die **Projektionsmatrix** matP zu konstruieren, und das Ergebnis im zweidimensionalem Raum darstellen zu können. Man hat nun eine zweidimensionale Darstellung der Strings gefunden, die im folgenden visualisiert wird. Außerdem werden verschiedene Einbettungsdimensionen und Wahlen der Eigenvektoren ausprobiert.

Aufgabe 3: 
**Nächste Nachbar Suche (KNN) mittels kD-Bäumen auf den eingebetteten Strings**. Außerdem wird geschaut, ob die Dimension des Einbettungsraums einen Unterschied auf das Ergebnis macht.

Aufgabe 4: 
**k-Means Clustering** auf den eingebetteten Stringdaten.

Aufgabe 5: 
**Eigene Implementierung des k-Means clustering Algorithmus nach MacQueen.**


Blatt5:

Aufgabe 1: 
Wein-Klassifikationsproblem gelöst mittels **Entscheidungsbäumen**. Außerdem werden verschiedenen Parameterkombinationen ausprobiert.

Aufgabe 2: 
Entwurf eines **Entity-Relationsship-Diagramms** für eine Videosharing Plattform.

Aufgabe 3: 
Übertragung des Datenmodells (ER-Diagramm von oben) in ein **relationales Datenbankschema**.

Aufgabe 4-5: 
Grundlegende Datenbankbefehle auf der nach dem Schema aus Aufgabe 3 designten Datenbank.
