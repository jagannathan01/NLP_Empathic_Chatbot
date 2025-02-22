There are 3 notebooks uploaded for 3 tasks.

1. Topic Classification : This notebook contains the code for Dialogue Manager for 3 Tasks : Topic Classification, Subreddit Classification and Empathic Context Classification. Each task has a specific dataset loaded, using which the model is trained. Run each cell one by one, after which the notebook has sample examples for testing purposes. The notebook also has the code for classification report.

2. Response Generation : This notebook has the code for Response Generation for each of Empathic, ChitChat and Reddit data. Run each cell one by one to load the dataset and train the model. After that, the notebook has sample examaples for testing purposes. For testing purpose, the examples are tested by providing the topic, subreddit and empathic context as static values. But in end to end use case, the topic from the Dialogue Manager acts as the input for determining the model to bve processed.

3. Evaluation Metrics : This notebook contains code for computing the evaluation metrics such as BERT, BLEU, ROUGE and PERPLEXITY scores. The code computes evaluation metrics by loading the complete dataset, creating a test data split and uses that to evaluate the metrics. the notebook also has cell level output which was computed and reported in the individual report. These scores were computed using models trained during response generation.
