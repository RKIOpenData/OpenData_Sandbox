<!-- HEADER_START: {"lang": "de"} -->


Datensatzdokumentation
# Open Data Sandbox

<br> 
<br> 


[**AKTIN-Notaufnahmeregister**](http://aktin.org/), [**Robert Koch-Institut**](https://rki.de/)

**Beitragende**   
Susanne Drynda&sup1; (ProjectLeader), Ronny Otto&sup1; (DataManager), Wiebke Schirrmeister&sup1; (ProjectLeader), Jonas Bienzeisler&sup2; (DataManager), Alexander Kombeiz&sup2; (DataCurator), [Robert Koch-Institut | Fachgebiet 32](https://www.rki.de/DE/Institut/Organisation/Abteilungen/Abteilung-3/FG32/fg32-surveillance-und-elektronisches-melde-und-informationssystem-demis-oegd-kontaktstelle-node.html), [Madlen Schranz](https://orcid.org/0000-0002-2426-5770)&sup3; (Researcher), [Theresa Kocher](https://orcid.org/0000-0002-9300-6625)&sup3; (Researcher)

&emsp;&emsp;&sup1;[AKTIN-Notaufnahmeregister](http://aktin.org/) | [AKTIN-Geschäftsstelle](https://kchu.med.ovgu.de/Forschung/AG+Register_+und+Versorgungsforschung+in+der+Notfallmedizin/AKTIN.html)  
&emsp;&emsp;&sup2;[AKTIN-Notaufnahmeregister](http://aktin.org/) | [AKTIN-IT](https://www.medizin.rwth-aachen.de/cms/medizin/die-fakultaet/institute-und-kliniken/die-institute/klinisch-theoretische-institute/~ezkv/institut-fuer-medizinische-informatik/)  
&emsp;&emsp;&sup3;[Robert Koch-Institut](https://rki.de/) | [Fachgebiet 32](https://www.rki.de/DE/Institut/Organisation/Abteilungen/Abteilung-3/FG32/fg32-surveillance-und-elektronisches-melde-und-informationssystem-demis-oegd-kontaktstelle-node.html)

**Zitieren**  
Drynda, S., Otto, R., Schirrmeister, W., Bienzeisler, J., Kombeiz, A., Schranz, M., & Kocher, T. (2025). Open Data Sandbox [Data set]. Zenodo. [https://doi.org/10.5072/zenodo.171784](https://doi.org/10.5072/zenodo.171784)



**Zusammenfassung**  
Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum.




<!-- HEADER_END -->


**Inhaltsverzeichnis**   

<!-- TOC_START: {"heading_depth": 2} -->
- [Open Data Sandbox](#open-data-sandbox)
  - [Beispieltext](#beispieltext)
  - [Hinweise zur Nachnutzung der Daten](#hinweise-zur-nachnutzung-der-daten)
  - [Appendix](#appendix)
<!-- TOC_END -->

## Beispieltext 

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem.

Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a,
 

#### Variablen und Werte  


<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "Sandbox_Data", "lang": "de"} -->

Die Datei [Sandbox_Data.tsv](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Sandbox_Data.tsv) enthält die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen. Ein maschinenlesbares Datenschema ist im [Data Package Standard](https://datapackage.org/) in [tableschema_Sandbox_Data.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data.json) hinterlegt:
> [tableschema_Sandbox_Data.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable                                   | Typ     | Ausprägungen                                                                                                                                                                                                                                                                                       | Beschreibung                                                                                                            |
|:-------------------------------------------|:--------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------|
| date_and_time                              | date    | Format: `YYYY-MM-DDTHH:MM:SS`                                                                                                                                                                                                                                                                      | Datum der Probeentnahme im ISO 8601 Format ohne Zeitzone                                                                |
| date                                       | date    | Format: `YYYY-MM-DD`                                                                                                                                                                                                                                                                               | Datum der Probeentnahme im ISO 8601 Format ohne Zeitzone                                                                |
| week_as_date                               | date    | Format: `YYYY-ww`<br>Beispiel: `2021-04`                                                                                                                                                                                                                                                           | Berichtswoche im ISO-8601 Format ohne Zeitzone                                                                          |
| season                                     | string  | Beispiel: `2012/13`                                                                                                                                                                                                                                                                                | Saison jeweils von Kalenderwoche 40 bis Kalenderwoche 39 des Folgejahres (z.B. Saison 2012/13 = 2012W40 bis<br>2013W39) |
| text_with_fixed_set_of_<br>possible_values | string  | Werte: `random`, `requested`, `clinical`, `unknown, other`                                                                                                                                                                                                                                         | Mögliche Werte: `random`, `requested`, `clinical`, `unknown, other`                                                     |
| text_with_very_long_example                | string  | Beispiel: `873a7cc28d29e3f17b0544ea6e9e84`<br>`36defe32f6d60649159ee8ac78d414`<br>`7ac9`                                                                                                                                                                                                           | Eine Variable die eine lange ID enthält                                                                                 |
| number_with_minimum                        | number  | Werte: `≥2.5`                                                                                                                                                                                                                                                                                      | Gleitkommazahl mit inklusivem Minimum                                                                                   |
| integer_with_range                         | integer | Werte: `0` - `99999`<br>Beispiel: `1095`                                                                                                                                                                                                                                                           | Ganze Zahl (Zählwerte)                                                                                                  |
| integer_with_missing_values                | integer | Werte: `≥-1`<br>Fehlende Werte: `NA`                                                                                                                                                                                                                                                               | Ganze Zahl mit fehlenden Werten                                                                                         |
| text_with_json_example                     | string  | Beispiele: `[{'method': 'PANGOLIN_LATEST'`, `'classification_version': 'PUSHER-v1.28.1'`, `'tool_version': '4.3'`, `'lineage': 'BA.2'`, `'@qc_notes': 'Ambiguous_content:0.02'`, `'@is_designated': False`, `'@qc_status': 'pass'`, `'@conflict': 0.0`, `'@note': 'Usher placements: BA.2(1/1)'}]` | Text mit Beispiel im JSON-Format                                                                                        |
| unique_variable                            | integer |                                                                                                                                                                                                                                                                                                    | Jeder Wert kommt nur einmal im Datensatz vor.                                                                           |
| url                                        | string  | Beispiel: `https://www.gbe.rki.de/DE/Them`<br>`en/EinflussfaktorenAufDieGesun`<br>`dheit/GesundheitsUndRisikoverh`<br>`alten/Alkoholkonsum/Rauschtrin`<br>`ken/rauschtrinken_node.html`                                                                                                            | Link zu Ressource                                                                                                       |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->


<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "Sandbox_Data_lfs", "lang": "de"} -->

Die Datei [Sandbox_Data_lfs.tsv](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Sandbox_Data_lfs.tsv) enthält die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen. Ein maschinenlesbares Datenschema ist im [Data Package Standard](https://datapackage.org/) in [tableschema_Sandbox_Data_lfs.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data_lfs.json) hinterlegt:
> [tableschema_Sandbox_Data_lfs.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data_lfs.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable                                   | Typ     | Ausprägungen                                                                                                                                                                                                                                                                                       | Beschreibung                                                                                                            |
|:-------------------------------------------|:--------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------|
| date_and_time                              | date    | Format: `YYYY-MM-DDTHH:MM:SS`                                                                                                                                                                                                                                                                      | Datum der Probeentnahme im ISO 8601 Format ohne Zeitzone                                                                |
| date                                       | date    | Format: `YYYY-MM-DD`                                                                                                                                                                                                                                                                               | Datum der Probeentnahme im ISO 8601 Format ohne Zeitzone                                                                |
| week_as_date                               | date    | Format: `YYYY-ww`<br>Beispiel: `2021-04`                                                                                                                                                                                                                                                           | Berichtswoche im ISO-8601 Format ohne Zeitzone                                                                          |
| season                                     | string  | Beispiel: `2012/13`                                                                                                                                                                                                                                                                                | Saison jeweils von Kalenderwoche 40 bis Kalenderwoche 39 des Folgejahres (z.B. Saison 2012/13 = 2012W40 bis<br>2013W39) |
| text_with_fixed_set_of_<br>possible_values | string  | Werte: `random`, `requested`, `clinical`, `unknown, other`                                                                                                                                                                                                                                         | Mögliche Werte: `random`, `requested`, `clinical`, `unknown, other`                                                     |
| text_with_very_long_example                | string  | Beispiel: `873a7cc28d29e3f17b0544ea6e9e84`<br>`36defe32f6d60649159ee8ac78d414`<br>`7ac9`                                                                                                                                                                                                           | Eine Variable die eine lange ID enthält                                                                                 |
| number_with_minimum                        | number  | Werte: `≥2.5`                                                                                                                                                                                                                                                                                      | Gleitkommazahl mit inklusivem Minimum                                                                                   |
| integer_with_range                         | integer | Werte: `0` - `99999`<br>Beispiel: `1095`                                                                                                                                                                                                                                                           | Ganze Zahl (Zählwerte)                                                                                                  |
| integer_with_missing_values                | integer | Werte: `≥-1`<br>Fehlende Werte: `NA`                                                                                                                                                                                                                                                               | Ganze Zahl mit fehlenden Werten                                                                                         |
| text_with_json_example                     | string  | Beispiele: `[{'method': 'PANGOLIN_LATEST'`, `'classification_version': 'PUSHER-v1.28.1'`, `'tool_version': '4.3'`, `'lineage': 'BA.2'`, `'@qc_notes': 'Ambiguous_content:0.02'`, `'@is_designated': False`, `'@qc_status': 'pass'`, `'@conflict': 0.0`, `'@note': 'Usher placements: BA.2(1/1)'}]` | Text mit Beispiel im JSON-Format                                                                                        |
| unique_variable                            | integer |                                                                                                                                                                                                                                                                                                    | Jeder Wert kommt nur einmal im Datensatz vor.                                                                           |
| url                                        | string  | Beispiel: `https://www.gbe.rki.de/DE/Them`<br>`en/EinflussfaktorenAufDieGesun`<br>`dheit/GesundheitsUndRisikoverh`<br>`alten/Alkoholkonsum/Rauschtrin`<br>`ken/rauschtrinken_node.html`                                                                                                            | Link zu Ressource                                                                                                       |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->



<!-- FOOTER_START: {"lang": "de"} -->



### Metadaten  

Zur Erhöhung der Auffindbarkeit sind die bereitgestellten Daten mit Metadaten beschrieben. Über GitHub Actions werden Metadaten an die entsprechenden Plattformen verteilt. Für jede Plattform existiert eine spezifische Metadatendatei, diese sind im Metadatenordner hinterlegt:  

> [Metadaten/](https://github.com/robert-koch-institut/OpenData_Sandbox/tree/main/Metadaten/) 

Versionierung und DOI-Vergabe erfolgt über [Zenodo.org](https://zenodo.org). Die für den Import in Zenodo bereitgestellten Metadaten sind in der [zenodo.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/zenodo.json) hinterlegt. Die Dokumentation der einzelnen Metadatenvariablen ist unter https://developers.zenodo.org/#representation nachlesbar.
 
> [Metadaten/zenodo.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/zenodo.json)  

In der zenodo.json ist neben dem Publikationsdatum (`"publication_date"`) auch der Datenstand in folgendem Format enthalten (Beispiel):  

```
  "dates": [
    {
      "start": "2023-09-11T15:00:21+02:00",
      "end": "2023-09-11T15:00:21+02:00",
      "type": "Collected",
      "description": "Date when the Dataset was created"
    }
  ],
```    


Zusätzlich beschreiben wir tabellarische Daten mithilfe des [Data Package Standards](https://datapackage.org/).
Ein Data Package ist eine strukturierte Sammlung von Daten und zugehörigen Metadaten, die den Austausch und die Wiederverwendung von Daten erleichtert. Es besteht aus einer datapackage.json-Datei, die zentrale Informationen wie die enthaltenen Ressourcen, ihre Formate und Schema-Definitionen beschreibt.

Der Data Package Standard wird von der [Open Knowledge Foundation](https://okfn.org/) bereitgestellt und ist ein offenes Format, das eine einfache, maschinenlesbare Beschreibung von Datensätzen ermöglicht.

Die Liste der in diesem Repository enthaltenen Daten ist in folgender Datei hinterlegt:

> [datapackage.json]($GITHUB_REPOSITORY_URL/tree/main/datapackage.json)

Für tabellarische Daten definieren wir zusätzlich ein [Table Schema](https://datapackage.org/standard/table-schema/), das die Struktur der Tabellen beschreibt, einschließlich Spaltennamen, Datentypen und Validierungsregeln. Diese Schema-Dateien finden sich unter:

> [Metadaten/schemas/]($GITHUB_REPOSITORY_URL/tree/main/Metadaten/schemas) 



## Hinweise zur Nachnutzung der Daten  

Offene Forschungsdaten des RKI werden auf [Zenodo.org](http://Zenodo.org/), [GitHub.com](http://GitHub.com/), [OpenCoDE](https://gitlab.opencode.de) und [Edoc.rki.de](http://Edoc.rki.de/) bereitgestellt:  

- https://zenodo.org/communities/robertkochinstitut  
- https://github.com/robert-koch-institut  
- https://gitlab.opencode.de/robert-koch-institut  
- https://edoc.rki.de/  
 
### Lizenz  

Der Datensatz "Open Data Sandbox" ist lizenziert unter  der [Creative Commons Namensnennung 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de).  

Die im Datensatz bereitgestellten Daten sind, unter Bedingung der Namensnennung des Robert Koch-Instituts als Quelle, frei verfügbar. Das bedeutet, jede Person hat das Recht die Daten zu verarbeiten und zu verändern, Derivate des Datensatzes zu erstellen und sie für kommerzielle und nicht kommerzielle Zwecke zu nutzen. Weitere Informationen zur Lizenz finden sich in der [LICENSE](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/LICENSE) bzw. [LIZENZ](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/LIZENZ) Datei des Datensatzes.  
<!-- FOOTER_END -->



<!-- CUSTOM_MARKDOWN_START: {"id": "appendix"} -->

## Appendix

Dies ist ein Beispiel-Appendix 📂.
<!-- CUSTOM_MARKDOWN_END -->




