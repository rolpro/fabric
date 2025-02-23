INHALT:

# ÜBERBLICK

Funktionsweise: Fabric ist ein Open-Source-Framework, das die menschlichen Fähigkeiten mithilfe von KI erweitert und die Integration von KI in tägliche Aufgaben erleichtert.

Warum es genutzt wird: Anwender nutzen Fabric zur nahtlosen Anwendung von KI, um alltägliche Herausforderungen zu lösen, die Produktivität zu steigern und die menschliche Kreativität durch Technologie zu fördern.

# WIE MAN ES BENUTZT

Häufigste Syntax: Die häufigste Verwendung beinhaltet die Ausführung von Fabric-Befehlen im Terminal, wie z.B. `fabric --pattern <PATTERN_NAME>`.

# HÄUFIGE ANWENDUNGSFÄLLE

Zum Zusammenfassen von Inhalten: `fabric --pattern summarize`
Für die Analyse von Ansprüchen: `fabric --pattern analyze_claims`
Für die Extraktion von Weisheit aus Videos: `fabric --pattern extract_wisdom`
Für die Erstellung von benutzerdefinierten Mustern: `fabric --pattern create_pattern`
- Ein möglicher Ort, um sie zu speichern, ist ~/.config/custom-fabric-patterns.
- Wenn Sie sie dann verwenden wollen, kopieren Sie sie einfach nach ~/.config/fabric/patterns.
`cp -a ~/.config/custom-fabric-patterns/* ~/.config/fabric/patterns/`
- Jetzt können Sie sie mit ausführen: `pbpaste | fabric -p your_custom_pattern`


# WICHTIGSTE UND VERWENDETE OPTIONEN UND FUNKTIONEN

- **--Muster PATTERN, -p PATTERN**: Gibt das zu verwendende Muster (Prompt) an. Nützlich für die Anwendung spezifischer AI-Prompts auf Ihre Eingaben.
  
- **-stream, -s**: Streamt die Ergebnisse in Echtzeit. Ideal, um sofortiges Feedback von KI-Operationen zu erhalten.
  
- **--update, -u**: Aktualisiert Muster. Stellt sicher, dass Sie die neuesten KI-Eingabeaufforderungen für Ihre Aufgaben verwenden.
  
- **--model MODEL, -m MODEL**: Wählt das zu verwendende KI-Modell aus. Ermöglicht die Anpassung des KI-Backends für verschiedene Aufgaben.
  
- **--setup, -S**: Richtet Ihre Fabric-Instanz ein. Wichtig für Erstbenutzer, um Fabric korrekt zu konfigurieren.
  
- **-list, -l**: Listet die verfügbaren Muster auf. Hilft Benutzern, neue KI-Prompts für verschiedene Anwendungen zu entdecken.
  
- **-kontext, -C**: Verwendet eine Context-Datei, um Ihrem Muster einen Kontext hinzuzufügen. Erhöht die Relevanz von KI-Antworten durch zusätzliche Hintergrundinformationen.

# PATTERNS

## agility_story
Die Eingabeaufforderung fordert dazu auf, eine Benutzergeschichte und Akzeptanzkriterien für ein bestimmtes Thema zu schreiben, wobei der Schwerpunkt auf dem Agile Framework liegt. Der Schwerpunkt liegt auf dem Verständnis von Benutzergeschichten und der Erstellung von Akzeptanzkriterien. Die erwartete Ausgabe ist ein JSON-Format, das das Thema, die Benutzergeschichte und die Akzeptanzkriterien enthält.

## ai
Liefert aufschlussreiche Antworten durch ein tiefes Verständnis des Kerns von Fragen. Dazu gehört die Erstellung eines mentalen Modells der Frage vor der Beantwortung. Die Ausgabe besteht aus 3-5 prägnanten Markdown-Bullets mit jeweils 10 Wörtern.

## analyze_answers
Bewertet die Korrektheit der Antworten, die von den Lernenden auf Fragen gegeben werden, die von einem ergänzenden Muster für die Quizerstellung generiert wurden. Ziel ist es, das Verständnis der Lernziele zu bewerten und Bereiche zu identifizieren, die einer weiteren Untersuchung bedürfen, was Eingaben zum Thema und zu den Lernzielen erfordert. Die Ausgabe zeigt die Genauigkeit der Antworten der Lernenden in Bezug auf die vordefinierten Ziele an.

## analyze_claims
Analysiert und bewertet wahre Behauptungen in den Eingaben und liefert Beweise für und gegen sie, zusammen mit einer ausgewogenen Ansicht. Es trennt Wahrheitsansprüche von Argumenten, bewertet deren Gültigkeit und vergibt Bewertungen. Die Ausgabe enthält eine prägnante Zusammenfassung der Argumente und eine detaillierte Analyse jeder Behauptung.

## analyze_debate
Analysiert Debattenprotokolle, um Nutzern zu helfen, verschiedene Standpunkte zu verstehen und ihre Perspektiven zu erweitern. Es zeigt die Behauptungen auf, analysiert sie neutral und bewertet die Debatte nach Einsichtsfähigkeit und Emotionalität. Die Ausgabe umfasst Bewertungen, Emotionalität der Teilnehmer, Zusammenfassungen der Argumente mit Quellen, Übereinstimmungen, Meinungsverschiedenheiten, Missverständnissen, Erkenntnissen und Schlussfolgerungen.

## analyze_incident
Extrahiert und organisiert wichtige Informationen aus Artikeln über Cybersecurity-Verstöße und legt dabei den Schwerpunkt auf Effizienz und Klarheit. Der Schwerpunkt liegt auf der direkten Datenextraktion ohne Schlussfolgerungen, die Angriffsdetails, Angreifer- und Zielprofile, Besonderheiten des Vorfalls und Empfehlungen umfassen. Das Ergebnis ist eine strukturierte Zusammenfassung mit den wichtigsten Erkenntnissen über Cybersecurity-Vorfälle.

## analyze_logs
Analysiert eine Server-Protokolldatei, um Muster, Anomalien und potenzielle Probleme zu erkennen und so die Zuverlässigkeit und Leistung des Servers zu verbessern. Der Schwerpunkt liegt dabei auf einem datengesteuerten Ansatz, bei dem irrelevante Informationen und persönliche Meinungen ausgeschlossen werden. Zu den erwarteten Ergebnissen gehören Einblicke in die Betriebszuverlässigkeit, Leistungsbewertungen, die Identifizierung wiederkehrender Probleme und spezifische Verbesserungsvorschläge.

## analyze_malware
Die Eingabeaufforderung weist einen Experten für Malware-Analyse an, Malware methodisch zu zerlegen und sich dabei auf die Extraktion umfassender Details für die Analyse und Erkennung zu konzentrieren. Der Schwerpunkt liegt dabei auf einem strukturierten Ansatz zur Identifizierung von Malware-Merkmalen, Verhaltensweisen und potenziellen Indikatoren für eine Gefährdung. Die erwartete Ausgabe umfasst eine prägnante Zusammenfassung, einen detaillierten Malware-Überblick, Indikatoren für eine Gefährdung, Mitre Att&CK-Techniken, Erkennungsstrategien und Empfehlungen für die weitere Analyse.

## analyze_paper
Dieser Dienst analysiert Forschungsarbeiten, um ihre primären Ergebnisse zu ermitteln und ihre wissenschaftliche Qualität und Strenge zu bewerten. Es werden Behauptungen genauestens dargelegt, das Studiendesign, die Stichprobengröße und andere kritische Aspekte bewertet, um die Glaubwürdigkeit der Arbeit zu beurteilen. Die Ausgabe umfasst eine Zusammenfassung, Angaben zum Autor, Ergebnisse, eine Bewertung der Studienqualität und eine Endnote mit Begründung.

## analyze_patent
Die Aufforderung umreißt die Rolle und die Aufgaben eines Patentprüfers und beschreibt detailliert die Schritte zur Bewertung einer Patentanmeldung. Es wird Wert auf eine gründliche Analyse gelegt, die sich auf das Technologiefeld, das behandelte Problem, die Lösung, den Vorteil gegenüber dem Stand der Technik, die Neuheit und die erfinderische Tätigkeit konzentriert. Das erwartete Ergebnis umfasst ausführliche Abschnitte zu jedem Aspekt und zielt auf eine umfassende Bewertung ohne Platzbeschränkung ab.

## analyze_personality
Führt eine eingehende psychologische Analyse der Hauptperson in der angegebenen Eingabe durch und konzentriert sich dabei auf deren psychologisches Profil. Es beinhaltet eine detaillierte Betrachtung und einen Vergleich mit der menschlichen Psychologie, um daraus Erkenntnisse abzuleiten. Die Ausgabe enthält eine prägnante Zusammenfassung und unterstützende Aufzählungspunkte, die die wichtigsten psychologischen Eigenschaften hervorheben.

## analyze_presentation
Analysiert und kritisiert Präsentationen und konzentriert sich dabei auf den Inhalt, die Psychologie des Sprechers und die Diskrepanz zwischen erklärten und tatsächlichen Zielen. Es beinhaltet eine detaillierte Aufschlüsselung des Inhalts der Präsentation, der Selbstreferenzen des Sprechers und der Unterhaltungsversuche. Die Ausgabe umfasst Bewertungen und Zusammenfassungen für Ideen, Selbstlosigkeit, Unterhaltung und eine Gesamtanalyse mit ASCII-Powerbars, gefolgt von einer prägnanten Schlussfolgerung.

## analyze_prose
Bewertet die Qualität eines Textes, indem es seine Neuartigkeit, Klarheit und Prosa beurteilt und Empfehlungen zur Verbesserung gibt. Es verwendet einen detaillierten Ansatz, um jeden Aspekt zu bewerten und bietet präzise Ratschläge. Die erwartete Ausgabe umfasst Bewertungen und spezifische Vorschläge zur Verbesserung des Textes.

## analyze_prose_json
Bewertet die Qualität des Textes und des Inhalts, indem es Neuheit, Klarheit und Prosa beurteilt und dann Bewertungen und Empfehlungen zur Verbesserung abgibt. Dieser Prozess umfasst das Verstehen der Intention des Autors, die Bewertung von Ideen hinsichtlich ihrer Neuartigkeit, die Bewertung der Klarheit und der Qualität der Prosa sowie das Anbieten von präzisen Verbesserungsvorschlägen. Die erwartete Ausgabe ist ein JSON-Objekt, das diese Bewertungen und eine Gesamtbewertung auf der Grundlage der niedrigsten Einzelpunktzahl enthält.

## analyze_prose_pinker
Die Eingabeaufforderung skizziert einen umfassenden Prozess zur Bewertung von Prosa auf der Grundlage von Steven Pinkers "The Sense of Style", der sich auf die Identifizierung des Schreibstils, die Bewertung positiver und negativer Elemente und die Bereitstellung von Verbesserungsvorschlägen konzentriert. Es wird ein strukturierter Ansatz zur Kritik des Schreibens durch Stilanalyse, positive und negative Bewertungen, Beispiele für gute und schlechte Schreibpraktiken, Rechtschreib- und Grammatikkorrekturen und spezifische Verbesserungsvorschläge beschrieben, wobei die Prinzipien von Pinker angewendet werden. Das erwartete Ergebnis umfasst detaillierte Bewertungen, Beispiele und Punkte, die die Einhaltung oder Abweichung der Prosa von Pinkers Richtlinien widerspiegeln.

## analyze_spiritual_text
Analysiert spirituelle Texte, um überraschende Behauptungen hervorzuheben, und vergleicht sie mit der King James Bible. Der Schwerpunkt liegt auf der Identifizierung und dem Vergleich bestimmter Lehren und Behauptungen. Die Ausgabe enthält detaillierte Beispiele aus beiden Texten, um die Unterschiede zu verdeutlichen.

## analyze_tech_impact
Analysiert die gesellschaftlichen Auswirkungen von Technologieprojekten durch Aufschlüsselung ihrer Absichten, Ergebnisse und allgemeineren Auswirkungen, einschließlich ethischer Überlegungen. Es verwendet einen strukturierten Ansatz, um die Auswirkungen des Projekts auf die Gesellschaft und seine Nachhaltigkeit zu bewerten. Der Dienst erstellt eine umfassende Analyse, die eine Zusammenfassung, die verwendeten Technologien, die Zielgruppe, die Ergebnisse, die gesellschaftlichen Auswirkungen, ethische Überlegungen, die Nachhaltigkeit und eine Gesamtbewertung enthält.

## analyze_threat_report
Mit dieser Aufforderung wird ein superintelligenter Cybersecurity-Experte angewiesen, Berichte über Cybersecurity-Bedrohungen zu analysieren und die wichtigsten Erkenntnisse daraus zu extrahieren, wobei er sich auf neue, interessante und überraschende Informationen konzentriert. Der Schwerpunkt liegt auf der Erstellung von prägnanten, aufschlussreichen Zusammenfassungen und Listen von Trends, Statistiken, Zitaten, Referenzen und Empfehlungen ohne Verwendung von Fachjargon. Das erwartete Ergebnis umfasst geordnete Abschnitte mit extrahierten Informationen, die Klarheit und Tiefe im Verständnis von Cybersecurity-Bedrohungen anstreben.

## analyze_threat_report_trends
Analysiert Cybersecurity-Bedrohungsberichte, um bis zu 50 einzigartige, überraschende und aufschlussreiche Trends zu identifizieren. Dieser Prozess beinhaltet eine gründliche Untersuchung des Inhalts auf Expertenebene, um neue und interessante Erkenntnisse zu gewinnen. Die Ausgabe besteht aus einer Aufzählungsliste, in der diese Schlüsseltrends ohne Wiederholungen oder Formatierungsverzierungen hervorgehoben werden.

## answer_interview_question
Generiert maßgeschneiderte Antworten auf technische Interviewfragen, wobei ein lockerer und dennoch aufschlussreicher Ton angestrebt wird. Die KI greift auf eine technische Wissensbasis und berufliche Erfahrungen zurück, um Antworten zu erstellen, die Fachwissen demonstrieren und alternative Ansätze berücksichtigen. Die Ergebnisse sind so strukturiert, dass sie mündlich vorgetragen werden können, einschließlich Kontext, Haupterklärung, alternativer Ansatz und evidenzbasierter Schlussfolgerung.

## ask_secure_by_design_questions
Generiert einen umfassenden Satz sicherheitsorientierter Fragen, um sicherzustellen, dass der Entwurf eines Projekts inhärent sicher ist. Dieser Prozess beinhaltet eine gründliche Analyse und Konzeptualisierung der Projektkomponenten und ihrer Sicherheitsanforderungen. Die Ausgabe umfasst eine Zusammenfassung und eine nach Themen geordnete Liste von Sicherheitsfragen.

## capture_thinkers_work
Fasst die Lehren und Philosophien bedeutender Persönlichkeiten oder philosophischer Schulen zusammen und bietet detaillierte Vorlagen für jede. Dazu gehören Abkürzungen, Hintergrund, Schulen, einflussreiche Ideen, primäre Lehren, Werke, Zitate, Anwendungen und Lebensratschläge. Die Ausgabe bietet einen umfassenden Überblick über die Beiträge und Ideologien des Betreffenden.

## check_agreement
Analysiert Verträge und Vereinbarungen, um mögliche Probleme zu erkennen und die wichtigsten Punkte zusammenzufassen. Bei dieser Aufgabe geht es darum, kritische, wichtige und weniger wichtige Punkte herauszufiltern und zu organisieren, damit sie verhandelt oder überdacht werden können. Das erwartete Ergebnis umfasst eine prägnante Zusammenfassung des Dokuments, eine detaillierte Auflistung der wichtigsten Bestimmungen und strukturierte Empfehlungen für Änderungen.

## clean_text
Fasst Formatierungsprobleme im Text zusammen und korrigiert sie, wobei der Schwerpunkt auf der Beseitigung von ungeraden Zeilenumbrüchen und der Verbesserung der Zeichensetzung liegt, ohne den Inhalt zu verändern. Bei dieser Eingabeaufforderung liegt der Schwerpunkt auf der Beibehaltung der ursprünglichen Botschaft und der Verbesserung der Lesbarkeit. Die erwartete Ausgabe ist eine bereinigte, gut formatierte Version des Eingabetextes.

## coding_master
Dieser Prompt weist einen erfahrenen Programmierer an, einem Anfänger ein bestimmtes Programmierkonzept oder eine Programmiersprache anhand von Beispielen aus seriösen Quellen zu erklären. Der Schwerpunkt liegt dabei auf der verständlichen Vermittlung und der Formatierung von Codebeispielen in Markdown. Die erwartete Ausgabe umfasst strukturierte Markdown-Inhalte mit spezifischen Abschnitten für Ideen, Empfehlungen, Gewohnheiten, Fakten und Erkenntnisse, jeweils mit einer genauen Wortzahl und Anzahl.

## Vergleichen_und_Kontrastieren
Vergleicht und kontrastiert eine Liste von Elementen und konzentriert sich dabei auf deren Unterschiede und Ähnlichkeiten. Der Ansatz besteht darin, den Vergleich in einem Markdown-Tabellenformat zu organisieren, mit Elementen auf der linken Seite und Themen am oberen Rand. Die erwartete Ausgabe ist eine strukturierte Tabelle, die die wichtigsten Vergleiche hervorhebt.

## create_5_sentence_summary
Erzeugt prägnante Zusammenfassungen oder Antworten in fünf verschiedenen Tiefen. Es erfordert ein tiefes Verständnis und eine durchdachte Analyse der Eingabe, bevor eine mehrschichtige Zusammenfassung erstellt wird. Die Ausgabe ist eine strukturierte Liste von Zusammenfassungen, jede mit abnehmender Wortzahl, die das Wesentliche des Inputs erfasst.

## create_academic_paper
Die Eingabeaufforderung weist Sie an, hochwertige, aussagekräftige wissenschaftliche Arbeiten in LaTeX zu erstellen, wobei der Schwerpunkt auf klaren Konzepterklärungen liegt. Der Schwerpunkt liegt auf der Erstellung logisch strukturierter, visuell ansprechender Dokumente in einem zweispaltigen Layout. Die erwartete Ausgabe ist LaTeX-Code, der auf akademische Publikationen zugeschnitten ist.

## create_ai_jobs_analysis
Analysiert Stellenberichte, um Rollen zu identifizieren, die durch Automatisierung gefährdet sind, und bietet Strategien zur Verbesserung der Arbeitsplatzsicherheit. Es nutzt historische Erkenntnisse, um zukünftige Trends vorherzusagen. Die Ausgabe umfasst kategorisierte Job-Schwachstellen und personalisierte Resilienz-Empfehlungen.

## create_aphorisms
Erzeugt eine Liste von 20 Aphorismen, die sich auf das/die angegebene(n) Thema(s) beziehen, wobei jeder Aphorismus seinem ursprünglichen Autor zugeordnet ist. Es wird vermieden, alle Einträge mit den eingegebenen Schlüsselwörtern zu beginnen, um Vielfalt zu gewährleisten. Die Ausgabe ist eine kuratierte Sammlung weiser Sprüche von verschiedenen Personen.

## create_art_prompt
Der Prompt leitet einen erfahrenen Künstler und KI-Flüsterer an, ein Konzept zu entwerfen und die KI anzuweisen, Kunst zu schaffen, die ein bestimmtes Konzept perfekt umsetzt. Der Schwerpunkt liegt dabei auf dem Konzept und seiner visuellen Darstellung, wobei ein überzeugendes und interessantes Kunstwerk angestrebt wird. Das erwartete Ergebnis ist eine detaillierte Beschreibung des Konzepts, eine visuelle Darstellung und direkte Anweisungen für die KI, einschließlich stilistischer Hinweise für das Kunstwerk.

## create_better_frame
Der Aufsatz erörtert das Konzept der Rahmung als eine Möglichkeit, die Realität durch bestimmte Linsen zu konstruieren und zu interpretieren, und betont die Macht positiver Rahmung, um die eigenen Erfahrungen und Ergebnisse im Leben zu gestalten. Es wird hervorgehoben, wie wichtig es ist, positive und produktive Frames zu wählen, da diese die Wahrnehmung der Realität und folglich auch die Handlungen und Ergebnisse des Einzelnen erheblich beeinflussen können. Das erwartete Ergebnis ist ein Verständnis dafür, wie unterschiedliche Frames zu sehr unterschiedlichen Interpretationen ein und derselben Realität führen können, und die Ermutigung, positivere Frames zu wählen, um das eigene Leben und die gesellschaftliche Dynamik zu verbessern.

## create_coding_project
Erzeugt Wireframes und Startcode für Coding-Projekte auf der Grundlage von Benutzerideen. Dieses Tool nimmt eine Coding-Idee als Eingabe und gibt einen detaillierten Projektplan aus, einschließlich Wireframes, Codestruktur und Einrichtungsanweisungen. Die erwartete Ausgabe umfasst Projektzusammenfassungen, Entwicklungsschritte, Dateistruktur und Code für die Initialisierung des Projekts.

## create_command
Generiert spezifische Befehlszeilen für verschiedene Penetrationstest-Tools auf der Grundlage einer kurzen Beschreibung des gewünschten Ergebnisses. Dieser Ansatz nutzt die Hilfedokumentation des Tools, um die Genauigkeit und Relevanz der generierten Befehle sicherzustellen. Die erwartete Ausgabe ist eine präzise Befehlszeile, die ausgeführt werden kann, um das vom Benutzer angegebene Ziel mit dem Werkzeug zu erreichen.

## create_cyber_summary
Die Eingabeaufforderung weist den Benutzer an, eine umfassende Zusammenfassung von Cybersecurity-Bedrohungen, -Schwachstellen, -Vorfällen und -Malware zu erstellen, wobei der Schwerpunkt auf einem detaillierten und iterativen Analyseprozess liegt. Es wird ein einzigartiger, geistig visueller Ansatz zum Organisieren und Verstehen komplexer Informationen beschrieben. Das erwartete Ergebnis umfasst eine prägnante Zusammenfassung und kategorisierte Listen von Cybersicherheitsproblemen.

## create_git_diff_commit
Enthält Anweisungen für die Verwendung bestimmter Git-Befehle zur Verwaltung von Codeänderungen. Es wird erklärt, wie Unterschiede seit dem letzten Commit angezeigt werden und wie man die letzten Commit-Details anzeigt. Die erwartete Ausgabe enthält Beispiele für die Verwendung der Befehle.

## create_graph_from_input
Erstellt Diagramme über den zeitlichen Verlauf eines Sicherheitsprogramms, wobei der Schwerpunkt auf Verbesserungsmetriken liegt. Dazu werden Daten analysiert, um Trends zu erkennen und eine CSV-Datei mit bestimmten Feldern auszugeben. Die erwartete Ausgabe ist eine CSV-Datei, die den Fortschritt des Programms im Laufe der Zeit aufzeigt.

## create_hormozi_offer
Die KI wurde entwickelt, um Geschäftsangebote zu erstellen, die auf Alex Hormozi's "$100M Offers"-Strategien basieren und darauf abzielen, unwiderstehliche Angebote zu erstellen. Sie integriert die Prinzipien von Hormozi und konzentriert sich auf Wert, Preisgestaltung, Garantien und Marktausrichtung. Das erwartete Ergebnis umfasst eine detaillierte Analyse potenzieller Geschäftsangebote, in der ihre einzigartigen Wertvorstellungen hervorgehoben werden.

## create_idea_compass
Die Eingabeaufforderung leitet die Benutzer beim Organisieren und Analysieren einer Idee oder Frage mithilfe einer strukturierten Vorlage an. Der Schwerpunkt liegt auf der detaillierten Untersuchung, einschließlich Definitionen, Beweisen, Quellen und der Untersuchung von Ähnlichkeiten, Gegensätzen, Themen und Konsequenzen. Das erwartete Ergebnis ist eine umfassende Zusammenfassung mit geordneten Abschnitten und Markierungen.

## create_investigation_visualization
Erstellt detaillierte GraphViz-Visualisierungen zur Veranschaulichung komplexer nachrichtendienstlicher Untersuchungen und Daten. Dieser Ansatz beinhaltet eine umfassende Analyse und Organisation von Informationen, um klare, kommentierte Diagramme zu erstellen. Die Ausgabe umfasst eine visuelle Darstellung und analytische Schlussfolgerungen mit einer Gewissheitsbewertung.

## create_keynote
Die Eingabeaufforderung hilft bei der Erstellung von Keynote-Präsentationen in TED-Qualität auf der Grundlage des bereitgestellten Inputs, wobei der Schwerpunkt auf dem Erzählfluss und den praktischen Schlussfolgerungen liegt. Es werden Schritte zur Strukturierung der Präsentation in Folien mit prägnanten Aufzählungspunkten, Bildern und Sprechernotizen beschrieben. Die erwartete Ausgabe umfasst einen Erzählfluss, die endgültigen Erkenntnisse und ein detailliertes Foliendokument.

## create_logo
Generiert einfache und elegante Firmenlogos auf der Grundlage der Eingaben, wobei der Schwerpunkt auf minimalistischen Designs ohne Text liegt. Der Schwerpunkt liegt auf der Erstellung von Vektorgrafik-Logos, die das Wesentliche der Eingabe einfangen. Die erwartete Ausgabe ist eine Eingabeaufforderung für einen AI-Bildgenerator zur Erstellung eines minimalistischen Logos.

## create_markmap_visualization
Verwandelt komplexe Ideen in visuelle Diagramme unter Verwendung der MarkMap-Syntax. Dieser Prozess beinhaltet die Vereinfachung von Konzepten, um sicherzustellen, dass sie effektiv in einem visuellen Format dargestellt werden können. Die Ausgabe ist ein MarkMap-Syntax-Diagramm, das die Kernideen visuell vermittelt.

## create_mermaid_visualization
Diese Eingabeaufforderung leitet dazu an, Visualisierungen für komplexe Ideen mit der Mermaid-Syntax in Markdown zu erstellen. Der Schwerpunkt liegt auf der Erstellung eigenständiger Diagramme, die Konzepte durch komplexe Designs vollständig vermitteln. Die erwartete Ausgabe ist ein Mermaid-Syntaxdiagramm mit einer visuellen Erklärung.

## create_micro_summary
Die Eingabeaufforderung leitet dazu an, Inhalte in einem strukturierten Markdown-Format zusammenzufassen. Der Schwerpunkt liegt auf Prägnanz und Klarheit und konzentriert sich auf eine Zusammenfassung in einem Satz, die wichtigsten Punkte und die wichtigsten Erkenntnisse. Die erwartete Ausgabe ist eine gut organisierte Liste mit Aufzählungspunkten, die das Wesentliche des Inhalts hervorhebt.

## create_network_threat_landscape
Analysiert offene Ports und Dienste aus Netzwerk-Scans, um Sicherheitsrisiken zu identifizieren und Empfehlungen zu geben. Dieser Prozess umfasst eine detaillierte Untersuchung von Port- und Dienststatistiken, um potenzielle Schwachstellen aufzudecken. Die Ausgabe umfasst einen Bedrohungsbericht mit Beschreibungen offener Ports, Risikobewertungen, Empfehlungen zur Schadensbegrenzung, eine kurze Zusammenfassung sowie Einblicke in Trends und bemerkenswerte Zitate aus der Analyse.

## create_npc
Erzeugt detaillierte NSCs für D&D 5. Edition, wobei kreative Eingaben berücksichtigt werden, um ein reichhaltiges Charakterprofil zu gewährleisten. Dieser Prozess beinhaltet einen umfassenden Satz von Attributen, von Hintergrund und Schwächen bis hin zu Zielen und Besonderheiten, mit dem Ziel, einen vollständig ausgearbeiteten Charakterbogen zu erstellen. Das erwartete Ergebnis ist ein klares, detailliertes NSC-Profil, das sich für den sofortigen Einsatz im Spiel eignet.

## create_pattern
Interpretiert und beantwortet LLM/AI-Eingaben auf der Grundlage von spezifischen Anweisungen und Beispielen. Dieser KI-Assistent zeichnet sich durch das Organisieren und Analysieren von Aufforderungen aus, um genau strukturierte Antworten zu produzieren. Es wird erwartet, dass die Ausgabe perfekt mit den vorgegebenen Formatierungs- und Inhaltsanforderungen übereinstimmt.

## create_quiz
Generiert Fragen für Lernende, um Schlüsselkonzepte auf der Grundlage der vorgegebenen Lernziele zu überprüfen. Es benötigt das Thema und die Lernziele als Eingabe für eine genaue Fragengenerierung. Die Ausgabe besteht aus Fragen, die den Lernenden helfen sollen, die wichtigsten Konzepte zu verstehen.

## create_reading_plan
Erstellt einen maßgeschneiderten Drei-Phasen-Leseplan auf der Grundlage von Benutzereingaben, der sich auf einen Autor oder eine bestimmte Anfrage konzentriert. Es wählt sorgfältig Bücher aus, die sowohl populär als auch versteckt sind, um das Wissen des Benutzers über das Thema zu erweitern. Die Ausgabe umfasst eine kurze Einführung, einen strukturierten Leseplan über drei Phasen und eine Zusammenfassung.

## create_report_finding
Die Eingabeaufforderung weist die Erstellung eines detaillierten Markdown-Sicherheitsbefunds für einen Cybersicherheitsbewertungsbericht an, der Abschnitte wie Beschreibung, Risiko, Empfehlungen, Referenzen, Ein-Satz-Zusammenfassung, Trends und Zitate auf der Grundlage eines vorgegebenen Schwachstellentitels und einer Erklärung umfasst. Der Schwerpunkt liegt dabei auf einem strukturierten, aufschlussreichen Ansatz, ohne sich auf Aufzählungspunkte für bestimmte Abschnitte zu verlassen, und erfordert die Extraktion von Schlüsselempfehlungen, Trends und Zitaten. Das erwartete Ergebnis ist ein umfassendes, informatives Dokument, das auf die Aufnahme in einen Sicherheitsbewertungsbericht zugeschnitten ist.

## create_security_update
Diese Eingabeaufforderung weist Sie an, prägnante Sicherheitsupdates für Newsletter zu erstellen, die sich auf Entwicklungen im Bereich der Cybersicherheit, Bedrohungen, Hinweise und neue Schwachstellen konzentrieren. Der Schwerpunkt liegt auf der Gliederung des Inhalts in bestimmte Abschnitte mit kurzen Beschreibungen und Links zu weiteren Informationen. Die erwartete Ausgabe umfasst eine strukturierte Zusammenfassung von Cybersicherheitsthemen mit Links zu detaillierten Quellen.

## create_show_intro
Diese Aufforderung hilft bei der Erstellung überzeugender kurzer Intros für Podcasts, wobei der Schwerpunkt auf der Hervorhebung der interessantesten behandelten Themen liegt. Der Schwerpunkt liegt auf der Auswahl neuer und überraschender Elemente aus der Sendung für das Intro. Das erwartete Ergebnis ist eine prägnante, ansprechende Einleitung, die bis zu zehn wichtige Diskussionsthemen erwähnt.

## create_sigma_rules
Extrahiert Tactics, Techniques, and Procedures (TTPs) aus Sicherheitsnachrichten, um YAML-basierte Sigma-Regeln für die hostbasierte Erkennung zu erstellen. Diese Regeln konzentrieren sich auf die Erkennung von Cybersecurity-Bedrohungen mit Tools wie Sysinternals: Sysmon, PowerShell und Windows-Protokolle. Die Ausgabe umfasst gut dokumentierte Sigma-Regeln im YAML-Format, die jeweils durch Kopf- und Fußzeilen getrennt sind.

## create_stride_threat_model
Die Eingabeaufforderung leitet zur Erstellung eines detaillierten Bedrohungsmodells unter Verwendung der STRIDE-Methodik pro Element für ein bestimmtes Systementwurfsdokument an. Der Schwerpunkt liegt dabei auf dem Verständnis der Systemressourcen, der Vertrauensgrenzen und des Datenflusses, um potenzielle Bedrohungen zu identifizieren und zu priorisieren. Die erwartete Ausgabe ist eine umfassende Tabelle, in der die Bedrohungen kategorisiert, ihre Abhilfestrategien beschrieben und ihre Risikostärke bewertet werden.

## create_summary
Die Eingabeaufforderung leitet dazu an, Inhalte in einem strukturierten Markdown-Format zusammenzufassen. Der Schwerpunkt liegt auf der Erstellung prägnanter, informativer Zusammenfassungen mit spezifischen Abschnitten für eine Ein-Satz-Zusammenfassung, die wichtigsten Punkte und die wichtigsten Erkenntnisse. Das erwartete Ergebnis ist eine übersichtliche Zusammenfassung mit klaren, eindeutigen Abschnitten.

## create_tags
Die Aufforderung besteht darin, Tags aus dem Textinhalt zu identifizieren und auszugeben, die in Mindmapping-Tools verwendet werden können, wobei der Schwerpunkt auf der Extraktion von mindestens fünf Themen oder Ideen liegt. Es wird darauf geachtet, dass alle Autoren oder vorhandenen Tags einbezogen werden, Leerzeichen in Tags in Unterstriche umgewandelt werden und alle Tags in Kleinbuchstaben ohne Wiederholungen geschrieben werden. Die erwartete Ausgabe ist eine einzelne Zeile mit durch Leerzeichen getrennten, klein geschriebenen Tags, die für den Inhalt des Textes relevant sind.

## create_threat_model
Die Eingabeaufforderung leitet dazu an, narrativ basierte Bedrohungsmodelle für verschiedene Szenarien zu erstellen, wobei der Schwerpunkt auf einer realistischen Risikobewertung gegenüber unwahrscheinlichen Gefahren liegt. Es wird betont, wie wichtig es ist, zwischen möglichen und wahrscheinlichen Bedrohungen zu unterscheiden und die Verteidigungsbemühungen auf letztere zu konzentrieren. Die erwartete Ausgabe umfasst ein strukturiertes Bedrohungsmodell und einen Analyseabschnitt, der logische Verteidigungsentscheidungen gegen identifizierte Szenarien anleitet.

## create_threat_scenarios
Die Aufforderung zielt darauf ab, einfache Bedrohungsmodelle für verschiedene Sicherheitsbelange zu erstellen, die von der physischen bis zur Cybersicherheit reichen. Der Schwerpunkt liegt dabei auf einem realistischen Ansatz zur Identifizierung und Priorisierung potenzieller Bedrohungen auf der Grundlage von Wahrscheinlichkeit und Auswirkungen. Das erwartete Ergebnis umfasst eine detaillierte Analyse von Bedrohungsszenarien, eine logische Erklärung des Bedrohungsmodellierungsprozesses, empfohlene Kontrollen und eine narrative Analyse, die der Risikobewertung Realismus verleiht.

## create_upgrade_pack
Die Aufforderung leitet dazu an, Weltmodelle und Aufgabenalgorithmen aus vorgegebenen Inhalten zu extrahieren und zu aktualisieren. Der Schwerpunkt liegt dabei auf tiefem Denken, um Überzeugungen über die Welt und die Art und Weise, wie Aufgaben ausgeführt werden sollten, zu ermitteln. Die erwartete Ausgabe umfasst prägnante Aufzählungspunkte, die diese Überzeugungen und Aufgabenstrategien zusammenfassen und in relevante Kategorien einordnen.

## create_video_chapters
Extrahiert die interessantesten Themen aus einem Transkript und versieht sie mit einem Zeitstempel, um das Betrachten des Videos zu simulieren. Der Schwerpunkt liegt auf der Identifizierung von Schlüsselthemen und -momenten, die dann mit präzisen Zeitstempeln versehen werden. Die Ausgabe ist eine Liste von Themen mit aufeinanderfolgenden Zeitstempeln innerhalb der Videolänge.

## create_visualization
Wandelt komplexe Ideen in vereinfachte ASCII-Kunstvisualisierungen um. Dieser Ansatz ermöglicht es, komplexe Konzepte durch detaillierte ASCII-Diagramme visuell zu verstehen. Die Ausgabe ist ein eigenständiges ASCII-Kunstwerk, das von einer prägnanten visuellen Erklärung begleitet wird.

## explain_code
Die Eingabeaufforderung weist einen erfahrenen Programmierer an, Code, Ausgaben von Sicherheitstools oder Konfigurationstexte zu analysieren und zu erklären. Sie betont einen flexiblen Ansatz, um die beste Erklärung zu finden. Die erwartete Ausgabe sind kategorisierte Erklärungen oder Antworten auf spezifische Fragen, die auf die Art der Eingabe zugeschnitten sind.

## explain_docs
Verbessert Anleitungen zur Verwendung von Werkzeugen oder Produkten durch ein strukturiertes Format. Dieser Ansatz gliedert die Erklärung in die Funktionen des Tools, die Gründe für seine Nützlichkeit, die Verwendung des Tools, allgemeine Anwendungsfälle und die wichtigsten Funktionen. Das erwartete Ergebnis sind vereinfachte, besser organisierte Anleitungen.

## explain_project
Die Eingabeaufforderung leitet dazu an, die Projektdokumentation in einem strukturierten, benutzerfreundlichen Format zusammenzufassen. Der Schwerpunkt liegt darauf, das Projekt zu verstehen und dieses Verständnis dann in prägnante Zusammenfassungen und praktische Schritte für die Installation und Verwendung zu destillieren. Die Ausgabe enthält einen Projektüberblick, das behandelte Problem, den Lösungsansatz und klare Anweisungen für die Installation und Verwendung, um das Projekt für Benutzer und Entwickler zugänglich zu machen.

## explain_terms
Die Eingabeaufforderung zielt darauf ab, Glossare für komplexe Begriffe innerhalb eines bestimmten Inhalts zu erstellen und so das Verständnis zu verbessern. Sie konzentriert sich darauf, fortgeschrittene Begriffe zu identifizieren und zu erklären, mit Ausnahme von Grundbegriffen, um das Verständnis des Inhalts zu erleichtern. Die erwartete Ausgabe ist eine Liste von fortgeschrittenen Begriffen mit Definitionen, Analogien und ihrer Bedeutung, formatiert in Markdown.

## export_data_as_csv
Die Eingabeaufforderung weist die KI an, Datenstrukturen aus der Eingabe zu identifizieren und in eine CSV-Datei zu formatieren. Der Schwerpunkt liegt auf dem Verständnis des Kontexts und der korrekten Benennung der Felder auf der Grundlage der Eingabe. Die erwartete Ausgabe ist eine CSV-Datei, die alle identifizierten Datenstrukturen enthält.

## extract_algorithm_update_recommendations
Analysiert Eingaben, um prägnante, umsetzbare Empfehlungen zur Verbesserung von Prozessen innerhalb von Inhalten zu geben. Der Schwerpunkt liegt dabei auf der Extraktion praktischer Schritte zur Verbesserung von Algorithmen oder Methoden. Die Ausgabe besteht aus einer Aufzählungsliste mit bis zu drei kurzen Vorschlägen.

## extract_article_wisdom
Extrahiert wichtige Erkenntnisse und Weisheiten aus Textinhalten, um das Problem der Informationsflut und die Herausforderung, wertvolle Informationen zu behalten, zu lösen. Es identifiziert und organisiert auf einzigartige Weise Ideen, Zitate, Referenzen, Gewohnheiten und Empfehlungen aus einer Vielzahl von Texten. Die erwartete Ausgabe umfasst zusammengefasste Ideen, bemerkenswerte Zitate, relevante Verweise und umsetzbare Gewohnheiten.

## extract_book_ideas
Fasst die wichtigsten Inhalte eines Buches zusammen, indem 50 bis 100 der aufschlussreichsten, überraschendsten und interessantesten Ideen extrahiert werden. Dabei werden die Details des Buches in Erinnerung gerufen und die Ideen nach ihrer Bedeutung geordnet. Die Ausgabe wird als Aufzählungsliste formatiert und ist auf 20 Wörter pro Idee begrenzt.

## extract_book_recommendations
Fasst die wichtigsten Inhalte eines Buches zusammen, indem 50 bis 100 der praktischsten Empfehlungen extrahiert werden. Der Ansatz konzentriert sich auf umsetzbare Ratschläge und priorisiert die wirkungsvollsten Vorschläge zuerst. Die Ausgabe ist eine in Markdown formatierte Liste mit lehrreichen Empfehlungen, die jeweils auf 20 Wörter begrenzt sind.

## extract_business_ideas
Extrahiert und vertieft die besten Geschäftsideen aus den bereitgestellten Inhalten und konzentriert sich dabei auf diejenigen, die das Potenzial haben, Branchen zu revolutionieren. Dieser Assistent identifiziert zunächst alle bemerkenswerten Geschäftskonzepte und wählt dann die zehn vielversprechendsten aus, wobei er auf Einzigartigkeit und Differenzierung achtet. Die Ausgabe umfasst eine Liste der extrahierten Ideen und eine detaillierte Ausarbeitung der zehn besten Ideen.

## extrahieren_kontroverse_Ideen
Identifiziert und listet kontroverse Aussagen aus Eingaben auf. Dieses KI-System konzentriert sich auf die Extraktion kontroverser Ideen und Zitate und stellt sie in einem strukturierten Markdown-Format dar. Die erwartete Ausgabe umfasst Abschnitte für kontroverse Ideen und unterstützende Zitate, jeweils mit spezifischen Inhaltsrichtlinien.

## extract_extraordinary_claims
Die Aufforderung besteht darin, außergewöhnliche Behauptungen aus Gesprächen zu identifizieren und aufzulisten, wobei der Schwerpunkt auf solchen liegt, die von der wissenschaftlichen Gemeinschaft abgelehnt werden oder auf Fehlinformationen beruhen. Der Schwerpunkt liegt dabei auf Aussagen, die anerkannten wissenschaftlichen Wahrheiten widersprechen, wie z. B. die Evolution oder die Mondlandung. Das erwartete Ergebnis ist eine detaillierte Liste von mindestens 50 bis maximal 100 spezifischen Zitaten, die diese Behauptungen belegen.

## extract_ideas
Bei dieser Aufgabe werden aufschlussreiche und interessante Informationen aus einem Text extrahiert, wobei der Schwerpunkt auf dem Sinn des Lebens und dem menschlichen Fortschritt liegt. Der Schwerpunkt liegt auf der Erstellung prägnanter Aufzählungspunkte, die die wichtigsten Ideen zusammenfassen. Erwartet wird eine Liste mit aufschlussreichen Ideen, die jeweils genau 15 Wörter lang sind.

## extract_insights
Die Aufforderung besteht darin, aussagekräftige Erkenntnisse aus einem Text zu extrahieren und zusammenzufassen, wobei der Schwerpunkt auf dem Sinn des Lebens und der Interaktion zwischen Mensch und Technik liegt. Der Schwerpunkt liegt auf der Erstellung prägnanter, aufschlussreicher Aufzählungspunkte aus dem Inhalt. Die erwartete Ausgabe ist eine Liste von abstrahierten, klugen Einsichten, jede genau 15 Wörter lang.

## extract_main_idea
Die Aufforderung fordert dazu auf, den wichtigsten Gedanken aus einem gegebenen Inhalt zu extrahieren und zu präsentieren. Der Schwerpunkt liegt auf einem strukturierten Ansatz zur Ermittlung und Empfehlung von Maßnahmen auf der Grundlage der extrahierten Idee. Die erwartete Ausgabe umfasst einen prägnanten Hauptgedanken und eine Empfehlung, jeweils in einem Satz mit 15 Wörtern.

## extract_patterns
Die Aufforderung besteht darin, Muster aus einer Sammlung von Ideen, Daten oder Beobachtungen zu identifizieren und zu analysieren, wobei der Schwerpunkt auf den überraschendsten oder am häufigsten genannten Mustern liegt. Es wird ein strukturierter Ansatz zum Extrahieren, Gewichten und Dokumentieren dieser Muster skizziert, einschließlich einer detaillierten Analyse und Ratschlägen für Erbauer in der Startup-Branche. Das erwartete Ergebnis umfasst Abschnitte für Muster, eine Meta-Analyse, eine zusammenfassende Analyse, die fünf wichtigsten Muster und Ratschläge für Gründer, die alle als Aufzählungspunkte mit bestimmten Wortgrenzen formatiert sind.

## extract_poc
Analysiert Sicherheits- oder Bug Bounty-Berichte, um URLs zu extrahieren und als Proof-of-Concept für die Überprüfung von Schwachstellen bereitzustellen. Es identifiziert eindeutig URLs, die das Vorhandensein von Schwachstellen direkt überprüfen können, zusammen mit dem notwendigen Befehl, um sie auszuführen. Die Ausgabe enthält einen Befehl, gefolgt von der URL oder Datei zur Überprüfung der Schwachstelle.

## extract_predictions
Die Eingabeaufforderung gibt Anweisungen zum Extrahieren und Organisieren von Vorhersagen aus gegebenen Inhalten. Sie beschreibt einen Prozess zur Identifizierung spezifischer Vorhersagen, ihrer erwarteten Erfüllungsdaten, Konfidenzniveaus und Überprüfungsmethoden. Die erwartete Ausgabe umfasst eine Aufzählung von Vorhersagen und eine strukturierte Tabelle, die diese Details zusammenfasst.

## extract_questions
Extrahiert Fragen aus dem Inhalt und analysiert ihre Effektivität, wenn es darum geht, überraschende, hochwertige Antworten zu erhalten. Der Schwerpunkt liegt dabei auf der Identifizierung der Elemente, die diese Fragen herausragend machen. Die Ausgabe umfasst aufgelistete Fragen, eine Analyse ihrer Brillanz und Empfehlungen für Interviewer.

## extract_recommendations
Extrahiert und kondensiert praktische Empfehlungen aus dem Inhalt in eine prägnante Liste. Dieser Prozess umfasst die Identifizierung expliziter und impliziter Ratschläge innerhalb des Materials. Die Ausgabe besteht aus einer Aufzählung von bis zu 20 kurzen Empfehlungen.

## extract_references
Extrahiert Verweise auf verschiedene Formen von Kunst und Literatur aus dem Inhalt und stellt sie in einer übersichtlichen Liste zusammen. Bei diesem Prozess werden bis zu 20 Referenzen identifiziert und aufgelistet, wobei sichergestellt wird, dass jede einzelne in nicht mehr als 15 Wörtern kurz beschrieben wird. Das Ergebnis ist eine Aufzählung von Verweisen auf Kunst, Geschichten, Bücher, Literatur, Aufsätze und andere Lernquellen.

## extract_song_meaning
Analysiert und interpretiert die Bedeutung von Liedern auf der Grundlage von Liedtexten, Künstlerkontext und anderen relevanten Informationen. Dieser Prozess umfasst umfangreiche Recherchen und eine gründliche Analyse der Liedtexte. Das Ergebnis umfasst einen zusammenfassenden Satz, detaillierte Aufzählungspunkte zur Bedeutung des Songs und Belege für die Interpretation.

## extract_sponsors
Identifiziert und kategorisiert Sponsoren und potenzielle Sponsoren aus Transkripten. Es unterscheidet zwischen tatsächlichen Sponsoren und bloßen Erwähnungen und zielt auf eine genaue Identifizierung der Sponsoren ab. Die Ausgabe listet offizielle und potenzielle Sponsoren mit Beschreibungen und Links auf.

## extract_videoid
Extrahiert Video-IDs aus URLs zur Verwendung in anderen Anwendungen. Es analysiert die URL sorgfältig, um den spezifischen Teil zu finden, der die Video-ID enthält. Die Ausgabe ist lediglich die Video-ID ohne zusätzliche Informationen oder Formatierungen.

## extract_wisdom
Extrahiert Schlüsselerkenntnisse aus Textinhalten, um das Problem der Informationsüberlastung und des Gedächtnisses zu lösen. Es identifiziert eindeutig Ideen, Zitate, Referenzen, Gewohnheiten und Empfehlungen aus einer Vielzahl von Texten. Die Ausgabe umfasst zusammengefasste Inhalte, die wertvolle Erkenntnisse und umsetzbare Elemente hervorheben.

## extract_wisdom_agents
Die Aufforderung umreißt einen komplexen Prozess zur Gewinnung von Erkenntnissen aus Textinhalten, der sich auf Themen wie den Sinn des Lebens und die Auswirkungen der Technologie auf die Menschheit konzentriert. Es wird beschrieben, wie Teams von KI-Agenten mit unterschiedlichen Fachkenntnissen gebildet werden, um Inhalte zusammenzufassen, Schlüsselideen, Erkenntnisse, Zitate, Gewohnheiten, Fakten, Referenzen und Empfehlungen zu identifizieren und in einem Satz zusammenzufassen. Der erwartete Output umfasst Zusammenfassungen und Listen von Erkenntnissen und Empfehlungen, die alle so strukturiert sind, dass sie die wertvollsten Aspekte des Eingangsmaterials hervorheben.

## extract_wisdom_dm
Die Eingabeaufforderung skizziert einen umfassenden Prozess zur Extraktion und Organisation wertvoller Inhalte aus dem Eingabetext, wobei der Schwerpunkt auf Erkenntnissen über den Sinn des Lebens, das menschliche Wohlbefinden und die Auswirkungen der Technologie liegt. Der Schwerpunkt liegt auf einem detaillierten, schrittweisen Ansatz zur Identifizierung von Ideen, Erkenntnissen, Zitaten, Gewohnheiten, Fakten, Referenzen und Empfehlungen aus dem Inhalt. Zu den erwarteten Ergebnissen gehören Zusammenfassungen, Listen von Ideen, Erkenntnissen, Zitaten, Gewohnheiten, Fakten, Verweisen und eine Zusammenfassung in einem Satz, die alle in Markdown formatiert sind und sich an bestimmte Wortzahlen und Artikelmengen halten.

## extract_wisdom_large
Ziel ist es, die wichtigsten Erkenntnisse, Ideen, Gewohnheiten, Fakten und Empfehlungen aus einem ausführlichen Gespräch über das Schreiben, die Kommunikation und den iterativen Prozess der Inhaltserstellung zu extrahieren und zu destillieren. Der nuancierte Ansatz beinhaltet die Identifizierung der Essenz effektiver Kommunikation, die Bedeutung von Authentizität beim Schreiben und den Wert der Destillation bei der Vermittlung von Ideen. Das erwartete Ergebnis umfasst kategorisierte Zusammenfassungen von Ideen, Einsichten, Gewohnheiten, Fakten, Empfehlungen und mehr, die alle darauf abzielen, das Verständnis und die Anwendung der besprochenen Grundsätze in Bezug auf Schreiben und Kommunikation zu verbessern.

## extract_wisdom_nometa
Die Aufforderung leitet dazu an, verschiedene Einsichten, Ideen, Zitate, Gewohnheiten, Fakten, Empfehlungen und Referenzen aus Textinhalten zu extrahieren und zu organisieren, die sich mit dem Sinn des Lebens, dem menschlichen Gedeihen und den Auswirkungen von Technologie und KI befassen. Der Schwerpunkt liegt dabei auf der Entdeckung überraschender und aufschlussreicher Informationen innerhalb dieser Themen. Die Ausgabe ist in Abschnitte für Zusammenfassungen, Ideen, Einsichten, Zitate, Gewohnheiten, Fakten, Referenzen und Empfehlungen gegliedert, mit spezifischen Anweisungen zu Länge und Format für jeden Eintrag.

## find_hidden_message
Die Aufforderung weist die KI an, politische Botschaften zu analysieren und zu interpretieren, wobei zwischen offenen und versteckten Botschaften zu unterscheiden ist. Der Schwerpunkt liegt auf einer zynischen Bewertung, die sich auf die zugrundeliegenden politischen Absichten und die erwarteten Handlungen des Publikums konzentriert. Die Ausgabe umfasst strukturierte Analysen und Zusammenfassungen sowohl offener als auch versteckter Botschaften, die durch Argumente und gewünschte Aktionen des Publikums unterstützt werden und mit verschiedenen Analyseebenen von zynisch bis positiv abschließen.

## find_logical_fallacies
Die Aufforderung fordert die KI auf, verschiedene Arten von Fehlschlüssen in einem gegebenen Text zu erkennen, wobei eine umfassende Liste von Fehlschlüssen als Referenz dient. Es wird betont, wie wichtig es ist, ungültige oder fehlerhafte Argumente zu erkennen. Die erwartete Ausgabe ist eine Liste identifizierter Trugschlüsse, die jeweils in einer 15-Wörter-Erklärung prägnant beschrieben und in einem Abschnitt "FALLACIES" in Markdown formatiert werden.

## get_wow_per_minute
Bewertet die Dichte des "Wow-Faktors" in Inhalten und konzentriert sich dabei auf Überraschung, Neuheit, Einsicht, Wert und Weisheit in verschiedenen Inhaltstypen. Damit soll quantifiziert werden, wie lohnend Inhalte auf der Grundlage dieser Elemente sind. Die erwartete Ausgabe ist eine JSON-Datei mit detaillierten Punktzahlen und Erklärungen für jede Komponente des Wow-Faktors pro Minute.

## get_youtube_rss
Erzeugt RSS-URLs für YouTube-Kanäle auf der Grundlage von angegebenen Kanal-IDs oder URLs. Es extrahiert die Kanal-ID aus der Eingabe und konstruiert die entsprechende RSS-URL. Die Ausgabe ist ausschließlich die RSS-URL.

## improve_academic_writing
Diese Eingabeaufforderung zielt darauf ab, Eingabetexte in eine akademische und wissenschaftliche Sprache zu übersetzen, die Klarheit, Kohärenz und Verständlichkeit gewährleistet. Der Schwerpunkt liegt auf der Verwendung von formellem Englisch und der Vermeidung von Wiederholungen und trivialen Aussagen, um einen professionellen Ton zu erreichen. Das erwartete Ergebnis ist ein für akademische Zwecke verbesserter Text.

## improve_prompt
Verbessert die Qualität von LLM/AI-Prompts durch die Anwendung von Expertenschreibtechniken, die sich auf Klarheit, Spezifität und strukturierte Anweisungen konzentrieren. Es nutzt Strategien wie klare Anweisungen, Persona-Annahme und die Bereitstellung von Referenztexten, um Modellantworten zu verbessern. Der Dienst gibt verfeinerte Prompts aus, die für eine optimale Interaktion mit LLMs ausgelegt sind.

## improve_report_finding
Verbessert einen Sicherheitsbefund aus einem Penetrationstestbericht, indem ein detaillierter und erweiterter Bericht im Markdown-Format bereitgestellt wird, der sich auf Beschreibung, Risiko, Empfehlungen und Referenzen konzentriert und den Befund prägnant zusammenfasst. Der Schwerpunkt liegt auf Klarheit, Aufschlussreichheit und umsetzbaren Ratschlägen, wobei Fachjargon und Wiederholungen vermieden werden. Die Ausgabe enthält einen Titel, eine detaillierte Beschreibung, eine Risikoanalyse, aufschlussreiche Empfehlungen, relevante Verweise, eine kurze Zusammenfassung und bemerkenswerte Zitate, die alle für eine leichte Lesbarkeit und sofortige Anwendung formatiert sind.

## verbessern_schreiben
Diese Aufforderung zielt darauf ab, den Eingabetext zu verfeinern und zu verbessern, um Klarheit, Kohärenz, Grammatik und Stil zu verbessern. Dabei wird der Text auf Fehler und Ungereimtheiten hin analysiert und anschließend korrigiert, ohne den ursprünglichen Sinn zu verändern. Die erwartete Ausgabe ist eine grammatikalisch korrekte und stilistisch verbesserte Version des Eingabetextes.

## label_and_rate
Die Aufforderung umreißt einen Prozess zur Bewertung von Inhalten auf der Grundlage ihrer Relevanz für bestimmte, auf den Menschen bezogene Themen, zur Zuweisung von Labels aus einer vordefinierten Liste und zur Bewertung ihrer Qualität und thematischen Ausrichtung. Es wird betont, wie wichtig es ist, dass sich die Inhalte auf das menschliche Wohlergehen und die Bedeutung konzentrieren, und es werden Inhalte bestraft, die politisch aufgeladen sind oder keinen Bezug zu den Kernthemen haben. Die erwartete Ausgabe ist ein strukturiertes JSON-Objekt, das das Wesen des Inhalts, die anwendbaren Kennzeichnungen, eine abgestufte Bewertung und eine numerische Qualitätsbewertung zusammen mit Erläuterungen zu diesen Bewertungen zusammenfasst.

## official_pattern_template
Analysiert den Hintergrund und die Verhaltensweisen einer Person, um psychologische Probleme zu diagnostizieren und Maßnahmen zu empfehlen. Es handelt sich um einen detaillierten Prozess des Verstehens der Geschichte und des aktuellen Verhaltens der Person, um die zugrunde liegenden Probleme zu identifizieren. Das Ergebnis umfasst Zusammenfassungen von Ereignissen, möglichen Problemen, Verhaltensverbindungen und Empfehlungen zur Korrektur.

## philocapsulate
Die Eingabeaufforderung weist Sie an, detaillierte Vorlagen über Philosophen oder Philosophien zu erstellen, einschließlich ihres Hintergrunds, ihrer Lehren und ihrer Anwendung. Sie gibt die Struktur für die Darstellung von Informationen an, wie z. B. die Kapselung von Philosophien, die Auflistung von Werken oder Lehren und die Definition von Begriffen wie "$philosopher-ian". Das erwartete Ergebnis ist ein umfassender Überblick, der entweder auf einen einzelnen Philosophen oder eine Philosophie zugeschnitten ist und die wichtigsten Aspekte und Ratschläge für ein Leben nach ihren Lehren hervorhebt.

## provide_guidance
Bietet eine umfassende psychologische Beratung, die auf die spezifische Frage und den Kontext des Einzelnen zugeschnitten ist. Dieser Ansatz kombiniert Elemente der Psychiatrie, der Psychologie und des Lebenscoachings und bietet eine strukturierte Analyse und umsetzbare Empfehlungen. Das erwartete Ergebnis umfasst eine prägnante Analyse, detaillierte wissenschaftliche Erklärungen, personalisierte Empfehlungen und Fragen zur Selbstreflexion.

## rate_ai_response
Bewertet die Qualität von KI-Antworten im Vergleich zu den weltbesten menschlichen Experten, wobei der Schwerpunkt auf dem Verständnis von Anweisungen, dem Vergleich der KI-Leistung mit der optimalen menschlichen Leistung und der Bewertung der KI-Arbeit anhand eines detaillierten Benotungssystems liegt. Der Prozess umfasst eine gründliche Analyse sowohl der an die KI gegebenen Anweisungen als auch ihrer Antworten, gefolgt von einer strukturierten Bewertung, die eine Briefnote, spezifische Gründe für die Note und eine numerische Punktzahl enthält. Die Bewertungskriterien legen den Schwerpunkt auf den Vergleich mit menschlichen Fähigkeiten, die von Experten- bis zu durchschnittlichen Leistungen reichen.

## rate_ai_result
Bewertet die Qualität von KI-generierten Inhalten auf der Grundlage von Aufbau, Qualität und Geist. Dieser Prozess umfasst die Analyse von KI-Ergebnissen anhand von Kriterien, die von Experten und einem hochqualifizierten KI-Gremium festgelegt wurden. Das Endergebnis ist eine umfassende Punktzahl von 100, die die Übereinstimmung des Inhalts mit den Anforderungen und dem Wesen der Aufforderung widerspiegelt.

## rate_content
Die Aufforderung umreißt ein Verfahren zur Bewertung von Inhalten, indem sie mit relevanten Ein-Wort-Beschreibungen versehen und dann anhand der Anzahl der Ideen und der thematischen Ausrichtung auf bestimmte Themen bewertet werden. Der Schwerpunkt liegt auf einem nuancierten Ansatz zur Bewertung von Inhalten, der quantitative und qualitative Maßnahmen kombiniert. Die erwartete Ausgabe umfasst eine Liste von Bezeichnungen, eine abgestufte Bewertung mit einer Erklärung und eine numerische Inhaltsbewertung mit Begründung.

## rate_value
Die Aufforderung zielt darauf ab, Inhalte zu erstellen, die von der Informationstheorie von Claude Shannon und den viralen Techniken von Mr. Beast inspiriert sind. Dabei werden grundlegende Kommunikationstheorien und moderne virale Strategien für die Erstellung wirkungsvoller Inhalte genutzt. Das erwartete Ergebnis ist ein ansprechender und weit verbreiteter Inhalt.

## raw_query
Die Eingabeaufforderung weist die KI an, die bestmögliche Ausgabe zu produzieren, indem sie die Eingabe gründlich analysiert und versteht. Sie legt Wert darauf, die Bedeutung der Eingabe und die Absichten des Absenders eingehend zu prüfen. Die erwartete Ausgabe ist eine optimale Antwort, die auf die wahrgenommenen Wünsche des Absenders der Eingabeaufforderung zugeschnitten ist.

## recommend_artists
Empfiehlt ein personalisiertes Festivalprogramm mit Künstlern, die den bevorzugten EDM-Stilen und Künstlern des Benutzers entsprechen. Der Prozess umfasst die Analyse der Lieblingsstile und -künstler des Benutzers, die Auswahl ähnlicher Künstler und die Erläuterung der Auswahl. Das Ergebnis ist ein für den Benutzer optimierter Tages-, Set-Zeit- und Bühnenplan.

## show_fabric_options_markmap
Fasst das Fabric-Projekt zusammen, ein Open-Source-Framework zur Integration von KI in tägliche Herausforderungen durch anpassbare Eingabeaufforderungen, die Patterns genannt werden. Es legt Wert auf Benutzerfreundlichkeit und Anpassungsfähigkeit und bietet Werkzeuge für eine Vielzahl von Aufgaben, von der Zusammenfassung von Inhalten bis zur Erstellung von KI-Kunst. Die erwartete Ausgabe umfasst eine visuelle Markmap-Darstellung der Fähigkeiten von Fabric.

## suggest_pattern
Entwickelt eine Funktion für ein Fabric-Befehlszeilen-Tool, das auf der Grundlage von Benutzereingaben geeignete Befehle oder Muster vorschlägt. Es beinhaltet die Analyse von Anfragen, die Bestimmung geeigneter Befehle und die Bereitstellung klarer Vorschläge. Die Ausgabe enthält Erklärungen oder mehrere Optionen, um die Zugänglichkeit für den Benutzer zu verbessern.

## zusammenfassen
Diese Eingabeaufforderung leitet dazu an, Inhalte in einem strukturierten Markdown-Format zusammenzufassen. Der Schwerpunkt liegt auf der Erstellung von prägnanten, informativen Zusammenfassungen mit spezifischen Abschnitten für eine Ein-Satz-Zusammenfassung, Hauptpunkte und Kernaussagen. Das erwartete Ergebnis ist eine übersichtliche Zusammenfassung mit klaren, eindeutigen Abschnitten.

## summarize_debate
Die Aufforderung skizziert einen Prozess zur Analyse von Debatten, wobei der Schwerpunkt auf der Identifizierung von Meinungsverschiedenheiten, Argumenten und Beweisen liegt, die die Meinung der Teilnehmer ändern könnten. Der Schwerpunkt liegt auf einer strukturierten Vorgehensweise bei der Zusammenfassung von Debatten, einschließlich der Extraktion von Schlüsselpunkten und der Bewertung der Stärke von Argumenten. Zu den erwarteten Ergebnissen gehören Zusammenfassungen des Inhalts, der Argumente und der Beweise sowie eine Analyse der Stärke der Argumente und Vorhersagen über den Ausgang der Debatte.

## summarize_git_changes
Fasst die wichtigsten Änderungen und Aktualisierungen eines GitHub-Projekts in der vergangenen Woche zusammen. Der Ansatz besteht darin, einen prägnanten Abschnitt mit dem Titel "CHANGES" mit Aufzählungspunkten zu erstellen, die jeweils auf 10 Wörter begrenzt sind. Die erwartete Ausgabe umfasst einen Einleitungssatz mit 20 Wörtern und Aufzählungspunkte, die die Aktualisierungen ausführlich beschreiben.

## summarize_git_diff
Analysiert Git-Diffs, um die wichtigsten Änderungen und Aktualisierungen zu identifizieren und zusammenzufassen. Diese Eingabeaufforderung konzentriert sich auf die Erstellung von prägnanten Zusammenfassungen in Form von Aufzählungspunkten für Projektaktualisierungen unter Verwendung herkömmlicher Commit-Nachrichten. Die erwartete Ausgabe umfasst einen kurzen Einleitungssatz, gefolgt von Aufzählungspunkten, in denen die Änderungen detailliert beschrieben werden.

## summarize_lecture
Extrahiert und organisiert die wichtigsten Themen aus einer Vorlesungsmitschrift und liefert strukturierte Zusammenfassungen, Definitionen und Zeitstempel. Dieser Prozess beinhaltet eine detaillierte Durchsicht des Transkripts, um die Hauptthemen zu identifizieren, Aufzählungspunkte zu erstellen und Definitionen mit den entsprechenden Zeitstempeln des Videos aufzulisten. Die Ausgabe enthält eine prägnante Zusammenfassung, eine Liste der erwähnten Hilfsmittel mit Beschreibungen und eine Zusammenfassung in einem Satz, die alle für eine leichte Lesbarkeit formatiert sind.

## zusammenfassen_micro
Die Eingabeaufforderung gibt Anweisungen zum Zusammenfassen von Inhalten in einem strukturierten Markdown-Format. Der Schwerpunkt liegt auf Prägnanz und Klarheit, wobei der Schwerpunkt auf einer Zusammenfassung in einem Satz, den Hauptpunkten und den wichtigsten Erkenntnissen liegt. Die erwartete Ausgabe ist eine gut organisierte Liste mit Aufzählungspunkten, die das Wesentliche des Inhalts hervorhebt.

## summarize_newsletter
Extrahiert und organisiert die wichtigsten Inhalte von Newslettern in einem strukturierten, einfach zu navigierenden Format. Es konzentriert sich auf die Zusammenfassung, Kategorisierung und Hervorhebung wesentlicher Informationen, einschließlich Meinungen, Tools und erwähnter Unternehmen. Das Ergebnis ist eine umfassende Aufschlüsselung des Inhalts des Newsletters zum schnellen Nachschlagen.

## summarize_paper
Erzeugt eine Zusammenfassung einer wissenschaftlichen Arbeit aus dem Volltext und konzentriert sich dabei auf wichtige Abschnitte wie Titel, Autoren, Hauptziele und Ergebnisse. Die Ausgabe wird zur besseren Übersichtlichkeit eindeutig in bestimmte Kategorien unterteilt. Die erwartete Ausgabe enthält Abschnitte über den Titel der Arbeit, die Autoren, das Hauptziel, den technischen Ansatz, die Besonderheiten, die experimentellen Ergebnisse, die Vorteile, die Einschränkungen und die Schlussfolgerung.

## zusammenfassen_prompt
Diese Aufforderung leitet dazu an, KI-Chat-Prompts prägnant zusammenzufassen. Es wird Wert darauf gelegt, dass die aktive Stimme und das Präsens verwendet werden, um Klarheit zu schaffen. Das erwartete Ergebnis ist ein knapper Absatz, der den Zweck, die Vorgehensweise und das erwartete Ergebnis der Aufforderung beschreibt.

## summarize_pull-requests
Der Prompt leitet dazu an, Pull-Requests für ein Coding-Projekt zusammenzufassen, wobei der Schwerpunkt auf der Erstellung einer Zusammenfassung und der detaillierten Beschreibung der wichtigsten Pull-Requests in einem lesbaren Format liegt. Der Schwerpunkt liegt auf dem Umschreiben von Pull-Requests zur besseren Übersichtlichkeit. Die erwartete Ausgabe enthält einen kurzen Überblick über die Art der Pull-Requests und eine Liste der wichtigsten Pull-Requests, die zur besseren Lesbarkeit umgeschrieben wurden.

## summarize_rpg_session
Fasst persönliche Rollenspielsitzungen zusammen und konzentriert sich dabei auf Schlüsselereignisse, Kampfdetails, Charakterentwicklung und Worldbuilding. Es verwandelt RPG-Transkripte in strukturierte Zusammenfassungen, die wichtige Momente und die Charakterentwicklung hervorheben. Die Ausgabe enthält eine heroische Zusammenfassung, detaillierte Kampfstatistiken, MVPs, Schlüsseldiskussionen, Charakterschwächen, Veränderungen, Zitate, Humor und Einblicke in den Aufbau der Welt.

## to_flashcards
Erstellt Anki-Karten aus Texten und hält sich dabei an die Prinzipien minimaler Informationen, optimierter Formulierungen und ohne externen Kontext. Dieser Ansatz gewährleistet Einfachheit, ohne dass wesentliche Details verloren gehen, und zielt auf schnelles und genaues Erinnern ab. Die Ausgabe ist eine Reihe von Fragen und Antworten, die als CSV-Tabelle formatiert sind.

## tweet
Leitet die Nutzer bei der Erstellung ansprechender Tweets mit Emojis an, angefangen beim Verständnis der Twitter-Grundlagen bis hin zur Analyse der Tweet-Leistung. Der Schwerpunkt liegt auf prägnanten Botschaften, der Einbindung des Publikums und dem strategischen Einsatz von Emojis für Persönlichkeit und Klarheit. Das erwartete Ergebnis sind verbesserte Tweeting-Fähigkeiten und eine bessere Interaktion mit dem Publikum.

## write_essay
Ziel dieser Aufforderung ist es, einen Aufsatz im Stil von Paul Graham zu verfassen, der sich auf ein bestimmtes Thema konzentriert und seinen klaren, einfachen und unterhaltsamen Schreibstil nachahmt. Der Aufsatz sollte keine Klischees, keinen Jargon und keine journalistische Sprache enthalten und die Ideen auf einfache Weise und ohne übliche Schlussphrasen präsentieren.

## write_hackerone_report
Unterstützt Bug-Bounty-Jäger beim Schreiben von Berichten für HackerOne, indem Anfragen, Antworten und Kommentare analysiert werden, um einen strukturierten Bericht zu erstellen. Es nutzt das `bbReportFormatter`-Tool zur Formatierung der Eingaben und erleichtert die dynamische, Plugin-in-integrierte oder Kommandozeilen-Berichterstellung. Die Ausgabe ist ein HackerOne-fertiger Bericht, der mit zusätzlichen Details verfeinert werden kann.

## write_micro_essay
Der Zweck dieser Aufforderung ist es, einen Aufsatz im Stil von Paul Graham zu verfassen, der sich auf das vorgegebene Thema konzentriert und einen einfachen, klaren und unterhaltsamen Stil verwendet. Der Aufsatz sollte keine Klischees, keinen Jargon und keine journalistische Sprache enthalten, sondern ein veröffentlichungsreifes Werk sein, das Grahams Schreibstil widerspiegelt. Der Inhalt sollte kurz und prägnant sein, nicht mehr als 250 Wörter umfassen und keine gebräuchlichen Schlusssätze oder einleitende Worte enthalten.

## write_nuclei_template_rule
``yaml
id: vhost-enum-flow

info:
  name: vhost-enum-flow
  Verfasser: tarunKoyalwar
  Schweregrad: info
  beschreibung: |
    vhost enumeration durch Extrahieren von potentiellen vhost Namen aus dem ssl Zertifikat.

Ablauf: |
  ssl();
  for (let vhost of iterate(template["ssl_domains"])) {
    set("vhost", vhost);
    http();
  }

ssl:
  - Adresse: "{{Host}}:{{Port}}"

http:
  - raw:
      - |
        GET / HTTP/1.1
        Host: {{vhost}}

    Übereinstimmungen:
      - typ: dsl
        dsl:
          - status_code != 400
          - status_code != 502

    Extraktoren:
      - typ: dsl
        dsl:
          - '"VHOST: " + vhost + ", SC: " + status_code + ", CL: " + content_length'
```

## write_pull-request
Die Eingabeaufforderung weist einen Software-Ingenieur an, eine detaillierte Pull-Request-Beschreibung zu verfassen, die auf der Ausgabe eines `git diff`-Befehls basiert, der die Änderungen zwischen dem aktuellen Zweig und dem Hauptrepository-Zweig vergleicht. Es wird Wert darauf gelegt, die Änderungen zu analysieren, ihren Zweck zu verstehen und sie klar im Markdown-Format zu dokumentieren, einschließlich Zusammenfassungen, Gründe, Auswirkungen und Testpläne. Das erwartete Ergebnis ist eine strukturierte PR-Beschreibung, die die Änderungen und ihre Auswirkungen auf das Projekt prägnant wiedergibt.

## write_semgrep_rule
Die Eingabeaufforderung fordert die Erstellung einer Semgrep-Regel zur Erkennung eines bestimmten Schwachstellenmusters im Code auf der Grundlage des angegebenen Kontexts und der Beispiele. Es wird betont, wie wichtig es ist, den allgemeinen Fall der Schwachstelle zu erfassen, anstatt sich nur auf die erwähnten spezifischen Fälle zu konzentrieren. Die erwartete Ausgabe ist eine gut strukturierte Semgrep-Regel, die mit der Syntax und den Fähigkeiten übereinstimmt, die im detaillierten Leitfaden zur Syntax von Semgrep-Regeln beschrieben sind, und die in der Lage ist, potenzielle Sicherheitsprobleme im Code zu identifizieren.

