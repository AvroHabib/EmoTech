# EmoTech: A Multi-modal Speech Emotion Recognition Using Multi-source Low-level Information with Hybrid Recurrent Network

Emotion recognition is a critical task in human-
computer interaction, enabling more intuitive and responsive
systems. This study presents a multimodal emotion recognition
system that combines low-level information from audio and text,
leveraging both Convolutional Neural Networks (CNNs) and
Bidirectional Long Short-Term Memory Networks (BiLSTMs).
The proposed system consists of two parallel networks: an Audio
Block and a Text Block. Mel Frequency Cepstral Coefficients
(MFCCs) are extracted and processed by a BiLSTM network
and a 2D convolutional network to capture low-level intrinsic
and extrinsic features from speech. Simultaneously, a combined
BiLSTM-CNN network extracts the low-level sequential nature
of text from word embeddings corresponding to the available
audio. This low-level information from both speech and text is
then concatenated and processed by several fully connected layers
to classify the speech emotion. Experimental results demonstrate
that the proposed EmoTech accurately recognizes emotions from
combined audio and text inputs, achieving an overall accuracy of
84%. This solution outperforms previously proposed approaches
for the same dataset and modalities.

## Dataset and Data Preprocessing

<p align="center">
  <img src="assets/emo1.png" alt="The statistics of ten classes in IEMOCAP Dataset before augmentation" width="500"/>
  <br><em>The statistics of ten classes in IEMOCAP Dataset before augmentation</em>
</p>

<p align="center">
  <img src="assets/emo2.png" alt="The statistics of five dominated classes in IEMOCAP Dataset after augmentation" width="500"/>
  <br><em>The statistics of five dominated classes in IEMOCAP Dataset after augmentation</em>
</p>

## Methodology


<p align="center">
  <img src="assets/emo3.png" alt="Basic block diagram of the proposed EmoTech Architecture" width="500"/>
  <br><em>Basic block diagram of the proposed EmoTech Architecture</em>
</p>

<p align="center">
  <img src="assets/emo4.png" alt="A detail block diagram of audio signal processing in EmoTech" width="500"/>
  <br><em>A detail block diagram of audio signal processing in EmoTech</em>
</p>

<p align="center">
  <img src="assets/emo5.png" alt="A detail block diagram of text data processing in EmoTech" width="500"/>
  <br><em>A detail block diagram of text data processing in EmoTech</em>
</p>

<p align="center">
  <img src="assets/emo6.png" alt="A detail block diagram of classification processing in EmoTech" width="500"/>
  <br><em>A detail block diagram of classification processing in EmoTech</em>
</p>


## Results 

<p align="center">
  <img src="assets/emo7.png" alt="The impact of data augmentation on accuracy" width="500"/>
  <br><em>The impact of data augmentation on accuracy</em>
</p>

<p align="center">
  <img src="assets/emo8.png" alt="Different classification metrics for individual classes" width="500"/>
  <br><em>Different classification metrics for individual classes</em>
</p>

<p align="center">
  <img src="assets/emo9.png" alt="Confusion Matrix in classifying five emotion using EmoTech architecture" width="500"/>
  <br><em>Confusion Matrix in classifying five emotion using EmoTech architecture</em>
</p>

<p align="center">
  <img src="assets/emo10.png" alt="Comparison of different algorithms in SER" width="500"/>
  <br><em>Comparison of different algorithms in SER</em>
</p>

