## Overview
This repo contains named entity (NE) and entity linking (EL) annotations of the textual metadata of items drawn from collections of community-generated digital content (CGDC). The dataset consists of annotation files (in .ann format) produced by the [Brat annotation tool](https://brat.nlplab.org). The annotation files correspond to 100 CGDC items, 50 of which were collected from the [Morrab Library](https://morrablibrary.org.uk/) and the other 50 from [The People's Collection Wales (PCW)](https://www.peoplescollection.wales/).

## Usage
Researchers and practitioners can utilise this dataset in testing and evaluating Entity Linking models on CGDC metadata. It provides a set of annotations that can serve as a benchmark for assessing EL model performance. As we are still in the process of seeking permission to directly share and distribute the raw textual metadata that was anntotated, for now we can provide only the annotations. Interested users of the dataset will thus have to reconstruct the text themselves, following the instructions below.

## Dataset Description
- **Annotations**: Each annotation file corresponds to a CGDC item and has a filename that starts with the collection name abbreviation ("morrab" or "pcw") followed by an underscore and the item ID within the collection. For example, the annotation file `morrab_10286.ann` contains the annotations for the item with ID `10286` in the Morrab Library. 
- **Text reconstruction**: The original text for each item can be reconstructed by creating a plain text file whose filename should bear a similar prefix as the corresponding annotation file, but with ".txt" as file extension. For instance, to create the corresponding plain text file for `morrab_10286.ann`, one has to create a file called `morrab_10286.txt`. The content of the text file should be a concatenation of the title and description of each item, with a newline in between them. The titles and descriptions of items can be retrieved by accessing the following URLs, where `item_ID` should be replaced with the item ID of interest:
  - for Morrab Library items: `https://photoarchive.morrablibrary.org.uk/items/show/<item_ID>`
  - for PCW items: `https://www.peoplescollection.wales/items/<item_ID>`

## Citation
If you use this dataset in your research or work, please cite the following paper:
"Enriching the Metadata of Community-Generated Digital Content through Entity Linking: An Evaluative Comparison of State-of-the-Art Models"
(full citation details will be provided once when the EACL 2024 proceedings are published).

