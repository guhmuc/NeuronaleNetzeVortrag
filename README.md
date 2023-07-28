# Neuronale Netze

Diese Repo enthält ein Jupyter Notebook mit einem kurzen Crashkurs zu Neuronalen Netzen.
Ausserdem wird ein einfaches Neuronales Netz "from Scratch" programmiert, trainiert und getestet.

Zum trainieren und testen wird der MNIST Datensatz zur Erkennung von Ziffern benutzt - das Hello-World des Machine Learning.

Um das Notebook zu benutzen musst Du zunächst z.B. Jupyter Lab installieren und ausführen:

    pip3 install jupyterlab
    jupyter lab


Dann das Notebook neuro2.ipynb öffnen.

Anschließend nacheinander die Code-Cells 

- Utilities
- Neuronales Netz
- Ein- und Ausgabe
- Trainings- und Testdaten
- Initialisierung

ausführen.

Mit der Zelle 
- Stichproben

kannst Du die Ergebnisse des noch untrainierten Netzes ansehen (du kannst die Zelle mehrfach ausführen; es werden zufällige Ziffern aus dem Test-Set probiert) und mit der Zelle

- Erfolgskontrolle

die Erkennungsrate ermitteln (die untrainiert logischerweise bei ca. 10% liegen sollte).

Dann die Zelle 

- Lernen  (erstmal vllt. mit nur 1% der Trainingsdaten)

ausführen und erneut "Stichproben" und "Erfolgskontrolle" ausprobieren und staunen ... 
Dann nochmal "Lernen" aber nun die Prozent hochdrehen.  


Alternative zum lokalen clonen: Direkt mit Binder ausprobieren (ist aber ein bisschen langsam).

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/guhmuc/NeuronaleNetzeVortrag/HEAD?labpath=neuro2.ipynb)
