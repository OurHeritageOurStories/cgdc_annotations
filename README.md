## Overview
This repository contains historical and cultural narratives text annotated with Named Entities (NE) and Entity Linking (EL). The dataset consists of 100 annotation (.ann) files generated using the [Brat annotation tool](https://github.com/nlplab/brat). These annotations were applied to 100 items, with an equal distribution of 50 items collected from [Morrab Library](https://morrablibrary.org.uk/) and [The People's Collection of Wales (PCW)](https://www.peoplescollection.wales/).

## Usage
Researchers and practitioners can utilise this dataset for further testing and evaluation of Entity Linking models on historical and cultural narratives. It provides a curated set of annotations that can serve as a benchmark for assessing EL model performance.

## Dataset Description
- **Text construction**: The original text was generated by combining the English titles and descriptions of each item, using a carriage return between them.
- **Annotations**: Each annotation file corresponds to an item and starts with either the collection name ("morrab" or "pcw") followed by an underscore and the item ID.
- **Original Items**: The original items can be retrieved by combining the following URLs to the item ID
  - For Morrab Library items: https://photoarchive.morrablibrary.org.uk/items/show/ + Item ID
  - For The People's Collection of Wales (PCW) items: https://www.peoplescollection.wales/items/ + Item ID

## Citation
If you use this dataset in your research or work, please cite the accompanying paper:
[ The paper name is "Enriching the Metadata of Community-Generated Digital Content through Entity Linking: An Evaluative Comparison of State-of-the-Art Models"
Full citation will be provided soon when the proceeding is published]

