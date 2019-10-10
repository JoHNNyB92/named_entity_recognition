# named_entity_recognition

This question concerns the Named Entity Recognition. We will be using the Groningen Meaning Bank
dataset. GMB is composed of a lot of files, but we only care about the .tags files.
A file contains more sentences, which are separated by 2 newline characters. For every sentence, every
word is separated by 1 newline character. For every word, each annotation is separated by a tab character.

The target is to perform named entity recognition, to extract the named entities from the dataset and use the
annotated data to learn a supervised classifier (using the IOB representation) for named-entity
recognition and classification. We train the model using the Naïve Bayes classifier.
