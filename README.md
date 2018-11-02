---
layout: default
title: Readme
show: false
---
# SAP-CRM-Functional-Documentation
Documentation of Business Processes and Functional Modules in SAP CRM

We will use this repository to document the knowledge about business terms, processes, functionalities and interfaces. The technical implementation will be ignored/omitted.

Suggested documents (should all be .md type): 
* [Glossary](Glossary.md)  - short explanation of business terms
* [Admission](Admission/README.md) - key processes, responsibilities, data, functionalities and interfaces for trading and clearing
* Billing   - key methods, data and functionalities for billing, accounting, etc.
* etc.

Lessons learned will be collected continouosly in the [HowTo Guide](Howto.md).

The use of Github Markdown is described in this [guide](https://guides.github.com/features/mastering-markdown/). 

# How to Document
The folder structure has been setup similar to our UHD categorization.
GitHub pages option is activated and will generate webpages for each document.

### Do's and Don'ts
This document is supposed to collect the rules on how to extend this Github documentation, based on our experiences.
Let's try to squeeze everything into do or don't rules. And feel free to experiment and change rules that have not really helped.

## Folders and Files
* in each folder add a README.md-file for overview / introduction
* if pictures are required (-> whenever possible!!), add an images-folder and upload pictures there
* if a document becomes too large (e.g. 3-4 pages), split it and move it to a subfolder
* don't use spaces in document names, use "-" or "_" instead
* link all *.md-documents in the folder in the README.md-file and give some context

## Links and Tags
* create relative links by copying the path/filename from the linked document (e.g. "Admission/README.md")
* use tags without special characters, e.g. `tags: contract` (a useful list of tags, maybe based on SAP solution map, will be developed over time)
* place a tagging section at the end of your document, so it can be found

## Glossary
* add a link to the glossary for terms that need explanation (and an entry to the glossary, of course!). E.G. [NCM](Glossary.md#ncm)
* add new entries in the correct first-level category, in alphabetical order
* add a (useful!) name-tag to new entries, so it can be linked directly. E.G.`<a name="ncm"></a>`
* before splitting the glossary, e.g. because it grew too big, discuss in the contributors group, as lots of links need migration


