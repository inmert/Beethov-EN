# TaskList

-To create the data needed to train our recurrent neural network, we first parsed the piano notes of our dataset, representing each file as a list of notes found in the file. We then created the training input sequences by taking subsets of the list representation for each song and created the corresponding training output sequences by simply taking the next note of each subset
- To establish a baseline of music generation that we can improve on, we used recurrent neural networks (RNN), an existing and easily-replicable method. Generating music is formulated as a next-note prediction problem.
- With this training input and output, the model would be trained to predict the next note, which would then allow us to pass in any sequence of notes and get a prediction of the next note. Each input sequence was passed into an embedded layer that created embeddings of a size of 96.
- While the RNN next-note prediction model is easy and clean to implement, the generated music sounds far from ideal and there is very limited utility. Next steps include improving and adding multi instrument support.
