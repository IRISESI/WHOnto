# WHOnto
This repository contains the details (prompts and results) of  the experiments conducted for the construction of an ontology using ChatGPT-3.5. These experiments are part of the paper entitled "" submitted for publication in "".  

Technical details: 
1. We used ChatGPT-3.5, which is publicly available at https://chatgpt.com/. The experiments were performed in March-April 2024. At that time, GPT-3.5 was the default model, and GPT-4o had not yet been made available (see https://help.openai.com/en/articles/6825453-chatgpt-release-notes for more information).
2. We used Protégé-5.5.0 to verify the generated ontologies and to test the SPARQL queries.

Organization of the repository:

1. Folder FullOntologyAndSPARQL : it contains the ontology (TBox and ABox) for testing the SPARQL queries. The ontology is derived from 
   opening the TBoxPrompt2Corrected in Protégé and then importing the ABoxPrompt2 into the active ontology. We provide this file to allow 
   the reader to perform testing without having to carry out these operations personally. The files Prompts, SPARQLQPrompt1, and 
   SPARQLPrompt2 detail the prompts used and the resulting SPARQL queries per prompt, respectively.
2. Folder GeneratedTBox: it contains the generated TBox for each tested prompt (1&2). TBoxPrompt2Corrected is an edited version of 
    TBoxPrompt2 containing some corrections that we performed manually in Protégé.
3. Forlder GeneratedABox: it contains the generated Abox for each tested prompt.
4. Folder GeneratedCQsAndEval: the Competency Questions (CQs) generated per prompt are regrouped in the file PromptsAndResults. The evaluation of each prompt's results is detailed in a CSV file.
