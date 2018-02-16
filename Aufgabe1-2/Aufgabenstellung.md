# Wintervorrat

Das kleine Eichhörnchen Fritz wohnt im Rechteckwald, einem rechteckigen Gebiet bestehend aus
Feldern. Fritz sucht einen Platz, an dem er seine Wintervorräte vergraben kann. Das Vergraben benötigt Zeit, und in dieser Zeit darf Fritz nicht von einem Raubvogel erspäht werden. Fritz hat bereits ausgekundschaftet, wie sich die Raubvögel im Rechteckwald üblicherweise verhalten.
Ab dem ersten Sonnenstrahl beginnen die Vögel nach und nach, über den Wald zu ﬂiegen. Alle ﬂiegen parallel zu den Seiten des Waldes. Manche ﬂiegen zwischen West- und Ostrand, andere zwischen Nordund Südrand des Waldes hin und her. Dabei halten sie nach Beute Ausschau: Sie überblicken kurz das Feld, über dem sie sich befnden, und dann ﬂiegen sie zum nächsten Feld weiter. Das dauert insgesamt eine Minute. Die Sonne scheint genau 12 Stunden. Nur in dieser Zeit können die Vögel Beute erspähen.
Am liebsten hätte Fritz ein absolut sicheres Feld, das nie von einem Vogel überblickt wird. Es kann allerdings sein, dass es ein solches Feld nicht gibt. Das ist aber nicht schlimm, denn Fritz braucht nur 30 Minuten, um seine Vorräte zu vergraben. Deswegen genügt ihm auch ein sicheres Feld: Ein Feld ist sicher, wenn es am Tag einen sicheren Zeitraum von 30 Minuten gibt, in denen kein Vogel das Feld überblicken kann.

## Junioraufgabe 2
Schreibe ein Programm für Fritz. 
Gegeben sind die Größe des Rechteckwaldes, die Anzahl der Vögel und für jeden Vogel dessen Startfeld, -zeitpunkt und -ﬂugrichtung. Das Startfeld ist ein Randfeld, und jeder Vogel ﬂiegt von dort aus in der gegebenen Richtung zum gegenüberliegenden Randfeld und wieder zurück.
1. Das Programm soll zunächst entscheiden, ob es absolut sichere Felder gibt. Wenn ja, soll es sie ausgeben.
2. Außerdem soll das Programm sichere Felder finden, falls möglich, und für jedes dieser Felder einen sicheren Zeitraum ausgeben. Dazu kann das Programm simulieren, wie die Vögel während des Tages den Wald überﬂiegen.

![Beispiel](Beispiel.png)

Das Bild zeigt einen Rechteckwald, der 15 Felder in Nord-Süd-Richtung mal 3 Felder in West-Ost-Richtung groß ist. Im Bild sind Startzeiten und  Flugrichtungen der Vögel eingezeichnet. Die absolut sicheren Felder sind grün, die sicheren Felder gelb gefärbt.

Jede Datei enthält
- in der ersten Zeile zwei Zahlen, nämlich Breite und Höhe des Rechteckwaldes,
- in der zweiten Zeile die Anzahl der Vögel und
- in jeder der folgenden Zeilen die Angaben zu einem Vogel: das Startfeld (angegeben sind dessen x- und y-Koordinaten, also Spalte und Zeile des Startfeldes), die Startminute und die Flugrichtung (W, O, N oder S).

Die erste Koordinate ist die x-Koordinate (Ost-West) und die zweite Koordinate ist die y-Koordinate (Nord-Süd). Das Feld mit den Koordinaten 1 1 liegt in der süd-westlichen Ecke. (Vgl. das Bild in der Aufgabenstellung.)