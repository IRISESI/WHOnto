# WHOnto
This repository contains the details (prompts and results) of  the experiments conducted for the construction of an ontology using ChatGPT-3.5. The paper is entitled : "" published in "".  

Technical details: 
1. We used ChatGPT-3.5, which is publicly available at https://chatgpt.com/. The experiments were performed in March-April 2024. At that time, GPT-3.5 was the default model, and GPT-4o had not yet been made available.
2. We used Protégé-5.5.0 to verify the generated ontologies and to test the SPARQL queries.

Organization of the repository:

1. Folder FullOntologyAndSPARQL : This folder contains the ontology (TBox and ABox) for testing the SPARQL queries. The ontology is derived from opening the TBoxPrompt2Corrected in Protégé and then importing the ABoxPrompt2 into the active ontology. We provide this file to allow the reader to perform testing without having to carry out these operations personally. The files Prompts, SPARQLQPrompt1, and SPARQLPrompt2 detail the prompts used and the resulting SPARQL queries per prompt, respectively.
2. Folder GeneratedTBox: 
