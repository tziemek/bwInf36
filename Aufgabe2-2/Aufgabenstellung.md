# Aufgabe 2: Wehret den Wildschweinen!

Ein Wald ist von Wildschweinen bevölkert. Sie fallen regelmäßig auf einem südlich des Waldes liegenden Acker ein. Zwischen Wald und Acker liegt ein rechteckiges, hügeliges Brachland, das im Osten und im Westen abgezäunt ist.

![Gelaende](Gelaende.png)

Der Besitzer des gesamten Geländes ist es leid, dass die Wildschweine ständig seinen Acker verwüsten. Er will dafür sorgen, dass sie nicht vom Wald auf den Acker gelangen können. Dafür macht er sich zunutze, dass Wildschweine nicht in der Lage sind, größere Steigungen zu überwinden. Er kann die  Wildschweine also davon abhalten, das Brachland zu überqueren, indem er an gezielten Stellen dessen Landschaft so verändert, dass sie für ein  Wildschwein zu steil abfällt oder ansteigt. Zur Vereinfachung reduziert er die Landschaft auf Planquadrate und die möglichen Wege der Wildschweine auf solche, deren Abschnitte stets vom Zentrum eines Planquadrats zum Zentrum eines in nördlicher, südlicher, östlicher oder westlicher Richtung benachbarten Planquadrats verlaufen. Er muss jetzt erreichen, dass auf jedem solchen Weg von der Nordgrenze bis zur Südgrenze der Brache mindestens einmal der Höhenunterschied zwischen aufeinander folgenden Planquadraten mindestens 1 m beträgt. Dazu kann er Erde von einem Planquadrat zu einem benachbarten Planquadrat bringen lassen, wodurch die Höhe des ersten Planquadrats fällt und die des zweiten Planquadrats um genauso viel wächst. Da  solche Erdarbeiten aber teuer sind, ist er bestrebt, diese Maßnahme so wenig wie möglich einzusetzen.

## Aufgabe
Schreibe ein Programm, das eine Matrix mit den Höhen der Planquadrate des Brachlands einliest und kostengünstigste Erdarbeiten vorschlägt, die jeden Weg von der Nordgrenze bis zur
Südgrenze für Wildschweine unpassierbar werden lassen. Gehe dabei davon aus, dass es genauh Euro kostet, h cm Erde von einem Planquadrat zu einem benachbarten Planquadrat bringen zu
lassen.

Zu dieser Aufgabe gibt es fünf Beispieleingaben, die jeweils in einer Textdatei enthalten sind.  Jede Beispieleingabe beschreibt ein quadratisches Brachland, das aus N x N Planquadraten besteht.

Jede Beispieldatei enthält:
- in der ersten Zeile die "Seitenlänge" N (eine ganze Zahl)
- und in den folgenden N Zeilen jeweils die Höhen der N Planquadrate in dieser Zeile (angegeben als Fließpunktzahlen)