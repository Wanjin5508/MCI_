# Übung 1 - UCD
## 1.1 Sammlung von Methoden von UCD recherchieren
|**Phase**|**Unterpunkt der Phase**|**Input**|**Output**|**Methoden**|**Kosten**|
|---|---|---|---|---|---|
|**Understanding Context**|_Identifikation der primären Nutzer des Produktes_|Marktforschung|Benutzerprofile, Zielgruppendefinition|- Ethnografische Studien  <br>- Kontextuelle Interviews  <br>- Stakeholder-Analysen  <br>- Szenarien und Use Cases|Hoch, da immer Nutzer und deren Umfeld betrachtet werden muss|
||_Warum diese das Produkt nutzen_|Interviews, Umfragen, Verhaltensanalysen|Benutzermotivationen und Ziele|||
||_Was deren Ansprüche an das Produkt sind_|Anforderungsanalysen, Benutzerfeedback|Liste von Benutzeranforderungen und -erwartungen|||
||_In welchem Umfeld sie das Produkt nutzen_|Kontextanalysen, ethnografische Studien, Nutzerbeobachtungen|Kontextinformationen, Szenarien|||
|**Nutzeranalyse**|_Genauere Spezifikation der Ansprüche an das Produkt_|Benutzeranforderungen, Benutzerprofile|Detaillierte Benutzeranforderungen, Benutzersegmente, Use Cases|- Nutzerinterviews  <br>- Umfragen  <br>- Personas  <br>- Nutzerreisen (User Journeys)|Mittel bis Hoch, etwas geringer, da zum Beispiel Omnibusbefragungen genutzt werden können|
|**Designphase**|_Iterativer Prozess des Designs und der Entwicklung_|Detaillierte Benutzeranforderungen, Benutzerprofile, Kontextinformationen|Prototypen, Wireframes, Interaktionsdesign, Informationsarchitektur, Entwurfsdokumentation|- Prototyping (Papierprototypen, digitale Prototypen)  <br>- Wireframing  <br>- Storyboarding|Mittel bis Hoch|
|**Evaluationsphase**|_Feedback der Nutzer durch Usability-Studien_|Funktionsfähige Benutzeroberfläche, Testpläne|Usability-Berichte, Fehlerberichte, Designverbesserungen|Usability-Tests  <br>Heuristische Evaluation  <br>Expertenbewertung (Expert Review)  <br>A/B-Tests|Hoch, da Umsetzung meist mit mehr Problemen einhergeht als vorher angenommen|


## 1.2 Bei welcher Art Softwareprojekt findet der UCD-Prozess Anwendung?

### Bei welcher Art Softwareprojekt findet der UCD Prozess Anwendung? Und umgekehrt: Bei welcher nicht?

Da die *Benutzerfreundlichkeit* und *Akzeptanz* durch den Endnutzer beim UCD im Mittelpunkt steht, werden vor allem solche Produkte durch das UCD profitieren und mit diesem Modell entwickelt, z.B:

> **Software für Endanwender:** UCD ist besonders wichtig bei Software, die von Endbenutzern in ihrem täglichen Leben oder Arbeitsumfeld verwendet wird, wie mobile Apps, Webanwendungen, Bürosoftware und Unterhaltungssoftware.

> **E-Commerce- und Online-Shops:** Die Gestaltung einer benutzerfreundlichen Benutzeroberfläche und einer reibungslosen Kaufabwicklung ist entscheidend für den Erfolg von E-Commerce-Plattformen.

> **Gesundheitswesen und Medizinische Anwendungen:** In diesen Projekten ist die Benutzersicherheit und die einfache Bedienbarkeit von größter Bedeutung.

> **E-Learning und Bildung:** Die Gestaltung von E-Learning-Plattformen und -Anwendungen erfordert eine hohe *Benutzerfreundlichkeit*, um die Lernziele der Benutzer zu erreichen.

> **Soziale Netzwerke und Kommunikationsanwendungen:** Eine gute Usability und ein positives Benutzererlebnis sind entscheidend für den Erfolg von Plattformen wie sozialen Netzwerken und Messaging-Apps.

> **Innovative Start-ups:** Start-ups, die innovative Softwarelösungen entwickeln, legen oft großen Wert auf Benutzerfeedback und Benutzerzentriertheit, um ihren Wettbewerbsvorteil zu stärken.

Weniger relevant ist das UCD z.B. bei folgenden Anwendungsbereichen: (Allerdings kann UCD auch hier von Vorteil sein, um Effektivität und Effizienz des Produktes zu steigern)

> **Interne Entwicklungs- und Verwaltungs-Tools:** Tools, die von Entwicklern oder Administratoren zur Verwaltung von Systemen oder Prozessen verwendet werden, legen normalerweise weniger Wert auf eine aufwändige Benutzeroberflächengestaltung.

> **Hochspezialisierte Tools:** In einigen Fällen können hochspezialisierte Softwarelösungen entwickelt werden, bei denen die Benutzerbasis sehr begrenzt ist und die Anforderungen und Erwartungen der Benutzer bereits stark definiert sind.

### Wie lässt sich UCD in typischen Prozessmodellen zur Softwareentwicklung praktisch integrieren?

**Wasserfallmodell:**

- UCD-Phasen vor dem Entwurf und der Entwicklung durchführen, um die Anforderungen und Benutzerbedürfnisse zu verstehen.
- Integration des Benutzerfeedbacks in jede Phase, um sicherzustellen, dass das Design den Bedürfnissen der Benutzer entspricht.

**Iterative und inkrementelle Modelle (z. B. Agile, Scrum):**

- UCD kann leicht in *iterative Modelle* integriert werden, da es auf kontinuierlichem *Benutzerfeedback* und wiederholten Verbesserungen basiert.
- Planen Sie regelmäßige Benutzertests, Expertenbewertungen und Design-Überarbeitungen in den Entwicklungszyklus ein.

**V-Modell (V-Modell XT):**

- UCD-Phasen können parallel zu den jeweiligen Entwicklungsphasen des V-Modells durchgeführt werden.
- Benutzerakzeptanztests können die Validierung der Benutzeranforderungen und des Systemdesigns unterstützen.

**Rapid Application Development (RAD):**

- UCD kann gut in RAD integriert werden, da es auf schnellen Iterationen und Prototyping basiert.
- Verwenden Sie Prototypen, um Benutzerfeedback zu sammeln und das Design kontinuierlich zu verbessern.

**DevOps und Continuous Integration/Continuous Deployment (CI/CD):**

- Integrieren Sie UCD-Prinzipien in den gesamten DevOps-Prozess, um sicherzustellen, dass Benutzerfreundlichkeit und Benutzerfeedback in der Softwareentwicklung und -bereitstellung berücksichtigt werden.
- Nutzen Sie A/B-Tests und Benutzerfeedback in der Produktionsumgebung, um das Produkt kontinuierlich zu optimieren.

**Mögliche Schlüssel zur erfolgreichen Integration von UCD in diese Prozessmodelle:**

- Regelmäßige Benutzerbeteiligung und kontinuierliches Benutzerfeedback in allen Phasen.
- Die Schaffung eines interdisziplinären Teams, das Designer, Entwickler und Benutzerexperten zusammenbringt.
- Die Integration von UCD-Aktivitäten in den Projektplan und die Ressourcenallokation.
- Die Betonung der Bedeutung der Benutzerfreundlichkeit und der Benutzerzentriertheit im gesamten Entwicklungsprozess.


## 1.3 Projektidee für MCI-Übung entwickeln
- Finanzhandelssoftware für blinde Benutzer
- ToDo App mit Sprachassistenten
- ==Memory Spiel für Behinderte/Eingeschränkte Personen==
- medizinische Gesundheits-App für ältere Menschen mit leicht verständlichen Grafiken und sprachgestreuten Anleitungen
- intelligentes Haussteuerungssystem für Behinderte

---
# Übung 2 - Kontext
## Übung 2

### Aufgabe 2.1 - Kontext verstehen

**Ziel** ist die Entwicklung eines Verständnisses für die Nutzungsumstände für Ihr spezifisches System. Spezifizieren Sie daher den Kontext zum System durch die Beantwortung der nachfolgenden Fragen.

#### Wer sind die primären Nutzenden des Systems?

- Kinder
- geistig & körperlich behinderte Personen
- Betreuende Personen
- Familienangehörige
- Senioren
- Alzheimer Patienten

#### Weshalb wollen die Nutzenden das System einsetzen (Motivation)?

- Spaß & Zeitvertreib
- Lernen von Wörtern & Bildern
- Wissen vermitteln
- Gedächtnisleistung verbessern

#### Wofür wollen die Nutzenden das System einsetzen (Aufgaben)?

- Konkrete Aufgaben sind ähnlich wie bei einigen Sport- und Fitness-Apps, die durch tägliche Aufgaben das Denkvermögen und die Gedächtnisleistung der Benutzer trainieren, um die geistige Gesundheit zu gewährleisten.

#### In welcher Umgebung wollen die Nutzenden das System einsetzen (Umgebung/Kontext)?

- Schule / Betreuungsstätte
- Zu Hause
- mit Freunden

### Aufgabe 2.2 - Aufgaben analysieren

> Entwickeln Sie ein Verständnis für die Art und Weise der Aufgabenbewältigung, indem Sie eine Hierarchische Taskanalyse (HTA) für die ermittelten Aufgaben Ihres Systems durchführen.

1. Jede Aufgabe spannt einen separaten HTA Baum auf (Root Element).

2. Teilen Sie die Aufgaben systematisch in mehreren Schritten (mehrere Ebenen) in Teilaufgaben. Sie bestimmen den Detailgrad, der für ein Prozessverständnis notwendig ist. 
3. Notieren Sie Timing Labels für sequenzielle, parallele der alternative Abläufe an den inneren Konten. 
4. Zusatz: Überprüfen Sie die Blattknoten Ihrer HTA. Notieren Sie die Zuständigkeiten dieser Teilaufgaben.

![[Pasted image 20231116125426.png]]

--- 
# Übung 3 - Nutzende
## Persona 1: Maria - Geistig und körperlich behinderte Person

![[Pasted image 20240130205039.png|400]]

- **Alter:** 35
- **Beruf:** Friseurin (Teilzeit in einer Werkstatt für Menschen mit Behinderungen)
- **Einkommen:** Durchschnittliches Einkommen durch ihre Teilzeitarbeit
- **Familienstatus:** Ledig
- **Wohnort:** Kleinstadt in Deutschland

**Kontext:** Maria leidet an einer geistigen und körperlichen Behinderung, die ihre Mobilität beeinträchtigt. Sie sucht nach Aktivitäten, die ihre kognitiven Fähigkeiten verbessern und gleichzeitig Spaß machen.

**Bedürfnisse/Ziele:** Maria spielt das Memory-Spiel, um ihre Konzentration und Erinnerungsfähigkeiten zu stärken. Sie möchte auch eine Möglichkeit finden, sich zu entspannen und positive Erfahrungen zu sammeln.

**Kenntnisse im Umgang mit Apps:** Maria hat grundlegende Kenntnisse im Umgang mit Touchscreen-Geräten und nutzt sie regelmäßig für einfache Anwendungen.

**Ängste:** Maria fürchtet, aufgrund ihrer Behinderung nicht in der Lage zu sein, das Spiel effektiv zu spielen, und Angst vor Frustration und Misserfolg.

## Persona 2: Herr Müller - Senior mit Alzheimer
![[Pasted image 20240130205109.png|400]]

- **Alter:** 75
- **Beruf:** Pensionierter Lehrer
- **Einkommen:** Rente
- **Familienstatus:** Verwitwet, zwei erwachsene Kinder
- **Wohnort:** Vorort in Deutschland

**Kontext:** Herr Müller leidet an Alzheimer und hat Schwierigkeiten, sich an alltägliche Dinge zu erinnern. Er sucht nach spielerischen Aktivitäten, die seine kognitiven Fähigkeiten fördern und ihm Freude bereiten.

**Bedürfnisse/Ziele:** Herr Müller spielt das Memory-Spiel, um sein Gedächtnis zu trainieren und Momente der Freude zu erleben. Er hofft, durch regelmäßiges Spielen seine geistige Gesundheit zu unterstützen.

**Kenntnisse im Umgang mit Apps:** Herr Müller hat begrenzte Erfahrung mit Apps, benötigt jedoch eine benutzerfreundliche Oberfläche, die einfach zu bedienen ist.

**Ängste:** Herr Müller fürchtet, dass seine Alzheimer-Symptome seine Fähigkeit beeinträchtigen könnten, das Spiel zu verstehen, und hat Angst vor der Verschlechterung seiner geistigen Fähigkeiten.

## Persona 3: Emma - Kind
![[Pasted image 20240130205152.png|400]]

- **Alter:** 8
- **Beruf:** Schülerin
- **Einkommen:** Keines
- **Familienstatus:** Einzelkind, Eltern sind berufstätig
- **Wohnort:** Stadtrand in Deutschland

**Kontext:** Emma ist ein aufgewecktes Mädchen, das gerne spielt und neugierig auf die Welt ist. Sie sucht nach unterhaltsamen Aktivitäten, die sie gemeinsam mit ihren Eltern oder alleine spielen kann.

**Bedürfnisse/Ziele:** Emma spielt das Memory-Spiel, um Spaß zu haben, ihre Aufmerksamkeit zu schärfen und ihr Gedächtnis zu verbessern. Sie möchte auch etwas Neues lernen, während sie spielt.

**Kenntnisse im Umgang mit Apps:** Emma ist technikaffin und hat bereits Erfahrung mit verschiedenen Apps und Spielen auf Tablets und Smartphones.

**Ängste:** Emma hat Angst davor, dass das Spiel zu schwierig sein könnte und sie sich langweilt. Sie möchte Spiele, die herausfordernd, aber auch altersgerecht sind.

## Persona 4: Familie Schneider - Familienangehörige von geistig behinderten Personen
![[Pasted image 20240130205219.png|400]]

- **Alter:** Eltern (40 und 42), Kind (10) mit geistiger Behinderung
- **Beruf:** Vater - Büroangestellter, Mutter - Hausfrau (Teilzeit)
- **Einkommen:** Durchschnittliches Familieneinkommen
- **Familienstatus:** Familie mit einem Kind
- **Wohnort:** Vorort in Deutschland

**Kontext:** Die Familie Schneider engagiert sich stark für die Förderung ihres geistig behinderten Kindes und sucht nach geeigneten Aktivitäten, die die ganze Familie gemeinsam genießen kann.

**Bedürfnisse/Ziele:** Die Familie spielt das Memory-Spiel, um gemeinsam Zeit zu verbringen, die kognitiven Fähigkeiten des Kindes zu unterstützen und eine positive Atmosphäre zu schaffen.

**Kenntnisse im Umgang mit Apps:** Die Eltern haben grundlegende Kenntnisse im Umgang mit Apps, während das Kind bereits mit spielerischen Anwendungen auf Tablets vertraut ist.

**Ängste:** Die Familie fürchtet, dass das Kind sich ausgeschlossen fühlen könnte, wenn es Schwierigkeiten beim Spielen des Memory-Spiels hat. Sie haben Angst vor Frustration und wollen sicherstellen, dass das Spiel für alle Familienmitglieder geeignet ist.

---

# Übung 4 - Design
## Aufgabe 4.1 Open Card Sorting durchführen
--> [[aufgabe_1.pdf|Open Card Sorting]]

## Aufgabe 4.2 Lo-Fi-Prototyp erstellen
![[Pasted image 20240130210021.png|400]]

LoFi-Prototype: file:///Users/wanjinli/Library/CloudStorage/OneDrive-个人/桌面/WS%20%202324/WS_2324/MCI/MCI_Ü/UE4/Uebung4.2/home.html

Mock-up: [[Aufgabe 4.2.pdf]]
## Aufgabe 4.3 State chart erstellen
### Taste / Bedienelemente
- operate
- tapeIn
- record
- stop_eject. --> 弹出
- rewind --> 倒带
- play
- pause
- fastForward

### Zustand
insgesamt 14 Zustände + 48 Transitionen
1. ausgeschaltet
2. eingeschaltet
3. tape eingelegt
4. kein Tape eingelegt
5. wiedergebend
6. beschleunigte Wiedergabe
7. zurückgehende Wiedergabe
8. angehaltene Wiedergabe
9. vorgespultes Tape
10. zurückgespultes Tape
11. beendete Wiedergabe
12. normaler Modus der Aufnahme
13. automatischer Modus der Aufnahme
14. pausierte Aufnahme

![[Pasted image 20240130211135.png]]

---

# Übung 5 - Evaluation und Statistische Grundlagen
## 5.1 Evaluation
-> TLX
![[Pasted image 20240201134022.png]]


-> SUS
![[Pasted image 20240130211822.png]]
## 5.2 Statistik
https://github.com/Wanjin5508/MCI_/blob/main/MCI_Ü/UE5/mci_5_2/mci_5_2.ipynb

---
