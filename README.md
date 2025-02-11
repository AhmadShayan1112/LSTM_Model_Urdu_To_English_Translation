# LSTM Model for Urdu to English Translation

## Overview
This repository contains a Jupyter Notebook implementing an LSTM-based sequence-to-sequence (Seq2Seq) model for translating Urdu text into English. The model is developed using PyTorch/Keras and applies NLP techniques such as tokenization, teacher forcing, and scheduled sampling.

## Features
- **LSTM-based Encoder-Decoder**: Uses Long Short-Term Memory (LSTM) networks for sequence modeling.
- **Data Preprocessing**: Cleans and tokenizes Urdu-English text pairs.
- **Scheduled Sampling**: Improves model stability during training.
- **Gradient Clipping & Xavier Initialization**: Enhances training efficiency.
- **Learning Rate Scheduling**: Optimizes convergence.
- **Future Improvements**: Beam Search for better translation accuracy.

## Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/AhmadShayan1112/LSTM_Model_Urdu_To_English_Translation.git
cd LSTM_Model_Urdu_To_English_Translation
pip install -r requirements.txt
```

## Usage
1. **Open Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
2. **Load the Notebook**: Open `LSTM_Model_Urdu_To_English_Translation.ipynb`.
3. **Run All Cells**: Execute the notebook cells in order to preprocess data, train the model, and test translation.

## Dataset
The model requires a parallel corpus of Urdu-English sentence pairs. You can use datasets from:
- [CCAligned](https://opus.nlpl.eu/CCAligned.php)
- [Tatoeba](https://tatoeba.org/eng/)

## Model Architecture
- **Encoder**: LSTM-based network processes Urdu text.
- **Decoder**: Generates English translation using sequential decoding.
- **Training**: Cross-entropy loss optimization with teacher forcing.

---

For any queries, reach out via GitHub issues or email!

