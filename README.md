
## 📄 Associated Paper
"LIS at SimpleText 2025: Enhancing Scientific Text Accessibility with LLMs and Retrieval-Augmented Generation"

This paper presents a scientific text simplification system that leverages MedSimplify, a biomedical glossary also introduced in the paper. It was submitted to SimpleText https://simpletext-project.com/2025/, a track that is part of the CLEF 2025 https://clef2025.clef-initiative.eu/ conference.


## 📦 Dataset Description
The MedSimplify corpus is provided as a CSV file containing two columns:

word: The biomedical term
definition: A plain-English explanation of the term

## 🔍 Examples
BMI : a measure of body fat based on height and weight  
ECG : a recording of the heartbeat that helps doctors check if the heart is beating properly. It is made by placing electrodes on the chest, arms, and legs, and connecting them to a machine that records the heartbeat. Getting an ECG doesn’t hurt.
 
## 🛢️ Data Sources
MedSimplify was constructed by aggregating and unifying content from multiple publicly available medical glossaries created by researchers and experts in the medical field. These include:

- Glossary of Lay Terminology for Consent Forms
https://feinstein.northwell.edu/sites/northwell.edu/files/2019-07/Glossary-of-Lay-Terminology-for-Consent-Forms-07-19.pdf

- Plain Language Thesaurus for Health Communications
https://stacks.cdc.gov/view/cdc/11500

- CLAD-Thesaurus
https://clad.tccld.org/wp-content/uploads/2014/12/CLAD-Thesaurus.pdf

- Plain English Health Dictionary
https://nt.gov.au/__data/assets/pdf_file/0006/1257567/aid-plain-english-health-dictionary-spread.pdf

- Glossary (in Lay Terms)
https://rcm1.rcm.upr.edu/institutionalreview/wp-content/uploads/sites/16/2020/04/layterms.pdf

These glossaries were merged and curated to create a unified resource that supports scientific text simplification by providing plain-language definitions of biomedical terms.

