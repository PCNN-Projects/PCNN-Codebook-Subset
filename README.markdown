# Ontology-Annotated Codebook Subset for Post-COVID Network Netherlands (PCNN)

## Description
This repository contains a curated subset of the ontology-annotated codebook developed for the Post-COVID Network Netherlands (PCNN), as presented in our MIE 2026 paper. The workflow harmonizes health data using ontologies (e.g., SNOMED CT, LOINC) and contextual suffixes, supporting FAIR principles. This subset demonstrates semantic mapping of variables and is adaptable to other domains. The codebook contains metadata only, ensuring privacy. Expert review is ongoing.

## Codebook Structure
| Column              | Description                                                    |
|---------------------|----------------------------------------------------------------|
| Theme               | Data domain (e.g., Demographics)                               |
| Subdomain           | Subcategory (e.g., General)                                    |
| Instrument          | Source instrument (e.g., none, COMPASS-31)                     |
| Variable_name_CBS   | Original variable name                                        |
| Variable_label      | Descriptive label (e.g., Date of birth)                        |
| Standardized_name   | Ontology term with prefix/suffix (e.g., sct_184099003, sct_84229001_sev) |
| DataType            | Data format (e.g., date, radio buttons)                        |

## How to Use
- Review the codebook to understand metadata structure and ontology mappings
- Use as a template for harmonizing your own health data
- Cite this resource if used in academic work

## License
Licensed under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) for reuse with attribution.

## Citation
Cite as: [ Hajar Hasannejadasl, Shuxin Zhang, Bianca M. Boxma-de Klerk, Jos Bosch5, Ronald Cornet3, Sander MJ van Kuijk]. (2026). A FAIRification Workflow for Semantic Harmonization of Health Data: Application in the Post-COVID Network Netherlands. *MIE 2026 Proceedings*. Codebook DOI: [10.5281/zenodo.XXXXXXX].

