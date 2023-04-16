# Beethov-EN | Senior Capstone Project
![image](https://user-images.githubusercontent.com/54280820/232318936-5a6966f2-919f-4ef7-98d2-7830f45edba4.png)


### Team Members
- Priyan Rai


## Project Abstract
This is a Dall-E inspired music generation engine that will be able to compose musical compositions based on user inputs. Music generation using deep learning techniques has been a topic of interest for the past two decades. Music proves to be a different challenge compared to images, among three main dimensions: Firstly, music is temporal, with a hierarchical structure with dependencies across time. Secondly, music consists of multiple instruments that are interdependent and unfold across time. Thirdly, music is grouped into chords, arpeggios and melodies — hence each time-step may have multiple outputs.

## Project Navigation
- [Project Description](README.md)
- [Personal Bio](2_Homework_Submissions/Professional_Bio_PriyanRai.md)
- [Design Diagrams](2_Homework_Submissions/Design_Diagrams)
- [Task List](2_Homework_Submissions/Task_List.md)
- [How To](2_Homework_Submissions/HowTo.md)
- [Poster](2_Homework_Submissions/Poster_Final.pdf)
- [Timeline/Effort Matrix](2_Homework_Submissions/Timeline_Effort.md)
- [Self Assesment](2_Homework_Submissions/Self_Assesment.pdf)
- [Slideshow](https://docs.google.com/presentation/d/1PnDS7-w-HhcedK-apJhREPlPv2TgKBws/edit?usp=sharing&ouid=108564022775341956840&rtpof=true&sd=true)
- [Appendix](2_Homework_Submissions/Task_List.md)

# How to work with project

## Step 1: Download Anaconda

To download Anaconda, go to the [Anaconda website](https://www.anaconda.com/products/individual). Select the version of Anaconda that you want to install based on your operating system. There are two versions available: Anaconda for Python 2.7 and Anaconda for Python 3.7. Once you have made your selection, click the "Download" button.

## Step 2: Install Anaconda

Once you have downloaded the Anaconda installer, locate the downloaded file on your system and double-click it to start the installation process. Follow the instructions provided by the installer to complete the installation process.

## Step 3: Verify Anaconda Installation

After installation, open the Anaconda Navigator to verify that it has been installed correctly. On Windows, click the Start menu and search for "Anaconda Navigator". On macOS, open Launchpad and click on the Anaconda Navigator icon. 

Once you have opened the Anaconda Navigator, you should be able to see various tools such as Jupyter Notebook.

## Step 4: Install Jupyter Notebook
![image](https://user-images.githubusercontent.com/54280820/232316306-0c55ff34-1d48-4638-9eb1-5a5659b67cf0.png)

## Libraries Installation Instructions

### 1. Numpy
Numpy is a popular Python library for numerical computing. To install Numpy, simply open your terminal and enter the following command:
```
pip install numpy
```


### 2. Pandas
Pandas is another popular Python library used for data manipulation and analysis. To install Pandas, enter the following command in your terminal:
```
pip install pandas
```


### 3. Matplotlib
Matplotlib is a popular data visualization library for Python. To install Matplotlib, enter the following command in your terminal:

```
pip install matplotlib
```


### 4. Pretty_MIDI
Pretty_MIDI is a Python library used to create and modify MIDI files. To install Pretty_MIDI, enter the following command in your terminal:

```
pip install pretty_midi
```


### 5. Pypianoroll
Pypianoroll is a Python library used to create and manipulate piano rolls, which are commonly used to represent musical data. To install Pypianoroll, enter the following command in your terminal:

```
pip install pypianoroll
```


### 6. Music21
Music21 is a Python library used for computer-aided musicology, which can be used to analyze, manipulate, and generate musical data. To install Music21, enter the following command in your terminal:
```
pip install music21
```


### 7. Librosa
Librosa is a Python library used for audio analysis and manipulation. To install Librosa, enter the following command in your terminal:

```
pip install librosa
```


### 8. Keras
Keras is a popular deep learning framework for Python. To install Keras, enter the following command in your terminal:
```
pip install keras
```


### 9. Torch
Torch is a popular deep learning framework for Python. To install Torch, enter the following command in your terminal:
```
pip install torch
```

# How to Download and Setup Lakh Piano Dataset in Google Colab

## Introduction
The Lakh Piano Dataset is a large collection of MIDI files and aligned audio files that can be used for music research and analysis. In this guide, we will go over the process of downloading and setting up the Lakh Piano Dataset in Google Colab.

## Downloading the Dataset
To download the Lakh Piano Dataset, follow these steps:

1. Go to the [official website](https://colinraffel.com/projects/lmd/) of the dataset.

2. Click on the "Download" button, and then select "lmd_full.tar.gz" to download the full dataset.

3. Once the download is complete, you can upload the dataset to your Google Drive by following these steps:

   - Open your Google Drive and create a new folder named "lmd".
   
   - Upload the downloaded file ("lmd_full.tar.gz") to the "lmd" folder.
   
   - Right-click on the file and select "Copy path".
   
## Setting Up the Dataset in Google Colab
To set up the Lakh Piano Dataset in Google Colab, follow these steps:

1. Open a new notebook in Google Colab.

2. Mount your Google Drive by running the following code:

   ```python
   from google.colab import drive
   drive.mount('/content/drive')



## Step 5: Open the Desired Project File in Google Collab or Jupyter Notebook

### * Project has no budget or ABET constraints

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
