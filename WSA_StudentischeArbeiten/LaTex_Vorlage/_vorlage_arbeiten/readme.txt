Dies ist die Hilfe-Datei f�r die Latex-Vorlage f�r wissenschaftliche Arbeiten am WSA.

Folgende Schritte sind notwendig, um die Vorlage f�r die eigene Arbeit nuzten zu k�nnen:

0.	Damit die Vorlage lauff�hig ist, muss man sich den Ordner _vorlage_arbeiten und _src
	herunterladen. Der erste Ordner kann umbenannt werden, der zweite sollte so gelassen
	werden, damit die Pfade zu den notwendigen Quelldateien stimmen.
---------------------------------------------------------------------------------------
1.  Die .tex und .idx Datei mit dem Namen "Arbeit(bitte umbenennen)" umbennen, z.B. in
	"Bachelorarbeit". Wichtig ist, dass beide Dateien gleich hei�en!
---------------------------------------------------------------------------------------
2.  Die Hauptdatei (.tex) �ffnen und dort die Variablen \title, \betreuer, \artderarbeit
	usw. anpassen. (Zeile 79 - 85)
	ACHTUNG! Wenn seltsame Zeichen wie z.B. 'ä' an mehreren Stellen in den Kommentaren 
	auftauchen, stimmt die Zeichencodierung der Vorlage nicht mit der des genutzten 
	Editors	�berein. Die Codierung muss auf ISO-8859-15 stehen! In Texmaker geht das in
	Optionen > Texmaker konfigurieren > Editor
---------------------------------------------------------------------------------------
3.  Wenn es sich um eine Projektarbeit handelt, die von mehr als einer Person
	geschrieben wird, die Anzahl der Mitschreiber in \anzahlautoren angeben. Standard-
	wert ist 1. (Zeile 88) Darunter alle Autoren mit Namen und Matrikelnummern in die 
	entsprechenden Felder eintragen. (Zeile 94 - 103)
---------------------------------------------------------------------------------------
5.	Vor dem ersten kompilieren muss der Befehl f�r das schnelle �bersetzten konfiguriert
	werden. Das funktioniert in jedem Programm anders, grunds�tzliches dazu findet sich
	als Kommentar ganz oben in der Hauptdatei. Als erster Test kann auch einfach 
	"PDFLatex" ausgef�hrt werden, allerdings werden dann die Verzeichnisse nicht korrekt
	erstellt bzw. nicht aktualisiert.