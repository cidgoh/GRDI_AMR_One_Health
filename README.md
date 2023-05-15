# The GRDI-AMR

## Using genomics as a tool for understanding how antimicrobial resistance genes and resistant bacteria move throughout the Canadian food supply

“One Health” is a collaborative approach that recognizes that the health of people is closely connected to the health of animals and our shared environment. Genomic surveillance using a One Health approach is a powerful tool for understanding and tracking how pathogens affecting human health evolve and spread. Genomic surveillance of pathogens requires high quality sequence data as well as well structured contextual data. Contextual data is the sample, laboratory, clinical, epidemiological, and methods information that enables the interpretation of sequence data. One Health initiatives often involve data streams from different sources, agencies, sectors, and information management systems, and because the data is structured in different ways it is often difficult to harmonize and integrate. By structuring contextual data using community standards such as minimum information checklists and ontologies, this information can be more easily understood and used by both humans and computers, and can be more easily reused for different types of analyses.

Antimicrobial resistance occurs when microbes evolve mechanisms that protect them from the effects of antimicrobial agents (such as antibiotics), resulting in a decreased ability to treat infections and illnesses in people, animals and plants. Antibiotic resistance is a public health concern around the world and the number of bacteria that are resistant to antibiotics is increasing.

The [Canadian Antimicrobial Resistance Genomics Research and Development Initiative (AMR-GRDI)](https://grdi.canada.ca/en/projects/antimicrobial-resistance-amr-project) uses a genomics-based approach to understand how food production contributes to the development of antimicrobial resistance of human health concern, and explore strategies for reducing antimicrobial resistance in food production systems. The AMR-GRDI is a component of the Federal Action Plan for Antimicrobial Resistance and Use in Canada, and involves data streams from federal departments and agencies spanning human health, agriculture, the environment, and food regulation. Participating government departments and agencies include: Agriculture and Agri-Food Canada, the Canadian Food Inspection Agency, Environment and Climate Change Canada, Fisheries and Oceans Canada, Health Canada, the National Research Council of Canada, Natural Resources Canada, and the Public Health Agency of Canada. 

To better harmonize AMR-GRDI contextual data across sectors and agencies, CIDGOH is leading the Metadata Harmonization Working Group in the development of an ontology-based One Health AMR data standard for foodborne pathogens, which provides standardized fields, pick lists of controlled vocabulary and prescribed formats for the harmonized capture of contextual data. The standardized fields are based on community standards such as NCBI’s combined Pathogen and Environmental attribute package derived from internationally agreed upon Minimal Data for Matching (MDM) standards, as well as applicable fields from different MIxS packages (Genomic Standards Consortium). The data standard will also be harmonized with recently developed standards (e.g. One Health Enteric Package v1.0: Expanded and Standardized Metadata for Enteric Genomic Epidemiology in the U.S, and the Food MIxS package). 

### What are ontologies and how do they improve the quality of data in the GRDI-AMR?

Labs collect, encode and store information in different ways. They use different fields, terms and formats, they categorize variables in different ways, and the meanings of words change depending on the focus of the organization (think of the word “plant”. To someone in agriculture, “plant” could mean an organism that carries out photosynthesis, while a food regulator might understand the word “plant” to mean a factory where food products are made). This variability makes comparing, integrating and analyzing data generated by different organizations like trying to compare apples, oranges and bananas, which is difficult to do.
 
Ontologies are collections of controlled vocabulary that are arranged in a hierarchy, where all the terms are linked using logical relationships. Ontologies are open source and meant to represent “universal truth” as much as possible (so not tied to one organization’s vocabulary of use case). Ontologies encode synonyms, which enables mapping between the specific languages used by different organizations, and every term in the ontology is assigned a globally unique and persistent identifier. Using ontology terms to standardize GRDI-AMR contextual data not only helps make data more interoperable by using a common language, it also helps to make contextual data FAIR (Findable, Accessible, Interoperable, Reusable).

The GRDI-AMR specification is also [ISO 23418](https://www.iso.org/standard/75509.html) compliant (Microbiology of the food chain — Whole genome sequencing for typing and genomic characterization of bacteria — General requirements and guidance).

### The GRDI-AMR contextual data specification package

The AMR-GRDI standard is implemented via a spreadsheet-based data collection instrument (i.e. metadata template), accompanying Field and Term reference guides (which provide definitions and additional specific guidance) and a curation SOP. New terms can be added by making a new term request using the NTR SOP (please note that the specification will be updated periodically to address user needs). Find these resources below:
 
#### Data Collection Template 7.6.4
- [XLSX version](https://github.com/cidgoh/GRDI_AMR_One_Health/tree/main/Template)
- [DataHarmonizer App](https://github.com/cidgoh/pathogen-genomics-package/releases)
  - The [DataHarmonizer](https://github.com/cidgoh/DataHarmonizer) is a standardized browser-based spreadsheet editor and validator. Template name "GRDI".
  - Instructions on "[Getting Started](https://github.com/cidgoh/pathogen-genomics-package/wiki/DataHarmonizer-Getting-Started)".
 
#### Field and Term Reference Guides 7.6.4
- [XLSX version](https://github.com/cidgoh/GRDI_AMR_One_Health/tree/main/Reference%20Guide)
- [PDF version](https://github.com/cidgoh/GRDI_AMR_One_Health/tree/main/Reference%20Guide)
- [Online version](https://docs.google.com/spreadsheets/d/1crc7yQtd8aj5LJYyeDMrNWqUO-o9ulKRkSqAub-51gg/edit?usp=sharing)

#### Curation Standard Operating Procedure (SOP) 7.6
- [PDF version](https://github.com/cidgoh/GRDI_AMR_One_Health/tree/main/SOPs)
- [Online version](https://docs.google.com/document/d/e/2PACX-1vTFrkZ5CaZTgoQLnAnIYPVOrDhl1xkYvCaMIcQ4BfcvH77N9vcy5zRnjyM6dvl4ZwYK2EwhDTc1Rvl1/pub)

#### New Term Request Standard Operating Procedure (SOP) 1.2
- [PDF version](https://github.com/cidgoh/GRDI_AMR_One_Health/tree/main/SOPs)
- [Online version](https://docs.google.com/document/d/e/2PACX-1vQN0xPHYyr7Tgvu7RYHYGNY2QHh8Vb9XaoIw7we0VmaR5JsjV_OIdyn4wuGBz7dXPqFPT67mjJmjiUl/pub)

### Version Control
Changes to vocabulary in template pick lists are updated by incremental increases to the third position in the version (i.e. “Z” position). Changes to fields and features are updated by incremental increases to the second position in the version (i.e. “Y” position). Changes to basic infrastructure or major changes to functionality are updated by incremental increases to the first position in the version (i.e. “X” position).

Descriptions of updates are provided in [release notes](https://github.com/cidgoh/GRDI_AMR_One_Health/releases) for every new version.

Discussions contributing to updates may be tracked on the DataHarmonizer GitHub issue tracker.
