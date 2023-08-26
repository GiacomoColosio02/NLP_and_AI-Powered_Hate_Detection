### NLP_and_AI-Powered_Hate_Detection
This is the notebook for the NLP project of Colosio Giacomo. The project is a text classification task on the dataset 'https://github.com/t-davidson/hate-speech-and-offensive-language'. This is a collection of offensive and hate tweets, which were all manually labeled by CrowdFlower users, which voted them as:

- hate speech (0);
- offensive language (1);
- neither (2).

In fact, togheter with the tweets and the class there are also columns for the singular categories voting.

As this is the code part, the notebook comments will be more code-oriented, in such a way to technically explain the steps.

The dataset wasn't 'heavy', this choice was oriented to our curiosity in trying out different kinds of embeddings to predict the nature of the tweets. The code is divided in three main blocks, for classification with three different embeddings:

### tf-idf;
### CboW (implemented from scratch);
### ElMo (imported from Tensorflow Hub).

All the information are contained in the YPNB project
