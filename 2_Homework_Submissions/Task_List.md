# TaskList

- To create the data needed to train our recurrent neural network, we first parse the piano notes of our dataset, representing each file as a list of notes found in the file. We then create the training input sequences by taking subsets of the list representation for each song and created the corresponding training output sequences by simply taking the next note of each subset.
- To establish a baseline of music generation that we can improve on, we use recurrent neural networks (RNN), an existing and easily-replicable method. Generating music is formulated as a next-note prediction problem.
- With this training input and output, the model would be trained to predict the next note, which would then allow us to pass in any sequence of notes and get a prediction of the next note. Each input sequence was passed into an embedded layer that created embeddings of a size of 96.
- While the RNN next-note prediction model is easy and clean to implement, the generated music sounds far from ideal and there is very limited utility. Next steps include improving and adding multi instrument support.

### Sources
- MidiNet: https://github.com/annahung31/MidiNet-by-pytorch
- Next-note prediction: from https://github.com/Skuldur/Classical-Piano-Composer
- Code adapted from https://nbviewer.jupyter.org/github/craffel/midi-dataset/blob/master/Tutorial.ipynb
- Code to convert from MIDI to music21 adapted from https://github.com/Skuldur/Classical-Piano-Composer
- Lakh Pianoroll Dataset: https://salu133445.github.io/lakh-pianoroll-dataset/
- Genre Labels for songs in the Million Song Dataset: https://www.tagtraum.com/msd_genre_datasets.html

### References
- https://ai.plainenglish.io/building-a-lo-fi-hip-hop-generator-e24a005d0144
- https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5
- https://towardsdatascience.com/creating-a-pop-music-generator-with-the-transformer-5867511b382a
- https://towardsdatascience.com/practical-tips-for-training-a-music-model-755c62560ec2
- https://towardsdatascience.com/a-multitask-music-model-with-bert-transformer-xl-and-seq2seq-3d80bd2ea08e
- https://towardsdatascience.com/how-to-remix-the-chainsmokers-with-a-music-bot-6b920359248c
- MuseGAN: https://arxiv.org/abs/1709.06298
- MidiNet: https://arxiv.org/abs/1703.10847
- https://github.com/ashishpatel26/Best-Audio-Classification-Resources-with-Deep-learning#dl4m-details
