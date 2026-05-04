# Das Software Engineering Literatur-Repro

Auf diesem Repository finden Sie viele nützliche Links, Publikationen und Hinweise rund um meine 
Vorlesungsreihe Software Engineering. Diese Quellen-Sammmlung wird kontinuierlich 
und semesterübergreifend von mir gepflegt. Die aktuellen Folien zu der Vorlesung im aktuellen 
Semester finden Sie auf dem LEA-Kurs der jeweiligen Veranstaltung.
<br>
Diese Seite wird ständig aktualisiert. 

## Inhaltsverzeichnis
Das vorliegende Inhaltsverzeichnis orientiert sich an der thematischen Gliederung meiner 
Lehrveranstaltungen Software Engineering 1 und 2, welche ich an der Hochschule Bonn-Rhein-Sieg 
unterrichte.   
<!-- TOC -->
* [Das Software Engineering Literatur-Repro](#das-software-engineering-literatur-repro)
  * [Inhaltsverzeichnis](#inhaltsverzeichnis)
* [Quellen und Links zur Vorlesung Software Engineering 1 (SE-1)](#quellen-und-links-zur-vorlesung-software-engineering-1-se-1)
  * [Kapitel 1: Einführung ins Software Engineering](#kapitel-1-einführung-ins-software-engineering)
  * [Kapitel 2: Software-Prozessmodelle im Software Engineering](#kapitel-2-software-prozessmodelle-im-software-engineering)
  * [Kapitel 3: Modellierung und Erhebung von Anforderungen (Requirements Engineering Teil 1)](#kapitel-3-modellierung-und-erhebung-von-anforderungen-requirements-engineering-teil-1)
    * [Modellierung von Use-Cases mit UML](#modellierung-von-use-cases-mit-uml)
  * [Kapitel 4: Objektorientierte Analyse von Anforderungen](#kapitel-4-objektorientierte-analyse-von-anforderungen)
    * [Modellierung von Klassendiagrammen mit UML](#modellierung-von-klassendiagrammen-mit-uml)
    * [Objektorientiertes Analyse-Modell (OOA)](#objektorientiertes-analyse-modell-ooa)
  * [Kapitel 5: System Design (Grundlagen von Software-Architekturen)](#kapitel-5-system-design-grundlagen-von-software-architekturen)
  * [Kapitel 6: Objektorientiertes Design (Grundlagen und Entwurfsmuster (Design Pattern))](#kapitel-6-objektorientiertes-design-grundlagen-und-entwurfsmuster-design-pattern)
    * [Design Pattern (Entwurfsmuster)](#design-pattern-entwurfsmuster)
  * [Kapitel 7: Testen von Software (Grundlagen, Methoden und Tools)](#kapitel-7-testen-von-software-grundlagen-methoden-und-tools)
    * [Testfall-Erzeugung](#testfall-erzeugung)
  * [Kapitel 8: Nachhaltigkeit von Software (Refactoring und Software-Wartung)](#kapitel-8-nachhaltigkeit-von-software-refactoring-und-software-wartung)
* [Quellen und Links zur Vorlesung Software Engineering 2 (SE-2)](#quellen-und-links-zur-vorlesung-software-engineering-2-se-2)
  * [Kapitel 2: Requirements Management](#kapitel-2-requirements-management)
  * [Kapitel 3: Usability (Entwicklung von graphischen Benutzeroberflächen)](#kapitel-3-usability-entwicklung-von-graphischen-benutzeroberflächen)
  * [Kapitel 4: Einführung in das Web-Engineering (Vaadin)](#kapitel-4-einführung-in-das-web-engineering-vaadin)
  * [Kapitel 5: Continuous Delivery (CI / CD)](#kapitel-5-continuous-delivery-ci--cd)
  * [Kapitel 6: Software-Metriken](#kapitel-6-software-metriken)
  * [Kapitel 7: Erweiterte Methoden der Software-Entwicklung](#kapitel-7-erweiterte-methoden-der-software-entwicklung)
* [Allgemeine Quellen und Links zum Thema Software Engineering](#allgemeine-quellen-und-links-zum-thema-software-engineering)
  * [KI im Bereich Software Engineering](#ki-im-bereich-software-engineering)
  * [Wichtige SE-Tools (Case Tools)](#wichtige-se-tools-case-tools-)
    * [Tools zur Modellierung von UML-basierten Diagrammen](#tools-zur-modellierung-von-uml-basierten-diagrammen)
* [Literaturverzeichnis](#literaturverzeichnis)
<!-- TOC -->

c/o Prof. Dr. Sascha Alda, H-BRS. Ist ein Link "kaputt"? Dann bitte E-Mail an mich: sascha.alda [at]
h-brs.de

# Quellen und Links zur Vorlesung Software Engineering 1 (SE-1)

In diesem Bereich finden Sie Quellen und Links zu meiner Vorlesung Software Engineering 1, die 
ich regelmäßig im Wintersemester anbiete.

## Kapitel 1: Einführung ins Software Engineering
Die in der Vorlesung erwähnten Zitate rund um agile Software-Entwicklung ("Speed is everything", 
"[The end of agile!](https://janbosch.com/blog/index.php/2023/08/07/summer-reflections-the-end-of-agile/)" stammen von [Prof. Dr. Jan Bosch](https://www.chalmers.se/en/persons/janbo/), einem bekannten Professor aus der Chalmers 
University of Technology in Schweden. Viele gute Beiträge von ihm kann man aus seinem [Blog](https://janbosch.com/blog/) entnehmen. 

## Kapitel 2: Software-Prozessmodelle im Software Engineering

Das Wasserfallmodell wurde in einer ursprünglichen Version von den Software-Entwickler Royce 
vorgestellt [(Royce, 1970)](/papers/Royce,%201970.pdf). Das hier beschriebene Ablaufmodell mit 
dem Charakter eines Wasserfalls wird 
im Prinzip heute noch verwendet, lediglich haben sich die Bezeichnungen der Phasen geändert. 
Rücksprünge sind tatsächlich bei Royce schon vorgesehen - anders als in Industrie-Projekten, bei 
denen aus organisatorischen Gründen ein Rücksprung nicht mehr vorgesehen werden kann.  

Ein sehr guter und aktueller Vergleich zwischen Wasserfallmodell und modernen agilen 
Entwicklungsmodellen findet sich in dem guten Aufsatz von [(Mishra und Alzoubi, 2023)](/papers/Mishra%20und%20Azoubi%202023.pdf)).

Das Thema Security Touch Points ist in dem Buch von 
[(McGraw, 2005)](/papers/McGraw%202005.pdf) 
ausführlich beschrieben. Eine gute Erläuterung der Themen findet sich 
[hier](https://www.dcc.fc.up.pt/~edrdo/QSES1819/lectures/qses-02-sdlc_and_security.pdf).
Eine sehr gute Vorlesung im deutschsprachigen Raum wird von [Prof. Bodden](https://www.hni.uni-paderborn.de/sse/lehre/sse) angeboten. Diese ist 
anhand der [OWASP TOP 10](https://owasp.org/www-project-top-ten/) aufgebaut. 


## Kapitel 3: Modellierung und Erhebung von Anforderungen (Requirements Engineering Teil 1)
### Modellierung von Use-Cases mit UML
Für die Modellierung von Use-Cases (dt: Anwendungsfälle) haben sich UML-basierte 
Use-Case-Diagramme bewährt. Einen sehr guten Überblick liefert das Buch von Christin Rupp (Rupp, 
2012). 

## Kapitel 4: Objektorientierte Analyse von Anforderungen
### Modellierung von Klassendiagrammen mit UML
Für die Modellierung von Klassen haben sich UML-basierte
Klassen-Diagramme bewährt. Einen sehr guten Überblick liefert das Buch von Christin Rupp (Rupp,
2012).

### Objektorientiertes Analyse-Modell (OOA)
Das OOA abstrahiert von Anforderungen und liefert ein erstes Modell in Richtung der 
Implementierung. Das OOA wird auch als [Robustness Diagram](https://en.wikipedia.org/wiki/Entity-control-boundary) bezeichnet.
Assoziationen zwischen den Analyse-Klassen werden bei Brügge und Dutoit (2013) auf S. 211 
eingeführt, dies allerdings eher auf einem abstraken Niveau. Für eine praktische Anwendung muss man weitere Regeln beachten, die 
sich aus der Verwendung von [DTOs](https://martinfowler.com/eaaCatalog/dataTransferObject.html), 
aus den Annahmen von [Robustness-Diagrammen](https://en.wikipedia.org/wiki/Entity-control-boundary)
sowie aus der Praxis z.B. durch die Verwendung von 
[ORM-Technologien](https://de.wikipedia.org/wiki/Objektrelationale_Abbildung) ergeben. Diese Regeln führe ich meiner Vorlesung in Kapitel 4 ein.

## Kapitel 5: System Design (Grundlagen von Software-Architekturen)
Der Klassiker im Bereich Software-Architekturen ist und bleibt das sehr gute Buch von Gernot 
Starke, welches mittlerweile in der 10. Auflage erschienen ist (Starke, 2024). Dies sollte in 
jedem gut sorierten Bücherregal zu finden sein ;-) Falls kein Bücherregal vorhanden, dann kann man sich auch eine Online-Version 
anschauen ([Link in Bib](https://bib-discover.bib.h-brs.de/permalink/49HBZ_BRS/1hl68vi/alma991001257049706452)).

Einer der ersten Artikel über Software-Architekturen: [(Garlan and Shawn, 1994)](papers/Garlan%20and%20Shaw%201994.pdf).

Das Paper von [(Syromiatnikov, 2014)](/papers/Syromiatnikov,%202014.pdf) gibt einen guten 
Überblick über die verschiedenen Ausprägungen des [MVC](https://de.wikipedia.org/wiki/Model_View_Controller)-Musters.

Das MVC-Muster gilt heutzutage als Grundlage für verschiedene Web-Frameworks, welche das 
MVC-Pattern jedoch recht unterschiedlich auslegen. Eine Übersicht zu den bekanntesten 
Web-Frameworks auf dem Markt finden sie [hier](https://hotframeworks.com/) sowie auf den 
Trend-Seiten von [Stake-Overflow](https://survey.stackoverflow.co/2025/technology#1-web-frameworks-and-technologies).  

## Kapitel 6: Objektorientiertes Design (Grundlagen und Entwurfsmuster (Design Pattern))

### Design Pattern (Entwurfsmuster)
Das primäre Werk um die Thematik Design Pattern ist das berühmte Buch der [GoF](https://springframework.guru/gang-of-four-design-patterns/)-Autoren, allen voran 
[Erich Gamma](https://de.wikipedia.org/wiki/Erich_Gamma). Leider gibt es von dem Buch nur die 
erste Version, weitere Versionen wurden nie veröffentlicht. Es gibt aber eine Vielzahl von guten 
Sekundar-Quellen und Online-Quellen:

- [Seite](https://refactoring.guru/design-patterns) von Refacotoring Guru (sehr gute Darstellung 
  mit gute Code-Beispielen)

## Kapitel 7: Testen von Software (Grundlagen, Methoden und Tools)
### Testfall-Erzeugung
Die Anzahl Testfälle kann bei komplexen Anwendungssystemen aufgrund von vielfachen
Eingabe-Möglichkeiten (z.B. bei der Registrierung eines Benutzers) enorm groß werden. Eine Methode
zur Reduktion der Eingabe-Werte und somit zur Reduktion der Testfälle ist die Bildung von [Äquivalenzklassen](https://de.wikipedia.org/wiki/%C3%84quivalenzklassentest). Aus Äquivalenzklassen, welche
Eingabe-Werte zu einem Eingabe-Datum unterteilen, werden dann im nächsten Schritt konkrete
Testfälle abgeleitet.  Dazu werden sowohl gültige als auch ungültige Eingabe-Werte betrachtet.
Daraus können dann [Positiv-Testfälle](https://www.techtarget.com/searchsoftwarequality/tip/Positive-vs-negative-testing-Differences-and-examples) und [Negativ-Testfälle](https://de.wikipedia.org/wiki/Negativtest) abgeleitet werden. Eine sehr gute
Beschreibung liefert das Buch von Spillner und Linz (2019), hier vor allem
der [(Abschnitt 5.1)](/papers/Spillner%20und%20Linz,%202019,%20Kapitel%205-1%20Black%20Box%20Test.pdf)

## Kapitel 8: Nachhaltigkeit von Software (Refactoring und Software-Wartung)
tbc

# Quellen und Links zur Vorlesung Software Engineering 2 (SE-2)

In diesem Bereich finden Sie Quellen und Links zu meiner Vorlesung Software Engineering 2, die
ich regelmäßig im Sommersemester anbiete. Sie baut thematisch auf die Vorlesung Software 
Engineering 1 (WS) auf.

## Kapitel 2: Requirements Management
Das Thema KI und Requirements Engineering wird in dem [Buch](https://sophist.de/wissen/buch-ki-im-re/) von den SOPHISTen sehr gut aufgearbeitet.
Eine sehr gute Übersicht zu den Artikeln und Büchern von den SOPHSTen findet sich [hier](https://sophist.de/wissen/).

## Kapitel 3: Usability (Entwicklung von graphischen Benutzeroberflächen)
Sehr viele Arbeiten rund um Usability wurden von Jakob Nielsen beigesteuert. Grundlegendes Werk 
dazu: Nielsen, Jakob: Usability Engineering. Morgan Kaufmann, 1993.
Es werden auch aktuelle Arbeiten von seiner [Homepage](https://www.nngroup.com/) verwendet, auf der sehr viele Arbeiten und 
Paper verlinkt sind. 

Ein allgemeine Einführung zum Begriff Usability findet sich in diesem [Artikel von Nielsen von 2012](https://www.nngroup.com/articles/usability-101-introduction-to-usability/).

Der bekannteste Artikel von Nielsen sind die [10 Usability Heuristics for User Interface Design](https://www.nngroup.com/articles/ten-usability-heuristics/). Dieser Artikel wird regelmäßig 
aktualisiert und addressiert somit auch heute noch die wichtigsten Prinzipien zur Gestaltung von 
Benutzeroberflächen. Daneben gibt es ein gutes [Poster](https://media.nngroup.com/media/articles/attachments/Heuristic_Summary1_Letter-compressed.pdf), welches die 10 Heuristiken gut zusammenfasst.
Zudem gibt es für jede Heuristik ein eigenes Poster (herunterladbar als [ZIP-File](https://media.nngroup.com/media/articles/attachments/Jakob's10UsabilityHeuristics_AllPosters_5.zip)).

Speziell für die Entwicklung von Web-basierten Systemen gibt es einen ausführlichen 
[Web UX Style Guide](https://www.nngroup.com/articles/web-ux-study-guide/). Neben vielen Themen 
werden zum Beispiel die Vorteile des Musters [Breadcump Navigation](https://www.nngroup.com/articles/breadcrumb-navigation-useful/) vorgestellt.

Speziell für die [Entwicklung von KI-basierten Chatbots wurden ebenfalls 10 Heuristiken](https://www.nngroup.com/articles/ai-chatbots-design-guidelines/) 
entwickelt, die auch durch gute und moderne Beispiele umschrieben wurden.

Viele gute Heuristiken zur Gestaltung von Benutzeroberflächen werden auch bei (Starke, 2011), 
[Kapitel 7.7](/papers/Starke,%202011,%20Kap%207.7.pdf) gut und bündig beschrieben. Diese Quelle wird auch in der Vorlesung verwendet. 

In dem Artikel ([Le, Mayer et al., 2018](/papers/Fingers_Range_and_Comfortable_Area_for_One-Handed.pdf)) werden die wichtigsten Touch-Stellen in einer 
Mobile-Anwendung durch ein HeatMap-Analyse durchgeführt. In dieser Forschungsarbeit wurden 
allerdings nur Rechtshänder betrachtet, was sicherlich eine Limitierung darstellt.  

## Kapitel 4: Einführung in das Web-Engineering (Vaadin)
ToDo

## Kapitel 5: Continuous Delivery (CI / CD)
ToDo

## Kapitel 6: Software-Metriken
Todo

## Kapitel 7: Erweiterte Methoden der Software-Entwicklung
Todo

# Allgemeine Quellen und Links zum Thema Software Engineering
In diesem Bereich finden Sie Quellen und Links zu modernen Themen des Software Engineerings, die 
nicht direkt zu einem Kapitel aus einer Vorlesung verortet werden können.

## KI im Bereich Software Engineering
Ein kompletter Roundtrip von der Analyse von Anforderugen bis hin zur Auslieferung von Software 
mit Hilfe von KI-Tools wie [ChatGPT](https://chatgpt.com/auth/login) oder diverser Co-Pilot-Tools (z.B. [GitHub-CoPilot](https://github.com/features/copilot)) ist 
aktuell noch eine Illusion. Die Abbildung von informellen Wissen aus "den Köpfen der Kunden" auf 
formale Konstrukte (z.B. UML oder Java-Code) wird auf in Zukunft viele manuelle Aufgabe mit sich 
ziehen, die man im Software Engineering lernen muss. Ein visionäres Paper, wie so ein 
KI-unterstützer RoundTrip eines Software-Projektes aussehen könnte, liefert das Paper 
([Abdelfattah et al., 2024](/papers/Roadmap_for_Software_Engineering_Education_using_ChatGPT.pdf)).  

Eine [Untersuchung des Unternehmens Capgemini](https://www.bigdata-insider.de/wie-generative-ki-die-software-entwicklung-veraendert-a-1758fa47d007e68860c43dd9dc87affc/) zu den Einsatzmöglichkeiten von KI in der 
Software-Entwicklung stellt (Stand 2025) dar, dass Unternehmen durch den Einsatz von KI-Tools in 
der Software-Entwicklung eine Produktivitätssteigerung von 30% erreichen können.

Eine gute Referenz-Architektur zur Integration eines Large Language Modells (LLM) liefert das 
Paper von 
([Bucaioni et al., 2025](/papers/A_Functional_Software_Reference_Architecture_for_LLM-Integrated_Systems.pdf))
. Die dort beschriebene Referenz-Architektur liefert einen soliden und erweiterbaren Rahmen für 
die Bereitstellung von LLMs für interaktive Systeme. Durch die Einbindung einer 
Guardrail-Komponente können zudem wichtige sicherheitsrelevante Aspekte berücksichtigt werden. 
Weitere Infos über die Integration und Funktionalität einer Guardrail-Komponente finden sie auf 
der Seite von [Guardrails AI](https://github.com/guardrails-ai/guardrails). 


## Wichtige SE-Tools (Case Tools) 
### Tools zur Modellierung von UML-basierten Diagrammen

**Draw.io (heißt mittlerweile: Diagrams)**<br>
Schlankes browser-basiertes Tool, keine Installation auf ihrem Rechner notwendig! Abspeicherung der Dokumente in verschiedenen Formen möglich (Lokal, Cloud). Läuft nativ ohne Plugin auf allen gängigen Browsern.
<br>
Quelle: https://app.diagrams.net/


# Literaturverzeichnis

Hier eine Auflistung der wichtigen Quellen, die für das Software Engineering relevant sind. Alle 
Bücher können auch über 
[HBRS Bib Disover](https://bib-discover.bib.h-brs.de/discovery/search?vid=49HBZ_BRS:1044) online eingesehen werden.

Brass, L. et al.: _Software Architecture in Practice_. Addison Wesley; 4. Edition. 2021.
<br>
Bruegge, B.; Dutoit, A.H.: _Object-Oriented Software Engineering_. 3. Auflage, Prentice-Hall, 2013.
<br>
Rupp, Christin: _UML 2 glasklar: Praxiswissen für die UML-Modellierung_. Carl Hanser Verlag GmbH & 
Co. KG; 4 Edition, 2012.
<br>
Sommerville, Ian: _Software Engineering_. Pearson Studium; 10., aktualisierte Edition, 2018.
<br>
Starke, Gernot: _Effektive Software-Architekturen – Ein praktischer Leitfaden_. 10. Auflage, Hanser 
Verlag, 2024. (Anmerkung: auch die früheren Auflagen sind sehr gut und werden häufig verwendet)
<br>



