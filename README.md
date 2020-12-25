# Abstract
In recent years there’s is growing research for environmental sound classification with a plethora of real-world applications, especially in audio fields like speech and music. Spectral images based deep learning models are proven better performance compared to standard methods. This research work is aimed at creating an effective approach by combining the three auditory features like Log-Mel Spectrogram (LM), Chroma Stft (CST) and Mel Frequency Cepstral Coefficient (MFCC) for extensive representation of environmental sound classification using Convolutional Neural Networks (CNN) with audio-based data augmentation is proposed. The experiment results shows multi-feature inputs gave better performance than single spectral image dimensions. In this approach three different spectral image spectrogram features are extracted from audio clips, and then randomly selected CNN models are learned from scratch. Finally, CNN trained models are fused together with aggregation methods to compose MF-CNN model. For this experiment Us8k, ESC-50 and ESC-10 datasets are considered for evaluation. Also, significant data augmentation are proposed for synthetic data creation instead of using conventional augmentation methods for images. The experiment results shows that combined features with lighter network CNN models outperforms other state-of-art methods for environmental sound classification. The proposed MF-CNN fused model with data augmentation achieved competitive results on UrbanSound8K datasets compared to existing models.
