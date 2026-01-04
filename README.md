# MetalingProject

## Overview

The MetaLing Corpus is a curated corpus of metadata describing a selection of Early Modern English texts. The corpus is designed to support linguistic, philological, and historical research by providing structured, interoperable metadata rather than full textual transcriptions.

This repository is part of the MetaLing Corpus Project, which focuses on the collection, standardization, and analysis of linguistic metadata across historical corpora.

## Aims and Scope

The use of the MetaLing Corpus will be multifold. This tool will help raise awareness of the significance of linguistics and philology in multilingual Europe, highlighting the importance of these studies for understanding a long tradition of contact, exchange, and even conflict between linguistic and cultural identities across Europe. It is intended as both a scholarly and didactic resource, and the terminology extracted from it will provide valuable data for open source dictionaries and lexical repertoires. This work is timely and relevant as a contribution to the ongoing debate on the development of the discourse of the humanities as an inherently interdisciplinary field.
The corpus covers texts produced roughly between the late 15th and early 18th centuries. Texts may vary by genre, medium, authorship, and sociolinguistic context.

## Corpus Content
The corpus contains metadata records only. It does not include the full text of the documents.

Each record corresponds to a single text (or textual unit) and includes descriptive, bibliographic, and linguistic information such as:

Title of the text
Author (where known)
Date or date range of composition/publication
Genre 
Text type
Place of publication or production
Language variety and periodization
Source edition or repository
Editorial or annotation notes


The corpus is distributed as CSV files exported from Omeka.net.

The original Omeka structure is organized hierarchically as follows:

### MetaLing Corpus (top-level collection)
  #### Subcorpus A
    Items
  #### Subcorpus B
    Items
  #### Subcorpus C
    Items

Each CSV row represents a single item. The columns correspond to the Omeka metadata Dublin Core fields. 
This layout preserves the hierarchical collection structure conceptually, and fields such as collection_id allow users to reconstruct the subcorpus membership.

## Data Sources
Metadata have been compiled from a range of scholarly and digital resources, with specific roles assigned to each source:

- Alston Collection: primary reference for identifying and contextualizing works related to metalinguistic commentary and metalanguage in the Early Modern English period.

- Oxford Text Archive (OTA): consulted for information regarding textual provenance, cataloguing standards, and rights management.

- Early English Books Online (EEBO): used as the main source for the digital instantiation of the texts and for bibliographic cross-checking.


## Data Quality and Limitations
While care has been taken to ensure accuracy and consistency, the corpus reflects the limitations of available historical and bibliographic information. Dates, authorship, and genre classifications may be uncertain or disputed in some cases.

Users are encouraged to consult the original sources when precision is crucial.

## Licensing
Unless otherwise stated, the metadata in this corpus are released under an open license suitable for academic research and reuse. Please check the LICENSE file for detailed terms.

## Project Information
Project name: MetaLing Corpus Project
Focus: Linguistic metadata and historical corpora
https://metaling.unimi.it/
