# SemanticsExtraction
The aim of the project is to extract from Natural Language relevant semantic informations. The input text is divided into triples (Subject - Relation - Object). WordNet here is used to get the meaning of relation and DBpedia is used to extract information from subject and object.

## Dependencies
* NLTK
* spaCy
* Stanza
* CoreNLP
* textacy
* SPARQLWrapper

## How to run
It necessary to create a shortcut of this directory in your Google Drive. The Google Colaboratory notebook to run is 'SemanticsExtraction.ipynb'. It is divided in four sections that must be performed sequentially. The four steps are the following:

1. Mount the drive
2. Setup and Requirements
3. Reading the input file
4. Triples extraction

