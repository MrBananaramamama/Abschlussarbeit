# Abschlussarbeit CAS MAZ Datenjournalismus
"Wem gehören die börsenkotierten Schweizer Unternehmen?" 

Eine Annäherung an die Besitzverhältnisse von börsenkotierten Schweizer Unternehmen im UBS 100 Index und weiteren.

Link zum Artikel, weiteres Vorgehen: https://github.com/MrBananaramamama/Abschlussarbeit/blob/master/Artikel_Weiteres%20Vorgehen.pdf

## Ausgangsthese
Es ist bekannt, dass der grösste Teil der Schweizer Firmen auch natürlichen und juristischen Personen in der Schweiz gehören, danach wohl grosse amerikanische Vermögensverwalter folgen. Doch auch die Uebernahme von Firmen aus China hat in den letzten Jahren für Schlagzeilen gesorgt. Wie genau die Verteilung aber ist, ist nur bruchstückhaft bekannt.

## Aufwand/Ertrag
Der Aufwand wird wohl beträchtlich sein, die Webseite der SIX scheint zwar auf den ersten Blick gut strukturiert, aber die Angaben sind nicht einheitlich und manchmal fehlend. 
Der Ertrag kann je nach Entwicklung interessant sein. Insbesondere, wenn die Analyse jedes halbe Jahr wiederholt wird, können sich Änderungen der Besitzverhältnisse der Schweizer Firmen zeigen. Das hat Relevanz.

## Knackpunkt
Das Ergebnis wird bei weitem nicht abschliessend sein. Weil nur Besitz von 3, 5 oder mehr Prozent an einer börsenkotierten Firma gemeldet werden muss, bleibt ein sehr grosser Anteil der Besitzverhältnisse im Dunkeln. Dies nennt man Streubesitz.

## Briefing-Gespräch
Mit Julian Chan, Mediensprecher SIX Group:
"Knackpunkte sind grundsätzlich folgende: Es sind einfach die neuesten Meldungen, aber das heisst nicht, dass sie aktuell sind. Denn Meldungen müssen nur gemacht werden, wenn eine der Schwellen, also bei 3 oder 5 Prozent oder darüber, über oder unterschritten wird. Wenn sich die Anteile zwischen den Schwellen verschieben, braucht es keine Meldung. Ausserdem werden die Meldungen von den Firmen selbst verfasst, wir publizieren sie nur. Das heisst, sie sind auch nicht einheitlich."

"Die Daten können wir leider nicht zur Verfügung stellen, wir haben sie nicht so strukturiert."

- Weitere Antworten, schriftlich:
"Hat die Offenlegungsstelle Grund zur Annahme, ein Aktionär sei der Meldepflicht nicht nachgekommen, hat sie dies der FINMA mitzuteilen (Art. 122 FinfraG). Die Offenlegungsstelle verfügt nicht über hoheitliche Kompetenzen und kann daher keine Untersuchungen durchführen. SIX Exchange Regulation AG spricht zudem im Bereich der Offenlegung von Beteiligungen keine Sanktionen aus. Die FINMA ist zuständig für allfällige administrative Massnahmen und leitet mögliche Verstösse gegen das FinfraG dem Eidgenössischen Finanzdepartement (EFD) zur Beurteilung bzw. zur Sanktionierung / Auferlegung von Bussen weiter.
 
- Bei manchen Meldungen sind gleichzeitig Erwerbs- und Veräusserungspositionen angegeben. Was heisst das konkret? Vereinfacht gesagt sind unter den Erwerbspositionen gehaltene Aktien sowie alle Rechte zum Erwerb von Aktien (u.a. Call-Optionen und eingeräumte Put-Optionen) zu melden und unter den Veräusserungspositionen alle Rechte zum Verkauf von Aktien (u.a. Put-Optionen und eingeräumte Call-Optionen). Wer in den Erwerbspositionen oder den Veräusserungspositionen einen Schwellenwert erreicht, wird meldepflichtig. Die Positionen sind einzeln und unabhängig voneinander zu berechnen und gleichzeitig zu melden. Die Grundlage für die Meldepflicht findet sich in Art. 120 FinfraG sowie zur Berechnung der zu meldenden Positionen in Art. 14 FinfraV-FINMA.
 
- Was sind die konkreten Unterschiede zwischen wirtschaftlich Berechtigten zur Ausübung der Stimmrechte und den direkten Aktionären. Oder: Wer ist der eigentliche Besitzer der jeweiligen Aktien? Hier werden zwei Meldepflichten vermischt: Es gibt den wirtschaftlich Berechtigten als Subjekt der Meldepflicht, der die aus einer Beteiligung fliessenden Stimmrechte kontrolliert und das wirtschaftliche Risiko aus der Beteiligung trägt (Art. 10 Abs. 1 FinfraV-FINMA). In der Meldung sind die direkt beteiligten Gesellschaften, welche vom wirtschaftlich Berechtigten kontrolliert werden, als Zusatzinformation in der Meldung aufzuführen (Art. 11 FinfraV-FINMA und Art. 22 Abs. 1 lit. e FinfraV-FINMA). dZudem gibt eine Meldepflicht für Personen, welche die Stimmrechte an Beteiligungspapieren nach freiem Ermessen ausüben können (Art. 120 Abs. 3 FinfraG und Art. 10 Abs. 2 FinfraV-FINMA).

## Datensatz
Der Datensatz wird mittels scraping der Webseite "bedeutende Aktionäre" der SIX Group, der Schweizer Börse, beschafft. Zum Abgleich und zur Auswahl der Firmen wird auf weitere Datensätze der SIX Group zugegriffen, insbesondere für die Indizes UBS 100, SMI und SMI Expanded. Diese können auf der Webseite der SIX als Excel heruntergeladen werden. Die Quelle für diese Arbeit ist also durchgehend die SIX Group. 



_je nach gewählter Variante 1,2 oder 3: Endprodukt, Skizze des weiteren
Vorgehens oder Protokoll des Scheiterns




| Tätigkeit                                                          | Datum | Zeitaufwand |
|--------------------------------------------------------------------|-------|-------------|
| Erste Exploration Datenbank, verschiedene Herangehensweisen testen | 28.1. | 8h          |
| Recherche: Papers studieren, Recherchegespräch SIX                 | 07.2. | 4h          |
| Scraper schreiben                                                  | 12.2. | 10h         |
| Scraper schreiben                                                  | 13.2. | 10h         |
| Scraper Troubleshooting                                            | 14.2. | 10h         |
| Scraper finalisieren                                               | 15.2. | 5h          |
| Daten scrapen                                                      | 15.2. | 2h          |
| Daten putzen, manuell                                              | 15.2. | 1h          |
| Pandas Auswertung                                                  | 15.2. | 2h          |
| Pandas, weitere Auswertungen                                       | 16.2. | 6h          |
| Text schreiben                                                     | 16.2. | 4h          |
| Repository erstellen                                               | 16.2. | 2h          |
