# Music Captioning CNN-LSTM
 Thesis project focusing on implementing various neural  network algorithms for music captioning tasks. The main objective is to  modify existing architectures and incorporate music information retrieval techniques to improve the experience for individuals with hearing impairments when listening to music.

for the original journal in bahasa Indonesia accessible online via : https://journal.likmi.ac.id/index.php/media-informatika/article/view/213/108

How to use this project:
1. data_explorer.ipynb = the dataset explorer to download the audio files and save them to local storage. The original dataset is available at https://www.kaggle.com/datasets/googleai/musiccaps, including this data_explorer script.
2. caption_extract_ms.ipynb = this notebook functions as a feature extractor script to capture the mel spectrogram from the downloaded audio files.
3. the pre-trained word embedding is available [here](https://nlp.stanford.edu/projects/glove/)
4. MusicCaptioning.ipynb = the complete model script including training, tuning, testing, and validation.

this project is highly inspired by [this](https://github.com/ilaria-manco/muscaps) project