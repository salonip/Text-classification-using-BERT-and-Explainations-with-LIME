# Text-classification-using-BERT-and-Explainations-with-LIME

Here is the dataset obtained from kaggle https://www.kaggle.com/aviskumar/automatic-ticket-assignment-using-nlp? 
- The dataset groups various common IT issues into various 74 classes.I have used this data particularly because of its high imbalance hence close association with real time data.
- The dataset also contains a lot of real world like issues that needs to be taken care of before using models.
-  Using BERT transformers for embedding creation from a pretrained model. 
- Model is convolution neural network with multiple parallel layers resembling ngram systems. Because BERT already takes care of word associations using masks, a simple architecture can also be explored.
-  The first cut model performs decently, given the imbalance in class.
- LIME model is explored to explain the model outputs. While LIME can be used to explain predictions to business stakeholders, I found it useful to modify training and other preprocessing work too. you can refer to LIME here https://github.com/marcotcr/lime . CAn be installed from here https://pypi.org/project/lime/
