# Bird-Sound-Classification

Inference_from_Efficient_BO:
This notebook runs inference on BirdCLEF 2025 test soundscapes and generates a submission file. It supports both single model inference and ensemble inference with multiple models.\\

Audio_to_melspec:
Pre-processing (Extracting time and frequency features from audio files)

EfficientNet_B0_Pytorch_[Train]:
Training 

The preprocessing notebook focuses on transforming audio into a visual representation suitable for CNNs. The training notebook details the model architecture, training procedures including data augmentation and cross-validation, and saving the trained weights. Finally, the inference notebook explains how to load trained models, process unseen audio, and predict bird species to create the competition submission.





