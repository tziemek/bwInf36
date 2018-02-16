# Auto-Scrabble

Familie Petersen fährt mit dem Auto aus dem Urlaub nach Hause. Plötzlich ruft die kleine Heike: „Da steht mein Naaaame, daaaa auf dem Autoschild!“ Ganz begeistert zeigt sie auf das Kennzeichen, auf dem zu lesen ist:

![SchildHeike](SchildHeike.png)

Ihr Bruder Timo ist nicht beeindruckt. „Es gibt doch so viele verschiedene Kennzeichen. Da kann man bestimmt jedes Wort schreiben.“ Heike antwortet: „Neee, dein Name geht doch gar nicht!“ Wer hat Recht? Ein deutsches KfZ-Kennzeichen besteht aus drei Teilen:
- einem Kürzel für eine Stadt oder einen Kreis aus der Liste, die du auf den BwInf-Webseiten findest;
- einem Mittelteil, der aus einem oder zwei Buchstaben besteht (ohne Umlaute) und
- einer Zahl, die wir hier ignorieren.

## Aufgabe 4
1. Stimmt es, dass TIMO nicht auf einem Kennzeichen stehen kann?
2. Gib ein weiteres Wort mit vier Buchstaben an, das nicht auf einem Kennzeichen stehen kann. Findest du sogar ein solches Wort mit drei Buchstaben? Mit zwei?
3. Schreibe ein Programm, das ein Wort einliest und überprüft, ob es mit mehreren Kennzeichen geschrieben werden kann. Dabei darf das Wort aufgeteilt  werden, z.B.:
![Schilder1](Schilder1.png)
Ein Kennzeichen muss immer voll ausgenutzt
werden. Folgendes ist also nicht erlaubt:
![Schilder2](Schilder2.png)

4. Erweitere dein Programm so, dass es außerdem eine Folge von Kennzeichen ausgibt, mit denen das Wort gebildet werden kann (wenn es eine gibt).

Hier gibt es zunächst eine Datei mit der Liste der Städte- bzw. Kreis-Kürzel, die auf deutschen Kfz-Kennzeichen stehen können (kuerzelliste.txt).  Jedes Kürzel steht in einer eigenen Zeile dieser Datei.

Außerdem gibt es eine Eingabedatei, die in den Teilaufgaben 3 und 4 verwendet werden kann (autoscrabble.txt). Sie enthält in jeder Zeile ein Wort, für das überprüft werden soll, ob es aus Kfz-Kennzeichen gebildet werden kann.