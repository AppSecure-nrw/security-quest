# new approach

1. don't optimize for the case we are right (rechne damit dass der Kunde die von dir gebaute Software so nicht haben moechte und baue sie dementsprechend dass es merkst und dass du sie anpassen kannst)
   - aktivitaeten die schnelles feedback geben vewenden (z.b. threat-model nicht immer neu machen, nur bestehendes erweitern)
   - Ignoranz ist eine vertahene Chance zum Lernen
      - mit den teams reden wo es nicht funktioniert und lernen warum es nicht funktioniert
2. focus on value, not cost or estimation
   - prio nach wert (sichtbar fuer den product owner)
      - risk leadership &| benefits richtig aufschreiben
      - shift left ist ein Masstab um den Wert zu sehen (Kostenersparnis durch fruehes Fehler finden)
3. create feedback loops to validate assumptions
   - literatur Recherche
      - zum Nutzen von Security Tools/Praktiken
      - zur Haeufigkeit von Security Problemen (OWASP Top 10, [DBIR](https://www.verizon.com/business/de-de/resources/reports/dbir/))
   - mit den teams reden wo es nicht funktioniert und lernen warum es nicht funktioniert
   - oeffentliche reviews von inhaltlichen Aenderungen machen (Regeltermin, Unternehmensuebergreifend mit Leuten die an den Belts arbeiten)
   - Belts muessen selber auch feedback den teams geben (ist ein Wert, sollte man frueh machen)
      - risk leadership
      - defect treatment (nicht als eigene activity sondern teil von activities die tools einfuehren oder weiter vorne machen)
4. make it economic to work in small batches
   - release/prod deploy darf nichts kosten (security risk sind auch kosten)
      - highlighten in den benefits: statt pentest mache xyz
   - ein belt ist aktuell nichts anderes als ein major release wo man wartet bis alle features da sind und dann erst feiert und feedback bekommt
   - belt level schraenken die Belohnung und Transparenz ein. es ist eigentlich eine Baumstruktur (Skillbaum)
5. enable an experimental approach to product development
   - psychological safety (Es braucht Akzeptanz dass etwas nicht zu 100% sicher ist)
      - Guide for the Security Deparment: Risiko-Kosten gegen Opportunitaetskosten abwegen (extrem: wenn die opportunitaetskosten groesser sind sollte man unsicher nach produktion gehen)
      - haeufige Implementierung: tools die die grossen Risiko-Kosten abfangen, in der CI/CD Pipeline laufen lassen. beim Rest fragen ob das wirklich notwendig ist
   - TODO wie machen wir das fuer die Belts?

## common

- Die Belts muessen sich parallel zum DevOps Reifegrad eines Teams entwickeln.
- Die Belts laufen parallel zur DevOps Journey.

## TODO

DevOps Reifegradmodell anschauen und schauen wie weit Security behandelt wird und ggf. dort contributen.

## Ideas

- In der Methodik sollte stehen, dass man nur die Dinge machen soll die nachweislich einen Wert haben. Also Implementieren und dann testen.
- In einer Belt Activity muss eine GuideLine stehen wie man den Value einer Aktivitaet erkennt. #AkzeptanzTest
- Wenn eine Aktivity fuer ein Team keinen Sinn macht, machen vielleicht auch darauf aufbauende, abhaenige oder Artverwandte Aktiviaeten auch keinen Sinn. In einem Skilltree kann man diesen Ast nicht weiter gehen.
- Aktivitaeten wo wir es nicht schaffen einen Test zu definieren wandern nicht ins Model.
- Nimm den Output einer Aktivitaet in deine Team Retro, besprecht zusammen den Value
- Wenn eine Activity staendig was finden/nueztlich ist, solltest du in dem Pfad besser werden
- Zweige sind bauen drauf ungeplante Arbeit zu reduzieren

## Weitere Ideen:
- Anmerkunden in die Aktivitaeten oder Aeste aufnehmen, wann man diese Aktivitaet(en) machen moechte (wie weit der DevOps Reifegrad sein sollte). Beisp.: Wenn du schon Cloud machst, dann willst du auch folgende Dinge machen: 1. SAST on Infrastructure Code, ... etc

## Erkenntnis:
- Teams die bereits Security Incidents hatten sind extrsinisch motiviert den Schmerz nach links zu shiften, von ungeplanter Arbeit in geplante Arbeit (wenn sie DevOps verstandnen haben)
- Security Skill Ast sollte Pain nach links shiften (ungeplante Arbeit zu geplanter Arbeit machen)

## Weitere Ideen:
- Es gibt keine Belt Assessments mehr, da es keine Belts mehr gibt.
- Es wird ein Review gemacht, wo ein Team - wenn es eine Activity fertig hat - vorstellt.
- Erwartungshaltung: Jedes Team arbeitet immer genau an einer Activity.
- Die Entscheidung eine Activity nicht zu machen soll in einem Review begruendet werden

## Weitere Ideen:
- Activities muessen eine Formel beinhalten wie der Value fuer das eigene Team/Product gemessen werden kann.
- Spaeter kann man dieses vielleicht im Review oder Tool gestuetzt einsammeln
- Wenn man Value einsammelt kann man spaeter Durchschnittswerte bilden und damit die Actitivities scoren.
- Jede Activity gibt am Anfang einen Punkt solange wir noch keine Value daten haben. Die Teams sind dann motiviert den Value zu messen um mehr Punkte zu bekommen.
- Belts/Raenge haben keinen Wert. Die Aussage, wie viele Punkte man hat reicht zur Vergleichbarkeit und Progressdarstellung. Nur als Gamification ansatz reicht uns das nicht als Begruendung diese mit aufzunehmen.

## Weitere Ideen:
Das Modell startet mit einer Must Activity die Methodik enthaelt (da niemand methodik liest).

- Risk Leadership https://github.axa.com/security-champions/SecurityChampions/issues/206
  - Onboard Management in Security
  - Continuously Improve
  - Review Activities

**Guide for the auditor:**
Das Modell hier gut implementieren und dann zeigen dass man die komischen Policies nicht mehr braucht.

## Feedback 1
Sorge:
- Leichte Sachen machen, um sich zu drücken
- Jeder sollte das ISMS kennen

### Feedback
- Unit Tests für Security Tests: Haben in vielen Teams keinen Nutzen, da sie keine Security Features haben. Daher wird der Wert dann gering eingeschätzt und das Team kann sagen, dass es dies nicht macht.
- "Ich such mir eine Aktivität" -> Es ist einfacher rein zu kommen, da man machen kann was einem Spaß macht
- Viel Freiheiten finde ich gut
- Persona hat X Y und Z implementiert statt Leitplanken
- Wenn man hängen bleibt braucht man einen Tritt, dass man weiter macht.

### Feature Request:
- Fortschrittstool

## Feedback 2

- Motivation ist wichtig
- Skillbaum ist eine gute Idee da man schauen kann was man als naechsten am liebsten macht
- Focus auf einzel Aktivitaeten kann man besser planen und schneller Feedback bekommen
- Gamification koennte hier super Motivation Treiber sein
  - alle *n* Activities einen neuen Rang, Item oder Goody bekommt
  - Leaderboard wo man sieht wie gut man ist
- Die Pfeilfarben sind eine gute Idee
- Die Activities sollten mehr Punkte bringen wenn sie mehr Wert schaffen
- Fuer den PO ist Risiko-Reduzierung nicht greifbar
- Wenn das Risiko in Euro ermittelt werden kann wird man sich vermutlich trotzdem fuer ein Feature entscheiden, auch wenn es weniger Geld einbringt

## Weitere Ideen:
- Ein Pfad koennte der Aufbau und die Teilnahme einer Gilde sein