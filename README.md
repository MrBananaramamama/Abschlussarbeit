# Abschlussarbeit CAS MAZ Datenjournalismus
"Wem gehören die börsenkotierten Schweizer Unternehmen?" Eine Annäherung an die Besitzverhältnisse von börsenkotierten Schweizer Unternehmen im UBS 100 Index und weiteren.

## Ausgangsthese
Es ist bekannt, dass der grösste Teil der Schweizer Firmen auch natürlichen und juristischen Personen in der Schweiz gehören, danach wohl grosse amerikanische Vermögensverwalter folgen. Doch auch die Uebernahme von Firmen aus China hat in den letzten Jahren für Schlagzeilen gesorgt. Wie genau die Verteilung aber ist, ist nur bruchstückhaft bekannt.

## Aufwand/Ertrag
Der Aufwand wird wohl beträchtlich sein, die Webseite der SIX scheint zwar auf den ersten Blick gut strukturiert, aber die Angaben sind nicht einheitlich und manchmal fehlend. 
Der Ertrag kann je nach Entwicklung interessant sein. Insbesondere, wenn die Analyse jedes halbe Jahr wiederholt wird, können sich Änderungen der Besitzverhältnisse der Schweizer Firmen zeigen. Das hat Relevanz.

## Knackpunkt
Das Ergebnis wird bei weitem nicht abschliessend sein. Weil nur Besitz von 3, 5 oder mehr Prozent an einer börsenkotierten Firma gemeldet werden muss, bleibt ein sehr grosser Anteil der Besitzverhältnisse im Dunkeln. Dies nennt man Streubesitz.

## Briefing-Gespräch:
Mit Julian Chan, Mediensprecher SIX Group:
"Knackpunkte sind grundsätzlich folgende: Es sind einfach die neuesten Meldungen, aber das heisst nicht, dass sie aktuell sind. Denn Meldungen müssen nur gemacht werden, wenn eine der Schwellen, also bei 3 oder 5 Prozent oder darüber, über oder unterschritten wird. Wenn sich die Anteile zwischen den Schwellen verschieben, braucht es keine Meldung. Ausserdem werden die Meldungen von den Firmen selbst verfasst, wir publizieren sie nur. Das heisst, sie sind auch nicht einheitlich."
"Die Daten können wir leider nicht zur Verfügung stellen, wir haben sie nicht so strukturiert."

## Datensatz:
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
