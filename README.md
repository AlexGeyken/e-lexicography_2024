# e-lexicography_2024

## Vorbemerkung: 
Das Blockseminar e-lexicography gibt einen Überblick über die Geschichte der Lexikographie vom 19. Jh. bis heute, insbesondere mit Blick auf die technischen Entwicklungen.

(1) Das 19. Jh. ist das Zeitalter der "Großwörterbücher". Die Kultursprachen der Welt beginnen mit der "Vermessung der Sprache", sammeln Belege für Bedeutungen von Wörtern und verfassen auf dieser Basis große historische Wörterbücher. Aus dieser Zeit stammen das Oxford English Dictionary und das Grimmsche Wörterbuch.

(2) Ab der 2. Hälfte des 20. Jh. änderten sich die Voraussetzungen. Mit dem für die damalige Zeit bahnbrechenden Trésor de la langue francaise (Tlf) wurde erstmals ein maschinell abfragbares Korpus erstellt, welches als Basis für die Wörterbucharbeit verwendet wurde. Die Erstellung der lexikographischen Basis erfolgte vielfach datenbankbasiert.

(3) Ein kompletter Wandel der traditionellen Wörterbucharbeit wurde durch den "digital turn" ausgelöst. Dieser betraf (a) die Analyse der Wörterbuchartikel mit Hilfe von sehr großen digitalen Korpora anstelle der Belegarchive. Die 3. Auflage des OED konnte beispielsweise erst auf der Grundlage der großen digitalen Korpora konzipiert werden. (b) Mit diesem "digital turn" ging einher, dass Wörterbücher mittlerweile in klassischer Form kaum mehr publiziert werden, sondern lediglich als lexikalische Informationssysteme im Internet publiziert werden. 

(4) Mit der Veröffentlichung von GPT3 von Open-AI Ende 2022 wird ein weiteres Kapitel für die Lexikographie geöffnet. Seitdem wurden eine Vielzahl weiterer Modelle von Google, Meta, aber auch in Europa von Mistral-AI oder auch Aleph Alpha erzeugt. Mit diesen mächtigen Modellen ist es erstmals möglich, Teile von Wörterbuchartikeln, teilweise sogar gesamte Wörterbuchartikel automatisch durch diese Systeme generieren zu lassen. Ausführliche Evaluierungen stehen noch aus, aber die Veröffentlichungen für die aktuelle EURALEX-Konferenz 2024 zeigt, wie sehr sich das Thema KI mittlerweile in der Lexikographie Einzug gehalten hat: knapp 15% aller Einreichungen behandeln Themen mit Bezug zu GPTs bzw. LLMs.

Das *Kursprogramm* umfasst vier Termine, jeweils zwischen 10 und 16 Uhr.
Tag 1 und 3 finden in Potsdam statt, Tag 2 per Zoom (s. unten); Tag 4 entweder in Präsenz oder per Zoom (wird an Tag 3 entschieden)

## Tag 1 (12.9.2024): 
* 10-12.30 Einführung: Kurzer geschichtlicher Abriss der Lexikographie seit dem 19. Jh. sowie der e-Lexicography im 21. Jh.
* 13-14 Praktische E-Lexikographie: Die DWDS-Plattform - Wörterbuch, Korpus, Statistische Auswertungen)
* 14-16 (gemeinsam mit Anja Pfeiffer, BBAW/ZDL): "DWDS-Atelier - Workflow der Artikelerstellung im DWDS sowie gemeinsames Erstellen eines neuen DWDS-Wörterbuchartikels: *öffentlicher Bücherschrank* "


## Tag 2 (13.9.2024): per Zoom
* 10-11.15 Mikrostruktur: Definitionen im Wörterbuch: a) Oxford (s. Atkins/Rundell); b) DWDS
* 11.15-13.15 Axel Herold (BBAW/ZDL): Modellierung von lexikalischen Informationen (inkl. Einführung in *TEI* und *TEI Lex-0* sowie die DWDS-Wörterbuchstruktur mit praktischen Übungen: Voraussetzung hierfür ist ein bereits vorinstallierter XML-Editor)
* 14-15.30: (mit Gregor Middell - BBAW/ZDL) Technische Aspekte der lexikographische Arbeitsumgebung des DWDS / Vernetzungen von lexikalischen Informationen
* 15.30-16: Vergabe Referate

## Tag 3 (19.9.2024):
* 10-12.30 5 REFERATE
* 13.15-15.45 Andreas Nolda - BBAW/ZDL: "Daten zur diatopischen Variation im deutschen Wortschatz: Das ZDL-Regionalkorpus"

## Tag 4 (20.9.2024):
* 10-11 Von Kollokationen zu Wortprofilen
* 11-12 REFERATE  
* 13-14.30 REFERATE
* 14.30-15.30 Abschlussdiskussion zu Leichte Sprache und der benoteten Prüfungsleistungen

## Weiterführende Quellen:
* The Oxford Guide to Practical Lexicography. 2008. B.T. Sue Atkins and Michael Rundell. Oxford: Oxford University Press. Pp. 552. 
* Proceedings elex 2023: https://elex.link/elex2023/proceedings-download/

## Themen für Referate/Hausarbeiten:

**Vorbemerkung**: Die Referate sollten 20 Min dauern; danach 10 Min. Fragen/Diskussion

**[1]** Adam Kilgarriff, Miloš Husák, Katy McAdam, Michael Rundell and Pavel Rychlý (2008). GDEX: Automatically finding good dictionary examples in a corpus. In Proceedings of the 13th EURALEX International Congress. Spain, July 2008, pp. 425–432. (https://www.sketchengine.eu/wp-content/uploads/2015/05/GDEX_Automatically_finding_2008.pdf). Dazu auch die Konfigurations-Datei auf sketchengine.eu: https://www.sketchengine.eu/syntax-of-gdex-configuration-files/ bzw. Implementierung im DWDS-Kontext: https://github.com/ulf1/quaxa

**[2]** Miloš Jakubíček, Michael Rundell: The end of lexicography: Can ChatGPT outperform current tools for post-editing lexicography?  (Proc. elex 2023: p 518-533)

**[3]** Robert Lev, Sascha Wolfer. What lexical factors drive look-ups in Wiktionary (Proc. elex 2023)
 (https://journals.sagepub.com/doi/full/10.1177/21582440231219101 bzw. https://journals.sagepub.com/doi/epub/10.1177/21582440231219101)
....
weitere Referatsthemen folgen.

 **[10]** Literatur: Leichte Sprache. DIN SPEC (https://www.dinmedia.de/de/technische-regel-entwurf/din-spec-33429/364785446)

 ...

**[n]. Benotete Prüfungsleistung: Vorschlag: Entwickle mit Hilfe von Heuristiken (0-shot-prompting, few-shot-prompting, chain-of-thought) sowie einfachen RAG-Techniken auf der Basis der API von Open-AI einen Definitionsgenerierer, a) welcher möglichst in ihrer Qualität mit ausgewählten DWDS-Definitionen übereinstimmt, b) welcher ausgewählte Wörter in "Leichter Sprache" beschreibt. Ausführliche Beschreibung folgt. 





## Zoom-Raum
### Tag 2: 
https://us02web.zoom.us/j/89703237252?pwd=OWnrUmab9LOEFBmurK5Lmx3EN7MKZ1.1

### Tag 4: 
tba
