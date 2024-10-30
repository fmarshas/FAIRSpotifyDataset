# Spotify FAIR Data Repository

This repository contains FAIRified data and metadata for a curated collection of Spotify tracks, formatted and structured to align with the FAIR (Findable, Accessible, Interoperable, and Reusable) principles. The data includes cleaned and reconciled versions, as well as RDF and ontology files to enable semantic interoperability.

## Repository Structure

### `data/`
- **spotify_data_cleaned_3724.csv**: The cleaned version of the Spotify dataset, which includes key attributes like track title, artist, album, release date, and other metadata. This version contains 3,724 records after data cleaning.
- **spotify_data_reconciled_117.csv**: A sample subset of the Spotify dataset (117 rows) that has been reconciled with external identifiers for linking and interoperability.
- **spotify_data_reconciled_117.xls**: Excel version of the reconciled dataset for easy access and manipulation in spreadsheet software.

### `rdf/`
- **spotify_rdf_schema.ttl**: The RDF schema in Turtle format, representing the semantic data model and defining relationships between entities such as Track, Album, and Artist.
- **spotify_rdf_schema.rdf**: An RDF/XML format of the schema, providing an alternative serialization for RDF applications.

### `ontology/`
- **Spotify_Ontology_ttl.ttl**: The ontology created using Protégé, formalizing the classes, properties, and relationships for Spotify data in Turtle format.
- **spotify_ontology_owl.owx**: The OWL format of the ontology for use in Protégé or other ontology management tools.
 
## Data Source

The original dataset was obtained from Kaggle and contains information on the **most-streamed Spotify songs of 2024**. You can find the source dataset at [Most Streamed Spotify Songs 2024 on Kaggle](https://www.kaggle.com/datasets/nelgiriyewithana/most-streamed-spotify-songs-2024). This dataset was further processed to ensure compliance with FAIR principles, including cleaning, reconciliation, and transformation into RDF format.


## Usage

This repository provides the following resources:
1. **CSV Data**: The cleaned and reconciled datasets offer a structured view of Spotify tracks, with essential attributes and identifiers for cross-referencing.
2. **RDF Schema**: Use the RDF schema file to view the dataset as Linked Data, facilitating integration with other semantic resources.
3. **Ontology**: The ontology file formalizes the data structure and enables compatibility with semantic tools.

### How to Access

- Download each file directly from the repository by clicking on the filename.
- You can use the CSV files for data analysis in Python, R, or any data-processing software.
- Load the RDF schema and ontology files into a triple store or ontology editor to explore relationships and linked data capabilities.

## Licensing

This data and metadata are available under the [CC0 1.0 Universal (CC0 1.0) Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/), enabling open use, sharing, and adaptation.

