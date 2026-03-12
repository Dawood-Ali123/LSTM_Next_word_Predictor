# LSTM_Next_word_Predictor
## Project Overview
This project builds a **Next Word Prediction model using LSTM (Long Short-Term Memory)**.
The model learns patterns from a dataset of jokes and predicts the most probable next word in a sentence.

Example:

Input:

```
why did the robot
```

Prediction:

```
write poetry because it loved neural networks
```

---

## Technologies Used

* Python
* TensorFlow / Keras
* Natural Language Processing (NLP)
* LSTM Neural Networks
* Tokenization
* Sequence Padding

---

## Project Pipeline

1. Dataset preparation (jokes dataset)
2. Text preprocessing
3. Tokenization
4. Sequence generation (N-grams)
5. Padding sequences
6. Splitting input and output
7. Building LSTM model
8. Training the model
9. Predicting the next word

---

## Model Architecture

Embedding Layer → LSTM Layer → Dense Softmax Layer

```
Input Text
   ↓
Tokenizer
   ↓
Word Sequences
   ↓
Embedding Layer
   ↓
LSTM Layer
   ↓
Dense (Softmax)
   ↓
Next Word Prediction
```

---

## Example

Input sentence:

```
why did the robot
```

Predicted output:

```
write poetry because it loved neural networks
```

---

## How to Run the Project

1. Clone the repository

```
git clone https://github.com/Dawood-Ali123/LSTM_Next_word_Predictor.git

2. Install required libraries
```
pip install tensorflow numpy
```
3. Run the notebook
```
Nextwordpredictor.ipynb
```

---

## Future Improvements

* Train the model on a larger dataset
* Improve prediction accuracy
* Add a web interface using Flask or Streamlit
* Deploy the model as an AI application

---

## Author
**Dawood Ali**
Machine Learning & Data Science Student
