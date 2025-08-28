# GRDI-AMR / GAOH Data Collection Template
GRDI-AMR / GAOH = _Genomics Research and Development Initiative Shared Priority Projects for Antimicrobial Resistance (GRDI-AMR and GRDI-AMR-One Health (GAOH; aka GRDI-AMR2))_

**The contents of this directory include the spreadsheet-based implementation (i.e. metadata template) of the AMR-GRDI standard.**

## Files

- `GRDI_Harmonization-Template_v#.#.xlsm` 
Microsoft Excel Macro-Enabled Workbook file, opening in other applications risks the loss of validation, multiselect, and merge sheet functionality.

## Template Contents

- The "**Reference Guide**" tab contains field-level reference guide information.
- The "**Vocabulary**" tab contains picklist vocabularies.

Check the [curation standard-operating-procedure](https://github.com/cidgoh/GRDI_AMR_One_Health/tree/main/SOPs) for more information on using the following dataset worksheet tabs:

- The "**Reference Guide**" tab contains the following field information: whether it is required/recommended/optional, the label, ontology ID, definition, guidance, and examples.
- The "**Merged Sheet**" tab contains information for a sample/isolate across all applicable tabs.
- The "**Sample Collection and Processing Information**" tab is where you enter information about the original sample.
- "**Environmental conditions and measurements**" tab is where you enter information relating to environmental conditions at the time the original sample was collected.
- The "**Host Information**" tab is where you enter information about the host.
- The "**Strain and Isolate Information**" tab is where you enter information about the original strain or isolate.
- The "**Sequence Information**" tab is where you enter information about the sequence.
- The "**Public Repository Information**" tab is where you enter information about the sequence submitted to a public repository.
- The "**Risk Assessment**" tab is where you enter informations about samples and isolates to enhance risk assessment.
- The "**AMR Phenotypic Test Information**" tab is where you enter information about antimicrobial resistance (AMR) testing results.
- The "**Vocabulary**" tab contains the picklist vocabulary used across the various tabs.

## Macro Information

The Microsoft Excel Macro-Enabled Workbook file `.xlsm` format stores Visual Basic for Application (VBA) code in workbooks. The reason you get system warnings on whether it's safe to open a file is because people can use this feature to harm your computer. We have not done so in this case, and have posted all VBA code on https://github.com/cidgoh/GRDI_AMR_One_Health/wiki/Template-Macros so you may more easily observe the macros for yourself in case you are concerned.

### Troubleshooting - Enable Macros

#### Within the Worksheet

By default, when you first open a macro-enabled workbook you’ll see a yellow “SECURITY WARNING” bar appear just underneath the ribbon.  Clicking the “Enable Content” button will enable macros. (source: https://www.automateexcel.com/macros/enable-macros/)

#### File Explorer (Windows)

Find the file on your computer, right-click and select "Properties". Navigate to "Security: This file came from another computer and might be blocked to help protect this computer." and select "Unblock".

#### Add a Trusted Location

If you consistently save the template is a specific folder, or access via a GitHub repository clone, you can follow the "Add a new Trusted Location" on this page: https://www.automateexcel.com/macros/enable-macros/

