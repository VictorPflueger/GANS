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

## Bildateien

Die Bilddateien welche zum Asuführen des GANS verwendet werden, können auf zwei Arten erlangt werden:

1. Vorhab ist die Datei "Dataset.ipynb" auszuführen, welche die entsprechenden Dateien von der Plattform Kaggle herunterlädt. Dazu ist vorab durch den Nutzer die eigene "kaggle.json" Datei im entsprechenden Umgebungsordner zu hinterlegen. 

2. Die zu verwendenden Datein sind am folgenden Speicherort (Kaggle) herunterzuladen: 
https://www.kaggle.com/soumikrakshit/anime-faces (Download 228MB). Die heruntergeladene ZIP-Datei ist als "anime-faces.zip" in einem Ordner "animefaces" im entsprechenden Umgebungsordner abzulegen.


Ein direktes Abspeichern der ZIP-Datei in GitHub war aufgrund der Dateigrößenbegrenzung von 25MB nicht möglich. 

## Ausführung

Vorab sind die Bilddateien runterzuladen. Die .ipynb - Dateien sind in beliebiger Reihenfolge ausführbar, mittels des Buttons alle ausführen wird eine ausgewählte Datei bis zum Ende durchlaufen. 

## DCGAN

Bei der Datei DCGAN.ipynb handelt es sich um die Erfüllung der zugrundeliegenden Hauptaufgabe "Trainieren Sie (ein) Generative Adversarial Network (GAN) zur Generierung von Bilddaten in PyTorch". Dazu wurden Strukturen eines Deep Convolutional GANS verwenddet, kurz DCGAN. 

## WGAN

Bei der Datei WGAN.ipynb handelt es sich um die Erfüllung der ersten Zusatzaufgabe "Wandeln Sie Ihr GAN in ein Wasserstein GAN um". Dazu wurden Strukturen eines Wasserstein-GANS verwenddet, kurz WGAN. Hierbei wurde sich am dafür empfohlenen Paper orientiert: 
https://arxiv.org/pdf/1701.07875.pdf 

## GPGAN

Bei der Datei GPGAN.ipynb handelt es sich um die Erfüllung der zweiten Zusatzaufgabe "Wandeln Sie Ihr GAN in ein Gradient Penalty GAN um". Dazu wurden Strukturen eines Gradient Penalty-GANS verwenddet, kurz GPGAN. Hierbei wurde sich am dafür empfohlenen Paper orientiert: 
https://arxiv.org/pdf/1704.00028.pdf

##Testing

Die Programme wurden sowohl in VSCode als auch in Google Colab getestet. Als nachweis finden sich die Ergebnisbilder nach Durchlauf aller Epochen beispielhaft im beigefügten Ordner