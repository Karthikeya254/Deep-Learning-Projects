# Deep-Learning-Projects
This repo contains the work done as a part of Deep Learnng Systems course.

### I. Network Compression using SVD
- Trained a 5 layer DNN to classify MNIST data.
- Applied SVD on layer weights to reduce dimensions.
- Trained a new DNN by splitting each layer into two layers with corresponding left and right singular matrices as their weights.
- Total number of network parameters were reduced from 5 million to 0.215 million, without significantly affecting test error.

### II. Speech Denoising using RNN
- Trained a 2 layer RNN with GRU cells to seperate out clean signal from a noise induced signal.
- Acheive a good SNR (Signal to Noise Ratio) on the denoised test audio files.
