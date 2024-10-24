# Fine-Tuning Text-to-Speech (TTS) Models

## Overview
This project involves fine-tuning two TTS models for specific objectives: one for English technical vocabulary and the other for the Turkish language. The goal is to enhance pronunciation accuracy for technical terms in English and generate high-quality speech in Turkish.

## Task 1: Fine-Tuning TTS for English Technical Vocabulary

**Objective:**  
Fine-tune a TTS model to accurately pronounce technical terms commonly used in English technical interviews.

### Solution Overview:
- **Model Used:** SpeechT5
- **Dataset:**  
  Created a custom dataset by recording voice samples of various technical terms and converting them to .wav files.
  
### Fine-Tuning Process:
- The model was fine-tuned to enhance pronunciation accuracy, particularly for acronyms and abbreviations.
- Adjusted hyperparameters to prevent overfitting while ensuring high-quality output.

### Key Results:
- The fine-tuned model was evaluated on several acronyms and technical terms, demonstrating improved pronunciation accuracy.

---

## Task 2: Fine-Tuning TTS for Turkish

**Objective:**  
Fine-tune a TTS model to generate high-quality speech in Turkish.

### Solution Overview:
- **Model Used:** SpeechT5
- **Dataset:**  
  A collection of Turkish audio recordings sourced from the [Turkish Voice Dataset](https://huggingface.co/datasets/erenfazlioglu/turkishvoicedataset).

### Fine-Tuning Process:
- The model was adjusted to synthesize speech that adheres to Turkish phonological rules, focusing on pronunciation, prosody, and stress patterns.
- Ensured speaker diversity in the dataset to improve generalization and enhance the naturalness of the output.

### Key Results:
- The model was evaluated for naturalness and intelligibility by native Turkish speakers, showing promising results in speech synthesis quality.

---

## Step 3: Install Requirements
!pip install -r requirements.txt
