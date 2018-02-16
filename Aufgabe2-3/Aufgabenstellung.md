# Aufgabe 3: Quo vadis, Quax?

In einer abgelegenen und unwegsamen Gegend will Quax die Fähigkeiten seines neuen Quadcopters ausprobieren. Da wird aus dem Spiel Ernst: Ein Tornado mit anschließender Überschwemmung vernichtet seine Essenvorräte, so dass er seinen Urlaub abbrechen und sofort die
lange Wanderung zurück zur einzigen Stadt der Provinz antreten muss. Außerdem hat sich die
Landschaft vollkommen verändert – es haben sich Flüsse und Seen gebildet, wo früher keine
waren. Es ist nicht klar, ob es überhaupt noch einen gangbaren Weg zurück zur Stadt gibt und,
falls ja, wo sich ein solcher Weg zwischen den Gewässern durchschlängelt.
Quax möchte die Landschaft mit dem Quadcopter erkunden, bevor er loslegt, um lange Umwege zu vermeiden, die er sich nicht leisten kann. Der Quadcopter kann in einer frei wählbaren
Flughöhe einen beliebigen Punkt der Landschaft anfliegen. Allerdings ist auch er beschädigt:
Die Speicherkarte ist hin, und es funktioniert nur ein einziger Sensor. Dieser erfasst ein quadratisches, nach Norden ausgerichtetes Gebiet unter dem Quadcopter, dessen Seitenlänge proportional zur Flughöhe ist. Der Sensor kann für dieses Testgebiet entscheiden, ob es ganz von
Wasser bedeckt ist („Wasser“), ganz aus trockenem Land besteht („Land“) oder sowohl Wasser
als auch Land enthält („Gemischt“).
Quax kann wiederholt den Quadcopter für eine bestimmte Kombination aus Flughöhe und Zielpunkt programmieren, ihn entsenden und bei seiner Rückkehr das Ergebnis („Wasser“, „Land“
oder „Gemischt“) in Empfang nehmen. Liefert der Quadcopter auch für ein kleinstmögliches
Testgebiet mit Seitenlänge 20 m immer noch das Ergebnis „Gemischt“, geht Quax davon aus,
dass er dieses Testgebiet überqueren kann – zur Not schwimmt er ein paar Meter mit dem Gepäck.
Das folgende Pixelbild zeigt eine Beispiel-Landschaft. Jedes Pixel repräsentiert einen quadratischen Bereich der Landschaft mit Seitenlänge 10 m. Das grüne Pixel zeigt die Position der
Stadt. Vom oberen roten Startpunkt kann Quax die Stadt erreichen, vom unteren aber nicht.
![Gelaende](Gelaende.png)

## Aufgabe
1. Schreibe ein Programmmodul, das aus den Ergebnissen durchgeführter Flüge bestimmt,
ob es für Quax einen gangbaren Weg zurück zur Stadt gibt, ob es definitiv keinen solchen
Weg gibt oder ob mehr Flüge nötig sind, um eine Entscheidung herbeizuführen.

2. Beschreibe eine Strategie für das Entsenden des Quadcopters, die mit möglichst wenig
Flügen einen Weg zur Stadt findet, falls es einen gibt.

3. Schreibe ein Programm, das eine Landschaft einliest, in welcher die Stadt sowie mehrere mögliche Standorte von Quax markiert sind. Ein Pixel repräsentiert ein Quadrat der
Seitenlänge 10 m. Dann soll das Programm die anhand der Strategie aus (b) festgelegten
Entsendungen – für jeden Standort des Quadcopters einzeln – simulieren. Ausgeben soll
es je eine Darstellung der Landschaft, in der die Testgebiete mit ihren jeweiligen Ergebnissen geeignet eingetragen sind. Falls es einen gangbaren Weg zur Stadt gibt, soll dieser
in der Darstellung erkennbar sein.
Wende dein Programm mindestens auf die auf der BWINF-Website gegebenen Beispiele
an und dokumentiere die Ergebnisse. Gehe davon aus, dass sich außerhalb der eingelesenen Landschaft nur Wasser befindet.

4. Gibt es Verteilungen von Flüssen und Seen, bei denen deine Strategie aus (b) zu sehr
vielen Flügen führt? Falls nein, erkläre warum nicht. Falls ja, gib ein Beispiel dafür an
und erkläre, worin das Problem besteht.

Zu dieser Aufgabe gibt es drei Beispieleingaben, nämlich drei Pixelbilder.  Jedes Bild enthält genau ein grünes Pixel (den Zielpunkt bzw. die "Stadt") sowie ein oder mehrere rote Pixel (den Startpunkt).  Alle anderen Pixel sind entweder schwarz (Land) oder weiß (Wasser).