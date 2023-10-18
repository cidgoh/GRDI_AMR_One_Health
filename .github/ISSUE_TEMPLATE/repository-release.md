---
name: Repository Release
about: An issue template that outlines the steps needed to perform a repository release
title: "#.#.# - repository release"
labels: ''
assignees: ''

---

### Versioning
* **x** = changes to fields
* **y** = changes to values/ontology IDs
* **z** = changes definitions/formats/examples

_Incrementing up one point for any number of changes._

## Repository Release
- [ ] Upload updated **"Excel Template"**.
  - [ ] Versioning `x.y.z`
- [ ] Upload updated **"[Reference Guides](https://docs.google.com/spreadsheets/d/1crc7yQtd8aj5LJYyeDMrNWqUO-o9ulKRkSqAub-51gg/edit?usp=sharing)"** (TSV & PDF).
  - [ ] Update the `Version Tracking` tab
  - [ ] Make sure "text wrap" is on before export so all contents are legible in the PDF
  - [ ] Do not include "Editor Note" column
  - [ ] Clean up formatting (if applicable)
  - [ ] Versioning `x.y.z` (same as template)
- [ ] Upload updated **"[Metadata Curation SOP](https://docs.google.com/document/d/1AE53-gF2K-6Zd8SimvHrQN-wEXBeNrDqa_fK54-Dpvs/edit?usp=sharing)"** & **"[DataHarmonizer Curation SOP](https://docs.google.com/document/d/1rF73SMpXa9pFRueYI8t-hV6g-0X9e0IWnS_amrcDz3c/edit?usp=sharing)"**.
  - [ ] Versioning `x.y` (same as template, minus "z" changes since those don't come up in the protocol")
- [ ] Upload updated **"[New Term Request SOP](https://docs.google.com/document/d/11pQAMk1nMJBuHNEif0d8s64LarfEvqtSBEWG3ZImv84/edit?usp=sharing)"**.
  - [ ] Versioning `x.y` (independent versioning since changes to the specification/template doesn't impact this protocol)
- [ ] **Draft a new release** ([Example](https://github.com/cidgoh/GRDI_AMR_One_Health/releases/tag/v7.7.5)):
  - [ ] Release title: `GRDI-AMR specification package #.#.#`
  - [ ] Choose a tag: `v#.#.#` (create a new tag)
  - [ ] Include **"Contents:"** section that lists the files and their individual version information
     > Data Collection Template #.#.# <br> Field and Term Reference Guides #.#.# <br> Curation Standard Operating Procedure (SOP) #.#.# <br> DataHarmonizer Download and Operation Instructions (SOP) #.# <br> New Term Request Standard Operating Procedure (SOP) #.#
  - [ ] Include **"Updates:"** section with important information like "fixes", new fields, and a table of fields and their associated changes (e.g., picklist updates, ID/label changes, etc.).
  - [ ] Include `Release Notes` - referencing applicable GitHub `#issue` release notes
     > _More details can be found under release notes issue #_ <br>
  - [ ] Set as the latest release
  - [ ] Publish release
  - [ ] Notify curation team on the CIDGOH SLACK #grdi channel
