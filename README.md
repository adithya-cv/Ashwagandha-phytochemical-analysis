# Phytochemical Screening of Ashwagandha (Withania somnifera)
## Drug-Likeness Analysis Using Lipinski's Rule of Five

## Background
Ashwagandha (Withania somnifera) is a medicinal plant widely used in Ayurvedic medicine.Its key bioactive compounds, withanolides, have been studied for their 
ability to reduce cortisol levels. This project uses computational methods to screen these compounds for drug-likeness. This work is inspired by a Bachelor's 
research project exploring the use of Ashwagandha's phytochemical constituents to detect cortisol in biological samples, now reimagined as a computational 
drug discovery pipeline.

## Project Phases
- ✅ Phase 1 — Drug-likeness screening of Withanolides (Completed)
- ✅ Phase 2 — Full phytochemical screening of Ashwagandha (Completed)
- 🔲 Phase 3 — Molecular docking against cortisol-related target protein
- 🔲 Phase 4 — Write up and publication

## Phase 1 — Results Summary
- 21 withanolide compounds analysed
- Lipinski's Rule of Five applied to assess drug-likeness
- 13 out of 21 compounds (62%) identified as drug-like
- Molecular Weight was the only failing criterion
- Withanolide A, B and D identified as top drug-like candidates

## Phase 2 — Results Summary
- 163 phytochemicals retrieved from Dr. Duke's Phytochemical Database
- 129 phytochemicals retrieved from IMPPAT (Indian Medicinal Plants, Phytochemistry and Therapeutics)
- Datasets cleaned, duplicates removed and merged into a master list of 190 unique phytochemicals
- Physicochemical data automated retrieved from PubChem using the PubChem REST API
- 83 out of 190 compounds successfully retrieved (remaining compounds not found due to naming variations or absence in PubChem)
- Lipinski's Rule of Five applied across all 83 compounds
- 36 out of 83 compounds (43%) identified as drug-like
- Key drug-like candidates identified: Withaferin A, Withanone, Withanolide A, B, D, E and F, Quercetin, Scopoletin and Withasomnine
- Compared to Phase 1 (62%), the broader phytochemical dataset showed lower overall drug-likeness (43%), reflecting the chemical diversity beyond withanolides
- Molecular Weight and XLogP were the primary failing criteria

## Tools and Libraries Used
- Python
- Pandas — data manipulation and analysis
- Matplotlib — data visualisation
- Seaborn — statistical visualisation
- Requests — automated data retrieval from PubChem REST API
- Data sources: PubChem, Dr. Duke's Phytochemical Database, IMPPAT

## Author
Adithya Chithralekha Velayudhan
MSc Biomedical Engineering
B.Tech Biotechnology and Biochemical Engineering
