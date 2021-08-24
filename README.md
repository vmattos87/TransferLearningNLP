# TransferLearningNLP
Transfer Learning for NLP with TensorFlow Hub

In this project we use pre-trained Natural Language Processing text embedding models from TensorFlow Hub, perform transfer learning to fine-tune models on real-world data, build and evaluate multiple models for text classification with TensorFlow, and visualize model performance metrics with Tensorboard.

With Keras Sequential API, we create vectors using word-based and context based representation models available at Tensorflow Hub, like GoogleNews Swivel-20, Neural-Net Language Model (NNLM) and Universal Sentence Encoder. Then we convert sentences into embeddings by training these several TF-Hub modules, also fine-tuning some of these. Finally, their performance is evaluated by accuracy and loss curves with matplotlib and Tensorboard visualizations.
