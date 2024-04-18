# Artificial-Intelligence-based-Chatbots-for-generating-Federated-SPARQL-queries
Exploring the potential of Artificial Intelligence based Chatbots for generating Federated SPARQL queries over Bioinformatics Knowledge Graphs

Abstract:
In this paper we investigates the efficacy of five AI bots - ChatGPT, Gemini, Copilot, Chatsonic, and YouChat - in formulating simple and complex federated SPARQL queries across Dbpedia, DrugBank, and KEGG databases. Through comparison with manually created queries, we unveil the bots' capabilities and limitations. Our findings highlight the potential of AI in data science and healthcare research, offering insights into cross-domain query generation and its implications for interdisciplinary collaboration.

Improved Queries:
P1 Query: Write a single SPARQL query to retrieve the complete list of drugs from the Drugbank database. Use the provided DrugBank SPARQL endpoint URL (http://drugbank.bio2rdf.org/sparql) to retrieve a list of all distinct registered drugs in the Drugbank biological database. Only provide the code.

P4 Query: Generate a single federated SPARQL query to retrieve all drugs from DrugBank biological database that affect “humans and mammals”. For each drug found, get its CAS registry number. Using the CAS number from DrugBank, find the same drug in KEGG biological database and obtain the mass information for each drug. Also, retrieve the drug label, description of their biotransformation from DrugBank, if they are available. Only provide the code.

P5 Query: Generate a single federated SPARQL query to retrieve distinct drugs and get information like drug description, molecular weight average, compound, reaction title, and chemical equation. Use the DrugBank and KEGG biological databases. From DrugBank, select drugs with the drug type "small molecule" and retrieve their descriptions and KEGG compound IDs. Then, from KEGG, obtain information about enzymes, chemical reactions, reaction titles and chemical equations associated with the selected compounds. Finally, include an optional clause to filter drugs with a molecular weight average greater than 114. Only provide the code. 
