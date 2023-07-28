# Neuronale Netze

Diese Repo enthält ein Jupyter Notebook mit einem kurzen Crashkurs zu Neuronalen Netzen.
Ausserdem wird ein einfaches Neuronales Netz "from Scratch" programmiert, trainiert und getestet.

Zum trainieren und testen wird der MNIST Datensatz zur Erkennung von Ziffern benutzt - das Hello-World des Machine Learning.

Um das Notebook zu benutzen hast Du zwei Möglichkeiten: Lokal oder Cloud

## In der Cloud

Binder ist ein Cloud Service, mit dem Du Notebooks direk online, ohne etwas zu installation ausführen kannst. Ist aber ein bisschen (sehr) langsam! Einfach auf den Link hier clicken, ein wenig warten, bis alles eingerichtet ist (kann ein paar Minuten dauern) und das Notebook erscheint (mit dem Bild der Nervenzelle). Dann weiter wie unter "Ausprobieren" beschrieben.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/guhmuc/NeuronaleNetzeVortrag/HEAD?labpath=neuro2.ipynb)



## Lokal

Dazu musst Du Jupyter Lab auf Deinem Rechner installieren und ausführen:

    * pip3 install jupyterlab
    * jupyter lab

Dann dieses Repo auf Deinen Rechner clonen, das Notebook neuro2.ipynb öffnen und weiter wie unter "Ausprobieren" beschrieben.

## Ausprobieren

Jetzt nacheinander folgende "Code-Cells" ausführen. Code-Cells sind einfach die Bereiche im Jupyter Notebook, die ... Code (wow!) enthalten. Ausführen kannst Du sie, in dem Du mit der Maus in einen reinclickst (so dass links ein blauer Balken erscheint) und dann oben in der Toolbar auf den Start-Pfeil clickst. *Obacht: Du musst wirklich in die Code-Cells clicken, nicht auf die Überschriften dazwischen!*

- Utilities
- Neuronales Netz
- Ein- und Ausgabe
- Trainings- und Testdaten
- Initialisierung

Damit sind alle nötigen Funktionen definiert, die Lern- und Testdaten geladen und das Netz initialisiert. 

Mit der Zelle 
- Stichproben

kannst Du nun die Ergebnisse des noch untrainierten Netzes ansehen (du kannst die Zelle mehrfach ausführen; es werden zufällige Ziffern aus dem Test-Set probiert) und mit der Zelle

- Erfolgskontrolle

die Erkennungsrate ermitteln (die untrainiert logischerweise bei ca. 10% liegen sollte).

Dann die Zelle 

- Lernen  (erstmal vllt. mit nur 1% der Trainingsdaten)

ausführen und erneut "Stichproben" und "Erfolgskontrolle" ausprobieren und staunen ... 
Dann nochmal "Lernen" aber nun die Prozent hochdrehen.  

Viel Spaß!