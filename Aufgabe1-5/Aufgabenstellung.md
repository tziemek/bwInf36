# Dreiecke zählen

![Beispiel](Beispiel.png)

Janina hat von ihrer Freundin Nadine ein Rätsel aus dem Internet zugeschickt bekommen: Wie viele Dreiecke sind in dieser Zeichnung zu sehen? Nachdem Janina eine Weile Dreiecke gezählt hat, will sie ihr Ergebnis im Internet nachprüfen. Sie findet aber keine Lösung, sondern nur weitere Rätsel dieser Art. Da sie sich nicht jedes Mal erneut ans Zählen machen will, überlegt sie, ob sich solche Rätsel mit einem Computer lösen lassen.

## Aufgabe 3
Versetze dich in Janinas Lage und schreibe ein Programm, das die Dreiecke in einer Rätsel-Zeichnung zählt. Eine Zeichnung besteht aus einigen Strecken. Du kannst davon ausgehen, dass keine zwei Strecken auf derselben Geraden liegen und dass sich nie mehr als zwei Strecken im gleichen Punkt schneiden. In der obigen Zeichnung sind übrigens neun Dreiecke zu finden.


Bei dieser Aufgabe besteht eine Beispieleingabe aus einer Menge an Strecken.

Die Dateien sehen jeweils so aus:
- In der ersten Zeile steht die Anzahl der Strecken.
- In jeder folgenden Zeile sind die Endpunkte der Strecken angegeben. Jede Zeile enthält also
    - die x-Koordinate von Endpunkt 1
    - die y-Koordinate von Endpunkt 1
    - die x-Koordinate von Endpunkt 2
    - die y-Koordinate von Endpunkt 2

Die Koordinatenwerte sind als Gleitkommazahlen (float) angegeben.

Die Aufgabenstellung fordert, dass dein Programm Dreiecke zählt. Als Ausgabe genügt also jeweils eine Zahl. Es ist aber besser, wenn dein Programm auch die gefundenen Dreiecke ausgibt; dann ist es leichter, das Ergebnis zu überprüfen. Eine grafische Ausgabe ist sicher besonders überzeugend, aber eine Textdatei ist auch gut.