# NAMED ENTITY RECOGNITION

The overwhelming amount of unstructured text data available today from traditional media sources as well as newer ones, like social media, provides a rich source of information if the data can be structured. Named Entity Extraction forms a core subtask to build knowledge from semi-structured and unstructured text sources. Some of the first researchers working to extract information from unstructured texts recognized the importance of “units of information” like names (such as a person, organization, and location names) and numeric expressions (such as time, date, money, and percent expressions). They coined the term “Named Entity” in 1996 to represent these. Named Enity Recognition is one of the most common NLP problems.

## ENTITY EXTRACTION

The three common methods to approach entity extraction (and recognition)
Statistical models — entities that you cannot exhaustively list or which have too much overlap with non-entities, statistical modeling (a.k.a., machine learning) is best as it is context sensitive. Traditional ML and more recent approaches like CNN/RNN are used in this.
Entity lists — Used when the list of entities is known and finite (e.g., a list of professional tennis players from 2013–2014).
Regular expressions — Use regular expressions when the entity can be defined by a pattern. For example, credit card numbers are 16 digits beginning with a 4 (Visa), 5 (Mastercard), 6 (Discover), or 15 numbers beginning with a 34 or 37 (American Express). Regular expressions can reliably find these entities.

This is a guided project.
 The project comprises of 8 tasks. Namely,
 1. Importing libraries
 2. Load and explore ner dataset.
 3. Retrieve sentences and corresponding tags.
 4. Define mapping between sentences and tags.
 5. Padding input sentences and creating train/test splits
 6. Build and compile Bidirectional LSTM Model.
 7. Train the model
 8. Evaluate the named entity recogition.
 
 
