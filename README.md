# Definition
This is an experiment of letting the semantic relations flagged in Turki et al. (2024) verified by TypeSafe's Jev, a “System One” AI model launched on 15 September 2026 that returns typed, structured decisions (choices, scores, yes/no probabilities) instead of generating text.

# Files
- **Low PMI.xlsx**: The Jev-based evaluation of the MeSH-based Associations in Wikidata having a Pointwise Mutual Information value of less than 2.
- **Not Available in PubMed.xlsx**: The Jev-based evaluation of the MeSH-based Associations in Wikidata not found in PubMed.
- **Code.ipynb**: The source code of the Jev-based evaluation of Wikidata relations.
- **Wikidata_PMI_Jev_Analysis.ipynb**: The Claude Sonnet 5.5-generated statistical analysis for the Jev-based evaluation of Wikidata relations.
- **Research_Paper.pdf**: The Claude Sonnet 5.5-generated research paper for the Jev-based evaluation of Wikidata relations.

# Call for Contributors
Wikimedia contributors are invited to assess the semantic relations in **Low PMI.xlsx** and **Not Available in PubMed.xlsx** that are flagged by Jev as "false" and "maybe" and remove them from Wikidata if not accurate.

# To Cite
Turki, H. (2026). *csisc/MeSH2WikidataDelete: How well does a Pointwise Mutual Information threshold identify questionable Wikidata Biomedical Relations*. Zenodo.
