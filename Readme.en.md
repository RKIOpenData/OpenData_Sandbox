<!-- HEADER_START: {"lang": "en"} -->


Documentation  

# Open Data Sandbox

<br> 
<br> 
<br> 

[**Vorname Name**](https://orcid.org/0000-0002-2818-3641)&sup1;

<br> 



&emsp;&emsp;&sup1; Robert Koch Institute

<br> 

**Cite**  
Name, V. (2026). Open Data Sandbox [Data set]. Zenodo. [https://doi.org/10.5072/zenodo.318172](https://doi.org/10.5072/zenodo.318172)


<br>

**Abstract**    
Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum Lorem Ipsum.

<br>

**Table of Content**  

<!-- TOC_START: {"heading_depth": 2} -->
  - [Example text](#example-text)  
  - [Guidelines for reuse of the data](#guidelines-for-reuse-of-the-data)  
  - [Appendix](#appendix)  
<!-- TOC_END -->

<br>

<!-- HEADER_END -->


**Inhaltsverzeichnis**   


## Example text 

Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis, sem.

Nulla consequat massa quis enim. Donec pede justo, fringilla vel, aliquet nec, vulputate eget, arcu. In enim justo, rhoncus ut, imperdiet a, venenatis vitae, justo. Nullam dictum felis eu pede mollis pretium. Integer tincidunt. Cras dapibus. Vivamus elementum semper nisi. Aenean vulputate eleifend tellus. Aenean leo ligula, porttitor eu, consequat vitae, eleifend ac, enim. Aliquam lorem ante, dapibus in, viverra quis, feugiat a,
 

#### Variables and values  


<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "Sandbox_Data", "lang": "en"} -->

The file [Sandbox_Data.tsv](https://github.com/RKIOpenData/OpenData_Sandbox/blob/main/Sandbox_Data.tsv) contains the variables and their values shown in the following table. A machine-readable data schema is stored in [Data Package Format](https://datapackage.org/) in [tableschema_Sandbox_Data.en.json](https://github.com/RKIOpenData/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data.en.json):

> [tableschema_Sandbox_Data.en.json](https://github.com/RKIOpenData/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data.en.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable                                   | Type    | Characteristic                                                                                                                                                                                                                                                                                    | Description   |
|:-------------------------------------------|:--------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|
| date_and_time                              | date    | Format: `YYYY-MM-DDTHH:MM:SS`                                                                                                                                                                                                                                                                     |               |
| date                                       | date    | Format: `YYYY-MM-DD`                                                                                                                                                                                                                                                                              |               |
| week_as_date                               | date    | Example: `2021-04`<br>Format: `YYYY-ww`                                                                                                                                                                                                                                                           |               |
| season                                     | string  | Example: `2012/13`                                                                                                                                                                                                                                                                                |               |
| text_with_fixed_set_of_<br>possible_values | string  | Values:<br>`random`, `requested`, `clinical`, `unknown, other`                                                                                                                                                                                                                                    |               |
| text_with_very_long_<br>example            | string  | Example: `873a7cc28d29e3f17b0544ea6`<wbr>`e9e8436defe32f6d60649159e`<wbr>`e8ac78d4147ac9`                                                                                                                                                                                                         |               |
| number_with_minimum                        | number  | Values: `≥2.5`                                                                                                                                                                                                                                                                                    |               |
| integer_with_range                         | integer | Values: `0` - `99999`<br>Example: `1095`                                                                                                                                                                                                                                                          |               |
| integer_with_missing_<br>values            | integer | Values: `≥-1`<br>Missing values:<br>`NA`                                                                                                                                                                                                                                                          |               |
| text_with_json_example                     | string  | Examples: `[{'method': 'PANGOLIN_LATEST'`, `'classification_version': 'PUSHER-v1.28.1'`, `'tool_version': '4.3'`, `'lineage': 'BA.2'`, `'@qc_notes': 'Ambiguous_content:0.02'`, `'@is_designated': False`, `'@qc_status': 'pass'`, `'@conflict': 0.0`, `'@note': 'Usher placements: BA.2(1/1)'}]` |               |
| unique_variable                            | integer |                                                                                                                                                                                                                                                                                                   |               |
| url                                        | string  | Example: `https://www.gbe.rki.de/DE`<wbr>`/Themen/EinflussfaktorenA`<wbr>`ufDieGesundheit/Gesundhei`<wbr>`tsUndRisikoverhalten/Alko`<wbr>`holkonsum/Rauschtrinken/r`<wbr>`auschtrinken_node.html`                                                                                                 |               |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->


<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "Sandbox_Data_lfs", "lang": "en"} -->

The file [Sandbox_Data_lfs.tsv](https://github.com/RKIOpenData/OpenData_Sandbox/blob/main/Sandbox_Data_lfs.tsv) contains the variables and their values shown in the following table. A machine-readable data schema is stored in [Data Package Format](https://datapackage.org/) in [tableschema_Sandbox_Data_lfs.en.json](https://github.com/RKIOpenData/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data_lfs.en.json):

> [tableschema_Sandbox_Data_lfs.en.json](https://github.com/RKIOpenData/OpenData_Sandbox/blob/main/Metadaten/schemas/tableschema_Sandbox_Data_lfs.en.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable                                   | Type    | Characteristic                                                                                                                                                                                                                                                                                    | Description   |
|:-------------------------------------------|:--------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------|
| date_and_time                              | date    | Format: `YYYY-MM-DDTHH:MM:SS`                                                                                                                                                                                                                                                                     |               |
| date                                       | date    | Format: `YYYY-MM-DD`                                                                                                                                                                                                                                                                              |               |
| week_as_date                               | date    | Example: `2021-04`<br>Format: `YYYY-ww`                                                                                                                                                                                                                                                           |               |
| season                                     | string  | Example: `2012/13`                                                                                                                                                                                                                                                                                |               |
| text_with_fixed_set_of_<br>possible_values | string  | Values:<br>`random`, `requested`, `clinical`, `unknown, other`                                                                                                                                                                                                                                    |               |
| text_with_very_long_<br>example            | string  | Example: `873a7cc28d29e3f17b0544ea6`<wbr>`e9e8436defe32f6d60649159e`<wbr>`e8ac78d4147ac9`                                                                                                                                                                                                         |               |
| number_with_minimum                        | number  | Values: `≥2.5`                                                                                                                                                                                                                                                                                    |               |
| integer_with_range                         | integer | Values: `0` - `99999`<br>Example: `1095`                                                                                                                                                                                                                                                          |               |
| integer_with_missing_<br>values            | integer | Values: `≥-1`<br>Missing values:<br>`NA`                                                                                                                                                                                                                                                          |               |
| text_with_json_example                     | string  | Examples: `[{'method': 'PANGOLIN_LATEST'`, `'classification_version': 'PUSHER-v1.28.1'`, `'tool_version': '4.3'`, `'lineage': 'BA.2'`, `'@qc_notes': 'Ambiguous_content:0.02'`, `'@is_designated': False`, `'@qc_status': 'pass'`, `'@conflict': 0.0`, `'@note': 'Usher placements: BA.2(1/1)'}]` |               |
| unique_variable                            | integer |                                                                                                                                                                                                                                                                                                   |               |
| url                                        | string  | Example: `https://www.gbe.rki.de/DE`<wbr>`/Themen/EinflussfaktorenA`<wbr>`ufDieGesundheit/Gesundhei`<wbr>`tsUndRisikoverhalten/Alko`<wbr>`holkonsum/Rauschtrinken/r`<wbr>`auschtrinken_node.html`                                                                                                 |               |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->



<!-- FOOTER_START: {"lang": "en"} -->


### Metadata

To increase findability, the provided data are described with metadata. The Metadata are distributed to the relevant platforms via GitHub Actions. There is a specific metadata file for each platform; these are stored in the metadata folder:

> [Metadaten/](https://github.com/RKIOpenData/OpenData_Sandbox/tree/main/Metadaten/)

Versioning and DOI assignment are performed via [Zenodo.org](https://zenodo.org). The metadata prepared for import into Zenodo are stored in the [zenodo.json](https://github.com/RKIOpenData/OpenData_Sandbox/blob/main/Metadaten/zenodo.json). Documentation of the individual metadata variables can be found at [https://developers.zenodo.org/representation](https://developers.zenodo.org/#representation).

> [Metadaten/zenodo.json](https://github.com/RKIOpenData/OpenData_Sandbox/blob/main/Metadaten/zenodo.json)

The zenodo.json includes the publication date and the date of the data status in the following format (example):
```
  "publication_date": "2024-06-19",
  "dates": [
    {
      "start": "2023-09-11T15:00:21+02:00",
      "end": "2023-09-11T15:00:21+02:00",
      "type": "Created",
      "description": "Date when the published data was created"
    }
  ],
```


Additionally, we describe tabular data using the [Data Package Standard](https://datapackage.org/).  
A Data Package is a structured collection of data and associated metadata that facilitates data exchange and reuse. It consists of a `datapackage.json` file that contains key information such as the included resources, their formats, and schema definitions.  

The Data Package Standard is provided by the [Open Knowledge Foundation](https://okfn.org/) and is an open format that enables a simple, machine-readable description of datasets.  

The list of data included in this repository can be found in the following file:  

> [datapackage.json](https://github.com/RKIOpenData/OpenData_Sandbox/tree/main/datapackage.json)  

For tabular data, we additionally define a [Table Schema](https://datapackage.org/standard/table-schema/) that describes the structure of the tables, including column names, data types, and validation rules. These schema files can be found in:  

> [Metadaten/schemas/](https://github.com/RKIOpenData/OpenData_Sandbox/tree/main/Metadaten/schemas)  



## Guidelines for reuse of the data

Open data from the RKI are available on [Zenodo.org](http://Zenodo.org/), [GitHub.com](http://GitHub.com/), [OpenCoDE](https://gitlab.opencode.de), and [Edoc.rki.de](http://Edoc.rki.de/):

- https://zenodo.org/communities/robertkochinstitut
- https://github.com/robert-koch-institut
- https://gitlab.opencode.de/robert-koch-institut
- https://edoc.rki.de/



### License

The "Open Data Sandbox" dataset is licensed under the [Creative Commons Attribution 4.0 International Public License | CC-BY](https://creativecommons.org/licenses/by/4.0/deed.en).

The data provided in the dataset are freely available, with the condition of attributing the Robert Koch Institute as the source, for anyone to process and modify, create derivatives of the dataset and use them for commercial and non-commercial purposes.      
Further information about the license can be found in the [LICENSE](https://github.com/RKIOpenData/OpenData_Sandbox/blob/main/LICENSE) or [LIZENZ](https://github.com/RKIOpenData/OpenData_Sandbox/blob/main/LIZENZ) file of the dataset.


<!-- FOOTER_END -->



<!-- CUSTOM_MARKDOWN_START: {"id": "appendix"} -->

## Appendix

This is an example appendix 📂.
<!-- CUSTOM_MARKDOWN_END -->




