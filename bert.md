what does a BERT embedding have?
Token+Segment+Position embdedding. Inpout embdeddings are the sum of token embeddings, segmentation embeddings and position embeddings.

How many dimension vector does BERT pre trained model has?
768 dimensions

How to generate BERT embeddings?
Raw Input --> Word Piece Tokenization -->

What does token embedding refer to?
look up from 768 dimension vector embedding

What does Segment embedding refer to?
refers to n where n is sentence in the input context

What does position embedding refer to?
The position embedding determines the index portion of the individual token in the input sequence

Why ROberta over BERT?
1) Fine tuned
2) more training data

What is maximum sequence length parameter?
he max of sequence length parameter specifies the maximum number of tokens that can be passed into BERT model with a single sample.

What is a  Epoch?
An epoch is a full pass through the training data set.

what is Transfer learning?
It's a machine learning technique where a model is trained on one task and then repurposed on a second related task.

Why fine tuning pretained model?
Fine tuning is generally faster than pretraining, as the model doesn't have to learn millions or billions of BERT vector representations. Also note that fine tuning is a supervised learning step, as you fit the model using labeled training data. 
