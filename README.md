Detection of duplicate questions from a corpus containing a pair of questions deals with identifying whether two questions in the pair convey the same meaning or not. Quora is a growing platform comprising a user generated collection of questions and answers. The questions and answers are created, edited, and organized by the users. Enormous number of users on the Quora website makes it unavoidable to have multiple questions from different users with similar intent, which raises the issue of duplicate questions. Effectively detecting duplicate questions would make it easier to find high quality answers and help save time, which in turn would result in an improved user experience for writers and readers on Quora. In this paper, Quora Question Pairs dataset is collected from Kaggle for detection of duplicate questions. To detect duplicate question pairs, we have implemented several methods and algorithms. The implemented methods are the Siamese Manhattan LSTM model with different types of embedding (Keras embedding, Google News Vector embedding, FastText Common Crawl embedding, and GloVe Common Crawl embedding), the BERT Bi-LSTM model, the Siamese BERT model, and the RoBERTa Bi-LSTM model. Our best performer model is the RoBERTa Bi-LSTM model. We achieved up to 91.20% accuracy to detect duplicate question pairs.
