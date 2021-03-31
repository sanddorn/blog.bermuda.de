---
title: "Testen in Produktion?"
date: 2021-03-13T12:10:03+01:00
draft: true
toc: true
authorbox: false
Categories:
  - "Development"
  - "Testing"
  - "Monitoring"
share:
  twitter: true
  pocket: true
  xing: true
  linkedin: true
---
Testen in Produktion ist für viele Entwickler ein Tabu. 
*Sowas macht man nicht!*

Testen findet in der Entwicklungs- und der Integrations-Stage statt, um nur funktionsfähige Software in Produktion zu haben.
Außerdem -- welcher Entwickler will schon nachts um 3 aus dem Bett geklingelt werden, nur weil die Produktion einen Hick-Up hat...

## Ist funktional getestet wirklich genug?

Natürlich ist die Funktionalität unserer Software über Unit-Tests vollständig abgesichert. 
Das lässt sich sofort in der Testabdeckung überprüfen. 
Fraglich ist nur, ob wir da nicht etwas übersehen.

Wer sich an die „Gute Alte Zeit“ erinnert, am Ende einer Entwicklung stand ein längerer Test- und Qualitätssicherungszeitraum.
Innerhalb dieser Zeit wurde die neue Software nicht nur im Zusammenspiel mit Infrastruktur und Trabantensystemen überprüft, sondern auch das Zeit- und Lastverhalten.
Diese Testzyklen bedürfen nicht nur eigener Test-Hardware, sondern auch eine große Menge an Zeit. 
Häufig sind in diesen Zyklen Wochen oder gar Monate verbraucht worden. 

## Beschleunigung des Deployments hat Auswirkungen auf den Test

Bei dem Bedürfnis, neue Features möglichst schnell dem Kunden zur Verfügung zu stellen, sind Testzyklen im Wochenbereich nicht darstellbar.
Es muss dabei wohl eine Lösung gefunden werden, die Testzyklen deutlich zu verkürzen.
Daher verzichten viele Projekte komplett auf Lasttests. 
Natürlich ist es richtig, dass schwergewichtige Lasttests nicht in einen möglichst leichtgewichtigen Entwicklungsprozess passen.
Damit ist natürlich die Sicherheit, eine performante Software zu erhalten, reine Glückssache -- bzw. liegt an der Erfahrung der Entwickler.

Es muss also eine Lösung gefunden werden, mit der man Performance messen und steuern kann, ohne den Prozess unnötig zu verlangsamen. 

## Wie viel Lasttest ist nötig?

Dazu müssen wir uns natürlich fragen, wie viel Lasttest ist nötig und vor allem, welche Art von Lasttest ist überhaupt sinnvoll.
Schauen wir noch einmal zurück, in die „Gute Alte Zeit“. 
Dort wurden -- so vorhanden -- Daten aus dem Produktivsystem in das Lasttestsystem kopiert und genutzt.
Damit sind dort realistische Daten und Anfragen zur Simulation vorhanden.
Eine einfache Kopie von Produktivdaten ist natürlich nicht mehr DSGVO (oder GDPR) konform.
Sobald wir allerdings anfangen, die Daten zu verändern -- zu anonymisieren, so fangen wir schon an zu verändern.

Haben wir noch keine Produktivdaten, so müsste mit viel Aufwand artifizielle Daten erschaffen werden. 
Nur was gibt uns die Sicherheit, überhaupt realistische Daten zu erzeugen?
Somit ist ein Lasttest mit künstlichen Daten immer mit großen Unwägbarkeiten verbunden.
Wie auch schon Donald Knuth in [[1]](#references) gesagt hat: „Premature optimization is the root of all evil“.



## Monitoring -- ist das etwas wie Test in der Produktion?


## References
[1]: Donald Knuth. The Art Of Computer Programming. Addison-Wesley, 1968 
