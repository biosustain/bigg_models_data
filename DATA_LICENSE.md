# Data licensing

The code in this repository is released under the Apache License 2.0 (see
`LICENSE` and `NOTICE`). The data files are licensed according to their origin:

| Content | License |
|---|---|
| Models in `original_models/` inherited from BiGG Models (e.g. `iML1515.xml`, `iAF1260.xml`, `RECON1.xml`, `Recon3D.mat`), and reference definitions inherited from BiGG Models | BiGG Models license of The Regents of the University of California: educational, research and non-profit use; commercial use requires a separate agreement |
| `original_models/GCF_*.xml` (the `iPKB_Clostridiaceae` collection, see `model-genome-clostr.json`) and other models and data generated at BRIGHT | [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/), see `LICENSE-CC-BY-4.0` |
| Model files that state their own license (e.g. `original_models/yeast_7.00.xml`) | The license stated in the file |

Mapping and configuration files that combine inherited and BRIGHT-generated
content (e.g. `bigg_id_data.json`, `reaction_data.json`) follow the same rule
for their respective parts.

The license applying to each BiGG 2026 collection is listed on
[bigg.bio](https://bigg.bio/about#about_license) (About BiGG).

External cross-references (e.g. KEGG, MetaCyc, DrugBank, HMDB) are provided as
identifiers and links; the linked content remains subject to the terms of each
source.
