# 🌱 ASR Wav2Vec2 model performance evaluation

The aim of this study is to investigate the performance of the wav2vec model trained on five mutually exclusive subsets of the GigaSpeech dataset (a multi-domain English speech recognition corpus), each of which contains samples belonging to a specific category. Our goal is to train the model separately on each subset and evaluate its performance using a confusion matrix to derive conclusions about the generalization of the dataset to specific categories. The metric we plan to use is (w.e.r) word error rate. The wav2vec model has not previously been exposed to this dataset, and we seek to determine how it performs on these subsets. We describe the methodology used to create the subsets and preprocessed the data for training the model. We then evaluate the performance of the model on each subset separately and discuss the correlation between these categories. Our expectation is that the results will show that training the wav2vec model on these subsets separately can lead to improved performance and better generalization to the specific categories. Additionally, the confusion matrix analysis can provide insights into correlations between the different categories and if a combination of such data can improve the generalization of the model.
