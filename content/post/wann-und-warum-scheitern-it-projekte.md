---
title: "Wann Und Warum Scheitern It Projekte"
date: 2015-04-08T21:57:46+02:00
draft: false
tocOpen: true
share:
    facebook: true
    twitter: true
Categories:
  - "Business"
  - "Project"
---

In verschiedenen Studien wird eine Versagensquote von ca. 50-70 % bei IT Projekten festgestellt. 
Das heißt, dass nicht einmal die Hälfte aller IT Projekte das gewünschte Ziel erreicht. 
Eine Studie [[1]](#references) zeigt, dass kein signifikanter Zusammenhang zwischen Vorgehensmodell und Projekterfolg feststellbar ist. 
Das lässt die Frage offen, welche Faktoren zum Projekterfolg oder Projektmisserfolg führen. 
In [[2]](#references) wird auf mangelnde Kommunikation und mangelndes Vertrauen hingewiesen.

Diese Probleme sind meiner Meinung nach aber nur ein Symptom, nicht Ursache des Problems. 
Die Ursache findet sich deutlich tiefer, sprich früher im Projekt. 
Eine dieser Ursachen könnte sich bereits in der Auswahl der Projektmitarbeiter finden. 
Zum Nachweis dieser Behauptung möchte ich etwas weiter ausholen. 
Zunächst sollte man dazu die gebotenen Einkaufspreise für IT Berater und deren gewünschte Qualifikation betrachten.  
Fangen wir also mit den Einkaufspreisen an. 
Die Stundensätze, von denen hier geschrieben wird, sind mir persönlich angeboten worden.

# Einkaufspreise

Diese Stundensätze bewegen sich im Bereich von um die 50 € für einen Java/J2EE Entwickler (auf die Qualifikationen werde ich später eingehen). 
Für einen Angestellten mag ein Stundenlohn von 50 € geradezu verführerisch wirken. 
Daher möchte ich aus Unternehmersicht eine kurze Rechnung dazu aufstellen. 
Ich lege eine optimistische Auslastung von 80 % zugrunde, sowie den Stundensatz von 50 €. 
Bei 220 Arbeitstagen pro Jahr (nach Abzug der 30 Tage Urlaub) bleiben 176 fakturierbare Arbeitstage à 8h.

Zur Durchführung der Tätigkeiten werden wahrscheinlich Mitarbeiter eingesetzt, die zumindest einen Bachelor-Abschluss haben. 
Einstiegsgehälter für Bachelor IT Absolventen liegen zwischen 39000 € und 45000 €. 
In dieser Beispielrechnung nehmen wir einen Wert aus dem unteren Quartil und weil es eine einfach zu merkende Zahl ist, fixieren wir das Brutto-Gehalt des Mitarbeiters auf 40000 €. 
Es kommt zusätzlich zu dem Gehalt noch die arbeitgeberfinanzierten Nebenkosten wie Krankenversicherung, Rentenversicherung, Arbeitslosenversicherung sowie einige kleinere Umlagen (insg. 28 % [[3]](#references)). 
Damit kostet dieser Berufseinsteiger 51200 €.

Eine Renditebetrachtung findet sich in der folgenden Tabelle.

| AUFWAND | BERECHNUNGSGRUNDLAGE | SUMME |	EINNAHMEN |
| --------| -------------------- | ------ | --------- |
| Umsatz	| 176 (d)* 8 (h) * 50 € | 70400 € | 70400 € |
| Hotelkosten |176 (d) * (4/5) * 75 € |	10560 € |59840 € |
| Reisekosten |	36 (W) * 100km *0,30 € | 1080 € | 58760 € |
| Betriebliche Versicherungen | Schätzung | 2500 € | 56260 € |
| Fortbildungen	| Schätzung	|2500 € | 53760 € |
| Lohn incl. Lohnnebenkosten |	| 51200 € | 2560 € |

Damit bleiben als Rendite für den Angestellten gerade einmal 5 %. 
Das ist immerhin etwas mehr als man für festangelegtes Kapital erhalten würde, letzteres ist aber auch sicher verzinst.

# Qualifikation

Wir haben eben angenommen, dass wir einen Berufsanfänger mit Bachelor-Abschluss als Referenz annehmen. 
Es folgen auszugsweise Zitate aus den Ausschreibungen.

## Erste Ausschreibung

* schnellstmöglich erfahrene Java Entwickler
* Java (gute Kenntnisse/Projekterfahrungen)
* JavaScript (gute Kenntnisse/Projekterfahrungen)
* Backend: Hibernate, SQL Erfahrung, Grails
* Englisch (optional)

Wenn die Studienarbeiten nicht zu den Projekterfahrungen zählen, kommt der angenommene Mitarbeiter für diese Anfrage erst gar nicht in Betracht.

## Aus einer anderen Anfrage:

* Erfahrung in DB2
* Erfahrung in JEE
* Erfahrung in Hibernate

Auch hier sind Erfahrungen gefragt. 
Allerdings stellt sich mir hier noch eine weitere Frage. 
Der Kunde schafft eine große (teure) Datenbank an, sicherlich keine schlechte Idee, spart dann aber deutlich an der Expertise seiner Mitarbeiter. 
Eine schnelle Datenbank mit schlechtem Design kann weniger gefühlte Leistung erbringen als eine kostenfrei verteilte (z.B. postgreSQL oder MySQL) und dafür geschickt aufgesetzt und mit gutem Datenbankdesign versehen.

Lassen Sie mich den Vergleich ziehen, niemand käme auf die Idee einem Fahranfänger ein Formel 1 Auto zu überlassen. 
Hier wird einem Einsteiger aber das größte und teuerste Datenbank-System an die Hand gegeben, das man bekommen kann.

Geht die IT Industrie etwa immer noch davon aus, dass die Expertise auf dem Softwaremarkt zu beschaffen ist? 
Dies mögen uns Hersteller von Software zwar gerne suggerieren, aber das beste Werkzeug kann seine wirkliche Qualität erst in der Hand des Meisters beweisen.

## Und ein weiteres Beispiel:

* Erfahrung in SOA Projekten
* Expertenwissen in der Programmiersprache Java
* Expertenwissen in Bezug auf zeitgemäße Methoden der Softwareentwicklung
* Idealerweise Erfahrung in agil durchgeführten Projekten
* Erfahrung in Projekten im Bahn Umfeld
* Kenntnisse über allgemeine Regularien und Besonderheiten rund um das Thema […]
* JAVA
* JAVA Server Pages
* STRUTS
* Spring

Insgesamt sicher keine übermäßig komplexe Anforderung. 
Allerdings sind diese auch nicht durch den Berufsanfänger zu leisten, den wir uns mit Ach und Krach für den Stundensatz leisten können.

Gesetzt den Fall, als Bieter auf das Projekt bin ich entsprechend skrupellos und biete meinen Anfänger an, was bekommt dann der Kunde? 
Er bekommt einen Berufsanfänger als „Experten“ und „erfahrenen“ Entwickler. 
Der Kunde wird ihn auf seine Kosten weiterbilden, im Sinne eines „Trainings on the job“, sofern er ein paar wirklich erfahrene Mitarbeiter hat. 
Wenn nicht, naja.

Bedenkt man weiter, dass wir das Gehalt im unteren Quartil angenommen haben, so sollten wir nicht annehmen einen 1’er oder 2’er Kandidaten zu bekommen. 
Die Benotung des Studiums mag keinen Aufschluss über die weitere Berufslaufbahn geben, aber es ist doch eher wahrscheinlich, dass jemand, der während des Studiums kein besonderes Eigeninteresse gezeigt hat, diese Eigeninteresse gerade im Job zeigt.

# Ergebnis

Schon weit bevor sich der erste Projektmitarbeiter an den Schreibtisch setzt, kann das Scheitern des Projekts schon vorprogrammiert sein. 
Wie in [[2]](#references) angesprochen, steht und fällt ein Projekt mit den sogenannten weichen Faktoren aus Kommunikation und Vertrauen. 
Das Vertrauen kann aber bei Auswahl der Projektmitarbeiter und ohne deren aktive Mitarbeit schon gestört sein, weil die vermeintlichen Experten doch nur Anfänger sind.

Diese Ausführungen sollen nicht sagen, dass man keine Berufsanfänger (Junior) ins Team aufnehmen sollte, ganz im Gegenteil, diese können ein Team maßgeblich bereichern. 
Nur sollte man sich überlegen, dass erfahrene Mitarbeiter auch entsprechend entlohnt werden wollen. 
Das ist nicht nur fair, sondern wahrscheinlich auch zielführender als der Sparzwang, der aus einer hohen Quote an Projektabbrüchen herrührt. 
Das Leiden des Sparzwangs ist, wie oben hergeleitet, ja auch eher ein „hausgemachtes“ Problem.

Um ein Projekt möglichst günstig durchzuführen, ist es nicht sinnvoll ausschließlich am Einkaufspreis der Mitarbeiter zu sparen.

Allen Projektdurchführenden wünsche ich viel Glück bei der Auswahl der Partner und Mitarbeiter.

# References

[1]: Gulp. (2006, Jan.) Erfolgs- und Misserfolgsfaktoren bei IT-Projekten. https://www.gulp.de/knowledge-base/rund-ums-projekt/erfolgs-und-misserfolgsfaktoren-bei-it-projekten-teil-1.html#item-10

[2]: Dr. Eberhard Huber Cleo Becker. Die Bilanz des (Miss)-Erfolges in IT-Projekten. http://d-nb.info/99200375X/34

[3]: Wikipedia. Lohnnebenkosten. http://de.wikipedia.org/wiki/Lohnnebenkosten
