# The GRDI-AMR / GAOH Specification

## Table of Contents

<!-- TOC start (generated with https://github.com/derlin/bitdowntoc) -->

- **[Using genomics for understanding how AMR genes and resistant bacteria move throughout the Canadian food supply](#using-genomics-for-understanding-how-amr-genes-and-resistant-bacteria-move-throughout-the-canadian-food-supply)**
   * [What are ontologies and how do they improve the quality of data in the GRDI-AMR?](#what-are-ontologies-and-how-do-they-improve-the-quality-of-data-in-the-grdi-amr)
     
- **[The GRDI-AMR One Health Specification Package](#the-grdi-amr-one-health-specification-package)**
   * [Manuscripts](#manuscripts)
   * [Data Collection Template](#data-collection-template)
   * [Field and Term Reference Guide](#field-and-term-reference-guide)
   * [GRDI-AMR/GAOH Specification Curation SOP](#grdi-amrgaoh-specification-curation-sop)
   * [GAOH Metadata and Sequence Standardization and Submission SOP](#gaoh-metadata-and-sequence-standardization-and-submission-sop)
   * [DataHarmonizer SOP](#dataharmonizer-sop)
   * [New Term Request SOP](#new-term-request-sop)
     
- **[Version Control](#version-control)**

<!-- TOC end -->

## Using genomics for understanding how AMR genes and resistant bacteria move throughout the Canadian food supply

“One Health” is a collaborative approach that recognizes that the health of people is closely connected to the health of animals and our shared environment. Genomic surveillance using a One Health approach is a powerful tool for understanding and tracking how pathogens affecting human health evolve and spread. Genomic surveillance of pathogens requires high quality sequence data as well as well structured contextual data. Contextual data is the sample, laboratory, clinical, epidemiological, and methods information that enables the interpretation of sequence data. One Health initiatives often involve data streams from different sources, agencies, sectors, and information management systems, and because the data is structured in different ways it is often difficult to harmonize and integrate. By structuring contextual data using community standards such as minimum information checklists and ontologies, this information can be more easily understood and used by both humans and computers, and can be more easily reused for different types of analyses.

Antimicrobial resistance occurs when microbes evolve mechanisms that protect them from the effects of antimicrobial agents (such as antibiotics), resulting in a decreased ability to treat infections and illnesses in people, animals and plants. Antibiotic resistance is a public health concern around the world and the number of bacteria that are resistant to antibiotics is increasing.

In support of the Canadian Federal Action Plan for Antimicrobial Resistance (AMR) and Use in Canada (Public Health Agency of Canada, 2015), as well as the Pan-Canadian Action Plan on Antimicrobial Resistance (Public Health Agency of Canada, 2023), the Genomics Research and Development Initiative Shared Priority Projects for AMR ([GRDI-AMR](https://grdi.canada.ca/en/projects/antimicrobial-resistance-amr-project) and [GRDI-AMR-One Health](https://grdi.canada.ca/en/projects/antimicrobial-resistance-2-amr2-project) (GAOH; aka GRDI-AMR2)) uses a genomics-based approach to understand how food production contributes to the development of antimicrobial resistance of human health concern, and explore strategies for reducing antimicrobial resistance in food production systems. The AMR-GRDI is a component of the Federal Action Plan for Antimicrobial Resistance and Use in Canada, and involves data streams from federal departments and agencies spanning human health, agriculture, the environment, and food regulation. Participating government departments and agencies include: Agriculture and Agri-Food Canada, the Canadian Food Inspection Agency, Environment and Climate Change Canada, Fisheries and Oceans Canada, Health Canada, the National Research Council of Canada, Natural Resources Canada, and the Public Health Agency of Canada. 

To better harmonize AMR-GRDI contextual data across sectors and agencies, CIDGOH is leading the Metadata Harmonization Working Group in the development of an ontology-based One Health AMR data standard for foodborne pathogens, which provides standardized fields, pick lists of controlled vocabulary and prescribed formats for the harmonized capture of contextual data. The standardized fields are based on community standards such as NCBI’s combined Pathogen and Environmental attribute package derived from internationally agreed upon Minimal Data for Matching (MDM) standards, as well as applicable fields from different MIxS packages (Genomic Standards Consortium). The data standard will also be harmonized with recently developed standards (e.g. One Health Enteric Package v1.0: Expanded and Standardized Metadata for Enteric Genomic Epidemiology in the U.S, and the Food MIxS package). 

### What are ontologies and how do they improve the quality of data in the GRDI-AMR?

Labs collect, encode and store information in different ways. They use different fields, terms and formats, they categorize variables in different ways, and the meanings of words change depending on the focus of the organization (think of the word “plant”. To someone in agriculture, “plant” could mean an organism that carries out photosynthesis, while a food regulator might understand the word “plant” to mean a factory where food products are made). This variability makes comparing, integrating and analyzing data generated by different organizations like trying to compare apples, oranges and bananas, which is difficult to do.
 
Ontologies are collections of controlled vocabulary that are arranged in a hierarchy, where all the terms are linked using logical relationships. Ontologies are open source and meant to represent “universal truth” as much as possible (so not tied to one organization’s vocabulary of use case). Ontologies encode synonyms, which enables mapping between the specific languages used by different organizations, and every term in the ontology is assigned a globally unique and persistent identifier. Using ontology terms to standardize GRDI-AMR contextual data not only helps make data more interoperable by using a common language, it also helps to make contextual data FAIR (Findable, Accessible, Interoperable, Reusable).

The GRDI-AMR specification is also [ISO 23418](https://www.iso.org/standard/75509.html) compliant (Microbiology of the food chain — Whole genome sequencing for typing and genomic characterization of bacteria — General requirements and guidance).

## The GRDI-AMR One Health Specification Package

The GRDI-AMR standard is implemented via a spreadsheet-based data collection instrument (i.e. metadata template), accompanying Field and Term reference guides (which provide definitions and additional specific guidance) and a curation Standard Operating Procedure (SOP). New terms can be added by making a new term request using the New Term Request SOP (please note that the specification will be updated periodically to address user needs). Find these resources below:

### Manuscripts

**Implementation Manuscript:** Crossing the streams: improving data quality and integration across the One Health genomics continuum with data standards and implementation strategies
> Griffiths EJ, Jurga E, Wajnberg G, _et al._ Crossing the streams: improving data quality and integration across the One Health genomics continuum with data standards and implementation strategies. _Can J Microbiol._ 2025;71:1-14. [doi:10.1139/cjm-2024-0203](https://doi.org/10.1139/cjm-2024-0203)

**Design Manuscript:** The Broom of the System: A Harmonized Contextual Data Specification for One Health AMR Pathogen Genomic Surveillance
> Griffiths, Emma, _et al._ The Broom of the System: A Harmonized Contextual Data Specification for One Health AMR Pathogen Genomic Surveillance. _OSF Preprints_, 2024. [doi:10.31219/osf.io/xbf4t_v1](https://doi.org/10.31219/osf.io/xbf4t_v1)
 
### Data Collection Template
A specification template to facilate data curation and harmonization.

- [**XLSX version**](https://github.com/cidgoh/GRDI_AMR_One_Health/tree/main/Template)
  - A tabular, macro-containing excel spreadsheet version of the specification with a "merged sheet" generated from all the data across individual tabs.
- [**DataHarmonizer version**](https://github.com/cidgoh/pathogen-genomics-package/releases)
  - A standardized template-driven spreadsheet editor and validator for harmonizing, validating, and transforming genomics contextual data into submission-ready formats. As the excel spreadsheet became more complex and data processing became unwieldy, a GRDI-AMR/GOAH DataHarmonizer template was engineered to faciliated curation, validation, and automated transformations. The "Pathogen-Genomics-Package" is a version of the DataHarmonizer packaged with specification templates. The GRDI-AMR/GAOH Template is listed as **"GRDI"** within the DataHarmonizer template menu. Template schema files can be found as .yaml/.json/.tsv [here](https://github.com/cidgoh/DataHarmonizer/tree/master/web/templates/grdi). Instructions for "Getting Started" in the "[GRDI_DataHarmonizer-SOP.pdf](https://github.com/cidgoh/GRDI_AMR_One_Health/blob/main/SOPs)". Further information about application functionality can be found on the [DataHarmonizer Wiki](https://github.com/cidgoh/pathogen-genomics-package/wiki/DataHarmonizer-Getting-Started).
  - The template is currently implemented as a single tab/worksheet, but a multitabbed version is under active development (beta as of August 2025) to faciliate the "merged sheet"/one-to-many functionality within the DataHarmonizer.
 
### Field and Term Reference Guide
Reference guides providing field and picklist term descriptions, guidance, examples, and version information.

- [**XLSX version**](https://github.com/cidgoh/GRDI_AMR_One_Health/tree/main/Reference%20Guide)
- **PDF version**
  - [Field Reference Guide](https://github.com/cidgoh/GRDI_AMR_One_Health/blob/main/Reference%20Guide)
  - [Term Reference Guide](https://github.com/cidgoh/GRDI_AMR_One_Health/blob/main/Reference%20Guide)
- [**Online version**](https://docs.google.com/spreadsheets/d/1crc7yQtd8aj5LJYyeDMrNWqUO-o9ulKRkSqAub-51gg/edit?usp=sharing)

### GRDI-AMR/GAOH Specification Curation SOP
Guidance describing and explaining how to curate your data across the different sections of the specification.

- [**PDF version**](https://github.com/cidgoh/GRDI_AMR_One_Health/tree/main/SOPs)
- [**Online version**](https://docs.google.com/document/d/e/2PACX-1vTFrkZ5CaZTgoQLnAnIYPVOrDhl1xkYvCaMIcQ4BfcvH77N9vcy5zRnjyM6dvl4ZwYK2EwhDTc1Rvl1/pub)
- **Note:** Detailed worked examples, that may help users navigate different curation scenarios, can be found in the "[Design Manuscript](#manuscripts)" 

### GAOH Metadata and Sequence Standardization and Submission SOP
A webpage that outlines how to standardize sample, isolate, and sequence metadata as well as the process for submitting data to the central database (VMR), NCBI, and IRIDA.
- [**Online version**](https://github.com/grdi-amr/docs-and-SOPs/blob/main/metadata_standards_sop.md) 

### DataHarmonizer SOP
Guidance on how to download and use the DataHarmonizer version of the specification.
- [**PDF version**](https://github.com/cidgoh/GRDI_AMR_One_Health/blob/main/SOPs)
- [**Online version**](https://docs.google.com/document/d/e/2PACX-1vQgwhvNtRRw4lgLx807LF7VCtynshapoSPOUEvFcPNORmdUyJ1_KVm_rTDRwivW4Ppwy9s-rZfLqZmx/pub)

### New Term Request SOP
How to request new fields and/or terms to expand the specificantion so that it appropriately encompasses your data needs. Requests undergo working group discussion and data structure review, then experienced data curators integrate them into the specification and create/submit the terms in the appropriate ontologies.
- [**PDF version**](https://github.com/cidgoh/GRDI_AMR_One_Health/tree/main/SOPs)
- [**Online version**](https://docs.google.com/document/d/e/2PACX-1vQN0xPHYyr7Tgvu7RYHYGNY2QHh8Vb9XaoIw7we0VmaR5JsjV_OIdyn4wuGBz7dXPqFPT67mjJmjiUl/pub)

## Version Control
Please note that development of the specification is dynamic and it will be updated periodically to address user needs. Versioning is done in the format of `x.y.z`.

`x` = Field level changes <br>
`y` = Term value / ID level changes <br>
`z` = Definition, guidance, example, formatting, or other uncategorized changes <br>

Descriptions of updates are provided in [release notes](https://github.com/cidgoh/GRDI_AMR_One_Health/releases) for every new version.

Discussions contributing to updates may be tracked on the DataHarmonizer GitHub issue tracker.
