# Spotify FAIR Data Repository

This repository contains FAIRified data and metadata for a curated collection of Spotify tracks, formatted and structured to align with the FAIR (Findable, Accessible, Interoperable, and Reusable) principles. The data includes cleaned and reconciled versions, as well as RDF and ontology files to enable semantic interoperability.

## Repository Structure

### `data/`
- **spotify_data_cleaned.csv**: The cleaned version of the Spotify dataset, which includes key attributes like track title, artist, album, release date, and other metadata.
- **spotify_data_reconciled.csv**: The reconciled version of the Spotify dataset, with additional links and identifiers to ensure compatibility with Linked Data standards and external datasets.

### `rdf/`
- **spotify_rdf_schema.ttl**: The RDF schema in Turtle format. This file represents the semantic data model, defining relationships between entities like Track, Album, and Artist according to the ontology.

### `ontology/`
- **spotify_ontology.owl**: The ontology created using Protégé, which formalizes the classes, properties, and relationships for Spotify data. This ontology is essential for understanding the data structure and for linking to other semantic web resources.

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

