## Question Answering System

The dataset that this QA system is built upon is similar to TriviaQA. Our system uses a combination of information retrieval and deep learning.

For information retrieval part, we use a double TF-IDF strategy to select sentences to form a paragraph.

For deep learning part, we implemented [QANet](https://arxiv.org/abs/1804.09541) for answer extraction in single paragraph.

The corresponding notebooks are **preprocess.ipynb**, **build_and_train.ipynb** and **dev_test.ipynb**.

Our system achieves a third place in Kaggle competition.

We also tried some end-to-end solutions using only deep learning. However, this does not give us a better result. More work can be done in the future. Our experiments are in **para_predict.ipynb**, **shard_norm.ipynb** and **merge.ipynb**.
