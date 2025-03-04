# Telugu ASR Model using Whisper and PyTorch  

This repository contains an Automatic Speech Recognition (ASR) system for the Telugu language, leveraging OpenAI's Whisper model and PyTorch. 
The project involves preprocessing Telugu speech data, fine-tuning the Whisper model, and optimizing it for mobile deployment.  

## Features  
- Preprocessing Telugu Speech Data**: Noise removal and silence trimming  
- ASR Model: Using Whisper-small/tiny (PyTorch version)  
- Fine-tuning: Training Whisper on Telugu audio dataset  
- Model Optimization: Converting Whisper to TorchScript or ONNX for mobile deployment  

## Requirements  
- Python 3.x  
- PyTorch  
- OpenAI Whisper  
- Hugging Face Transformers  
- NumPy, Pandas  
- Librosa (for audio processing)  

## Dataset  
The dataset consists of Telugu audio files and a corresponding TSV text file. The files are stored in `https://drive.google.com/drive/folders/1ZFnbfTRbvldqd_igEYvKKuddZDZh2sgJ?usp=sharing` in Google Drive.  

## Results  
- Model performance evaluation on Telugu speech data  
- Accuracy, WER (Word Error Rate), and loss metrics  

## Future Improvements  
- Enhance dataset size and quality  
- Implement real-time speech-to-text inference  
- Improve inference speed on mobile devices  

## Acknowledgments  
- Hugging Face for ASR fine-tuning resources  
