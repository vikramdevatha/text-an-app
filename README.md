Text Analytics - Group Assignment 2: Building a Shiny App around the Adjective
Aakash Bawa (11910031), Sahil Khurana (11910048) & Vikram Devatha (11910049)
date: 2-June-2018

This is an app for analysing CVs of new candidates, in order to quickly assess the fit with the company. A CV can be thought of as a compilation of: 

NOUNS i.e. domains the person has worked in <br>
VERBS i.e. the roles and responsibilities the person has been invovlved with <br>
PROPER NOUNS i.e. the companies, organizations and places mentioned in the CV <br>
ADJECTIVES and ADVERBS i.e. the kind and nature of work the person has experience with <br>

This app lemmatizes the words in the CV to its root form, and then visualizes the important parts of speech (nouns, verbs, adjectives, adverbs, and proper nouns) as word clouds and cooccurrence graphs. It also calculates a sentiment score based on the NRC and AFINN lexicon to provide a quick snapshot of the person - is he/she confident and trustworthy, or fearful and desperate? A sentiment analysis may throw some light on the nature of the person.

To run this app, you will need a local installation of R, which can be downloaded from https://www.r-project.org/

After installation, run the following commands in R: <br>
source('https://raw.githubusercontent.com/vikramdevatha/CV-Analyser/master/dependencies.R') <br>
runGitHub('CV-Analyser', 'vikramdevatha')
