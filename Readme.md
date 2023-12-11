#### Berechnung der Impfquoten

Die zugrundeliegenden Datensätze enthalten auf 5 Nachkommastellen gerundete Impfquoten in Prozent für die jeweils kleinste mögliche Einheit: pro Geburtsjahr/Kalenderjahr/Saison, Altersgruppe, Impfstatus und Landkreis (`Impfquote`). Berechnet wurden diese auf Grundlage der in [Tabelle 1](#Tabelle-1-Einschlusskriterien-für-die-Bildung-der-Studienpopulationen-zur-Impfquotenberechnung-der-Säuglings--und-Kinderimpfungen-in-der-KV-Impfsurveillance) dargestellten Kohorten. Zur Berechnung der Impfquoten für höhere Regionalebenen ist eine Bevölkerungsgewichtung (`Bevoelkerung_Gewicht`) zu nutzen. Die Bevölkerungszahl zur Gewichtung ist die Größe der Bevölkerung des jeweiligen Stratums (Statisches Bundesamt). Die Formel zur Berechnung der bevölkerungsgewichteten Impfquote lautet:

    
$$Impfquote_{gewichtet} = {\sum(Bevoelkerung_{Gewicht} * Impfquote) \over \sum(Bevoelkerung_{Gewicht})} $$


