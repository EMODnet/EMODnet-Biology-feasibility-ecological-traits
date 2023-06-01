# Text mining in ecological traits

The report of this work is available [here](https://emodnet.ec.europa.eu/en/reports?field_emodnet_lot_value[]=biology) and for download [here](https://emodnet.ec.europa.eu/sites/emodnet.ec.europa.eu/files/public/Biology/D4.4.-EMODnet_MBON-Europe.pdf)

## Intro

Traits refer to the characteristics of a species, including its morphology, anatomy, physiology, biochemistry, and phenology. Scientists use traits to describe the characteristics of the taxa they study, and they are closely related to Essential Biodiversity Variables (EBVs) and ecosystem function. However, the meaning of traits is often inconsistent in literature due to their vast diversity and long history. To address this issue, trait databases have been created for many taxonomic groups, and standard vocabularies have been established to standardise trait terms. The Open Traits network has also been launched to promote open science standards and practices in the
field.

## Steps

During the development and training of the text mining models, the following steps were followed (Figure 1):
1. Vocabulary Establishment 2. Corpus Establishment
3. Tools Selection
4. Corpus Annotation
5. Data format preparation
6. Model Selection
7. Model Training for NER (Named Entity Recognition) 8. Model Evaluation

## Environment 

In order to train the models, a programming environment called Google Colaboratory is used for notebook production, edit and run processes. Google Colaboratory, known as "Colab", is a data analysis and machine learning application that enables the integration of rich text, charts, photos, executable Python code, and more into a single document stored in Google Drive. It was selected due to its ability to handle notebooks and attach a google drive folder. Such ability gives the convenience of having a folder in a drive account and just connecting it with the notebook in Google Colab, set the path and run the cells without need for example of uploading the different input files.

## Summary

The proposed methodology for developing an accurate text mining model involves several steps. This feasibility study concludes that the most suitable models are SpaCy and BioBERT. To further enhance the accuracy of these tools, an enriched workflow is recommended consisting of the following four steps: a. Corpus Enrichment and Text Annotation, b. Combining GNfinder with an NLP library, c. Management of the text mining process and d. Visualisation of results.

## Training session

Α training session was organised on the 20th of March 2023, in the framework of EMODnet Biology, specifically focusing on the ongoing Feasibility Study on Ecological Traits and sampling devices/methodologies identification with text mining. This training session focused on the interdisciplinary field of text mining and its application on marine ecological traits. During the session, which was advertised through the EMODnet portal Training session in the framework of the EMODnet Biology Phase IV on the feasibility study for recognition of
specific ecological traits and sampling devices/methodologies in text | European Marine Observation and Data
Network (EMODnet) (europa.eu); social media as well as the github of the Open Traits Network https://github.com/open-traits-network/open-traits-network.github.io/issues/253; participants received an overview of state of the art text mining technologies and bioinformatic tools.
The session began with training participants on literature curation workflows, standards, and resources. Participants prepared their own literature and followed the workflow to extract information on traits and species names. Using machine learning algorithms and tools, they evaluated the results and provided feedback on the user interface, usability, and feature requests. Thus, the participants had a unique opportunity to work on the complete workflow from literature preparation to data analysis. Programming was a key part of the session, during which an introduction on how to process data from raw text to the application of algorithms for text mining took place.

The agenda of the training session is available via the [link](https://mda.vliz.be/directlink.php?fid=VLIZ_00000708_642fb541462d3265669157), along with the presentations via the [link](https://mda.vliz.be/directlink.php?fid=VLIZ_00000708_642fb541460b0633179501) and the recorded file via the [link](https://mda.vliz.be/directlink.php?fid=VLIZ_00000708_642fb54146248723971708).

In the folder EMODnet_training are the examples of the multiple models demonstration for the training session. This material is also available in this [google folder](https://drive.google.com/drive/u/0/folders/1Jh4FKNwip249yQa5qJSmGLTYisHA1iIh).
