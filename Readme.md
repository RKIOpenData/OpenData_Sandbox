Datensatzdokumentation  
# OpenData_Sandbox: Testdokumentation 

<br>

[**Robert Koch-Institut | RKI**](https://rki.de)  
Nordufer 20  
13353 Berlin  

<br>

---

**Zitieren**  
<!-- CITATION_START: {"citation_style": "apa"} -->
Name, V. (2025). Open Data Sandbox [Data set]. Zenodo. [https://doi.org/10.5072/zenodo.166598](https://doi.org/10.5072/zenodo.166598)
<!-- CITATION_END -->


**Inhaltsverzeichnis**   

<!-- TOC_START: {"heading_depth": 2} -->
- [OpenData_Sandbox: Testdokumentation](#opendata_sandbox:-testdokumentation)
  - [Beispieltext](#beispieltext)
  - [Hinweise zur Nachnutzung der Daten](#hinweise-zur-nachnutzung-der-daten)
  - [Appendix](#appendix)
- [OpenData_Sandbox: Test documentation](#opendata_sandbox:-test-documentation)
  - [Example text](#example-text)
  - [Guidelines for Reuse of the Data](#guidelines-for-reuse-of-the-data)
  - [Appendix](#appendix)
<!-- TOC_END -->

## Beispieltext 

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem.

Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a,
 
### Formatierungstests

#### Links
Link: [Robert Koch-Institut](https://rki.de) 

#### Email
Email: [OpenData@rki.de](mailto:opendata@rki.de)

#### Aufzählungen

* Punkt 1  
* Punkt 2

1. Punkt 1
2. Punkt 2


#### Mathematische Formeln

##### Block

$$ Gene_{normalisiert} = {Q_{KA\_aktuell}}/{Q_{KA\_median}} \cdot Gene_{gemittelt} $$

##### Inline

- $Q_{KA\_median}$ : Median des Volumenstrom der Kläranlage  



#### Variablen und Werte  


<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "Sandbox_Data", "lang": "de"} -->

Die Datei [Sandbox_Data.tsv](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Sandbox_Data.tsv) enthält die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen. Ein maschinenlesbares Datenschema ist im [Data Package Standard](https://datapackage.org/) in [tableschema_Sandbox_Data.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data.json) hinterlegt:
> [tableschema_Sandbox_Data.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable   | Typ     | Ausprägungen   | Beschreibung       |
|:-----------|:--------|:---------------|:-------------------|
| A          | integer | Werte: `1`     | Dataset Variable A |
| B          | number  | Werte: `1`     | Dataset Variable B |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->

<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "Sandbox_Data_lfs", "lang": "de"} -->

Die Datei [Sandbox_Data_lfs.tsv](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Sandbox_Data_lfs.tsv) enthält die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen. Ein maschinenlesbares Datenschema ist im [Data Package Standard](https://datapackage.org/) in [tableschema_Sandbox_Data_lfs.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data_lfs.json) hinterlegt:
> [tableschema_Sandbox_Data_lfs.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data_lfs.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable   | Typ     | Ausprägungen   | Beschreibung       |
|:-----------|:--------|:---------------|:-------------------|
| A          | integer | Werte: `1`     | Dataset Variable A |
| B          | number  | Werte: `1`     | Dataset Variable B |

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






Data set documentation  
# OpenData_Sandbox: Test documentation 

<br>

[**Robert Koch-Institut | RKI**](https://rki.de)  
Nordufer 20  
13353 Berlin  

<br>

---

**Citation**  
<!-- CITATION_START: {"citation_style": "apa"} -->
Name, V. (2025). Open Data Sandbox [Data set]. Zenodo. [https://doi.org/10.5072/zenodo.166598](https://doi.org/10.5072/zenodo.166598)
<!-- CITATION_END -->

 **Table of contents**  
 
<!-- TOC_START: {"heading_depth": 2} -->
- [OpenData_Sandbox: Testdokumentation](#opendata_sandbox:-testdokumentation)
  - [Beispieltext](#beispieltext)
  - [Hinweise zur Nachnutzung der Daten](#hinweise-zur-nachnutzung-der-daten)
  - [Appendix](#appendix)
- [OpenData_Sandbox: Test documentation](#opendata_sandbox:-test-documentation)
  - [Example text](#example-text)
  - [Guidelines for Reuse of the Data](#guidelines-for-reuse-of-the-data)
  - [Appendix](#appendix)
<!-- TOC_END -->

## Example text 

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem.

Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a,
 
### Formatting tests

#### Links
Link: [Robert Koch-Institut](https://rki.de) 

#### Email
Email: [OpenData@rki.de](mailto:opendata@rki.de)

#### Bullet points

* Point 1  
* Point 2

1. Point 1
2. Point 2


#### Mathematical formulae

##### Block

$$ Gene_{normalized} = {Q_{KA\_current}}/{Q_{KA\_median}} \cdot Gene_{averaged} $$

##### Inline

- $Q_{KA\_median}$ : Median of the volume flow of the wastewater treatment plant  



#### Variables and Values 


<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "Sandbox_Data", "lang": "en"} -->

The file [Sandbox_Data.tsv](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Sandbox_Data.tsv) contains the variables and their values shown in the following table. A machine-readable data schema is stored in [Data Package Format](https://datapackage.org/) in [tableschema_Sandbox_Data.en.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data.en.json):
> [tableschema_Sandbox_Data.en.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data.en.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable   | Type    | Characteristic   | Description        |
|:-----------|:--------|:-----------------|:-------------------|
| A          | integer | Values: `1`      | Dataset Variable A |
| B          | number  | Values: `1`      | Dataset Variable B |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->

<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "Sandbox_Data_lfs", "lang": "en"} -->

The file [Sandbox_Data_lfs.tsv](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Sandbox_Data_lfs.tsv) contains the variables and their values shown in the following table. A machine-readable data schema is stored in [Data Package Format](https://datapackage.org/) in [tableschema_Sandbox_Data_lfs.en.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data_lfs.en.json):
> [tableschema_Sandbox_Data_lfs.en.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data_lfs.en.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable   | Type    | Characteristic   | Description        |
|:-----------|:--------|:-----------------|:-------------------|
| A          | integer | Values: `1`      | Dataset Variable A |
| B          | number  | Values: `1`      | Dataset Variable B |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->


<!-- FOOTER_START: {"lang": "en"} -->


### Metadata

To increase findability, the provided data are described with metadata. The Metadata are distributed to the relevant platforms via GitHub Actions. There is a specific metadata file for each platform; these are stored in the metadata folder:

> [Metadaten/](https://github.com/robert-koch-institut/OpenData_Sandbox/tree/main/Metadaten/)

Versioning and DOI assignment are performed via [Zenodo.org](https://zenodo.org). The metadata prepared for import into Zenodo are stored in the [zenodo.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/zenodo.json). Documentation of the individual metadata variables can be found at https://developers.zenodo.org/representation.

> [Metadaten/zenodo.json](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/Metadaten/zenodo.json)

The zenodo.json includes the publication date and the date of the data status in the following format (example):
```
  "publication_date": "2024-06-19",
  "dates": [
    {
      "start": "2023-09-11T15:00:21+02:00",
      "end": "2023-09-11T15:00:21+02:00",
      "type": "Collected",
      "description": "Date when the Dataset was created"
    }
  ],
```

## Guidelines for Reuse of the Data

Open data from the RKI are available on [Zenodo.org](http://Zenodo.org/), [GitHub.com](http://GitHub.com/), [OpenCoDE](https://gitlab.opencode.de), and [Edoc.rki.de](http://Edoc.rki.de/):

- https://zenodo.org/communities/robertkochinstitut
- https://github.com/robert-koch-institut
- https://gitlab.opencode.de/robert-koch-institut
- https://edoc.rki.de/

### License

The "Open Data Sandbox" dataset is licensed under the [Creative Commons Attribution 4.0 International Public License | CC-BY](https://creativecommons.org/licenses/by/4.0/deed.en).

The data provided in the dataset are freely available, with the condition of attributing the Robert Koch Institute as the source, for anyone to process and modify, create derivatives of the dataset and use them for commercial and non-commercial purposes.      
Further information about the license can be found in the [LICENSE](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/LICENSE) or [LIZENZ](https://github.com/robert-koch-institut/OpenData_Sandbox/blob/main/LIZENZ) file of the dataset.


<!-- FOOTER_END -->


<!-- CUSTOM_MARKDOWN_START: {"id": "appendix.en"} -->

## Appendix

This is an example appendix 📂.
<!-- CUSTOM_MARKDOWN_END -->