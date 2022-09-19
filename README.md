# __Named Entity Recognition__
## on Astrophysics Papers

**Named Entity Recognition** is an information extraction technique used to locate and classify named entities in unstructured text into predefined categories such as names, organizations, locations, numerical values , date etc.

Here NER is done to find and tag astronomical entities such as Celestial bodies, Event, Formula and other in astrophysics papers.

A problem by [**Workshop on Information Extraction from Scientific Publications**](https://ui.adsabs.harvard.edu/WIESP/)

## Contributors:
  * Preetpal Singh<br>
  * Devansh Shrestha<br>
  * Rampuneet Kumar<br>
  * Prateek K<br>

## Data Set
Name: WIESP2022-NER<br>
Link: [Dataset on Hugging face](https://huggingface.co/datasets/fgrezes/WIESP2022-NER)

### Description:
Dataset contains separate json files for Training and Validation . Made available by NASA Astrophysical Data System. with manually tagged astronomical facilities and other entities of interest.
Contains:
* "unique_id": a unique identifier for this data sample.
* "tokens": the list of tokens (strings) that form the text of this sample.
* "ner_tags": the list of NER tags

## Model Used

* Vanilla LSTM
* Word2vec embeddings
* Bidirectional LSTM model with word2vec embeddings
* Transformers with word2vec embeddings
