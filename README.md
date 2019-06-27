# speaker_embedding_playground

1. use the data from AISHELL
2. input data : I specify that Sij is the ith speaker's jth sentence and 
Si1 is the first sentence from the aishell dataset, and all the input data tuples are like the below format:
    (Skn, Sk1)
where the first element is the input and the second sentence is the ground truth
3. I will use dataset as the datastructure for input to the model training
4. the loss function will have MSE.
5. firstly, we will have an speaker embedding encoder, then, we will use this speaker embedding as the input to put into the seq2seq model to output a speech audio.
