# GANS
Abgabe der Projektaufgaben WS2021 MBB


## Umgebung

Visual Studio Code x64 1.64.2

Python: 3.9.10 x64 

Hinweis: Eine Python Version höher als 3.9 ist nicht zu verwenden, da PyTorch dafür noch nicht kompatibel ist. 

## Installationsansweisungen

Die Requirements der GANS werden bei der Ausführung einer Datei automatisch via pip install -r requirements.txt geladen. Sollte dies nicht funktionieren, müssen gegebenenfalls manuell folgende Schritte vorgenommen werden:

Vor dem Ausführen sind PyTorch, Matplotlib & Pandas in der Konsole zu installieren, folgende Befehle sind dafür nacheinander auszuführen:

pip3 install torch==1.10.2+cu102 torchvision==0.11.3+cu102 torchaudio===0.10.2+cu102 -f https://download.pytorch.org/whl/cu102/torch_stable.html

pip install matplotlib

pip install pandas

## Branch

Der auszuführende Code ist für alle GANS im Branch "Main" hinterlegt. 

## Dateien

Die zu verwendenden Datein sind am folgenden Speicherort (Kaggle) herunterzuladen: 
https://www.kaggle.com/soumikrakshit/anime-faces (Download 228MB)

Der heruntergeladene Ordner ist wie folgt zu benennen: 
anime-faces.zip

Diese ZIP-Datei ist im Ordner "GANS" (selbiger Ordner der README & .ipynb - Dateien) abzulegen.

Ein abspeichern der ZIP-Datei in GitHub war aufgrund der Dateigrößenbegrenzung von 25MB nicht möglich. 

## Ausführung

Die .ipynb - Dateien sind in beliebiger Reihenfolge ausführbar, mittels des Buttons alle ausführen wird eine ausgewählte Datei bis zum Ende durchlaufen. Sollte eine Datei wiederholt durchlaufen zu sein, sind die durch den vorherigen Durchlauf erstellten Ordner vorher zu löschen
