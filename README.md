# Word Prediction using Bidirectional LSTM

An advanced **word prediction system** powered by a **Bidirectional LSTM model**, offering dynamic sentence construction with an interactive and user-friendly interface.

---

## Project Overview

This project aims to predict and suggest the next words based on a given sequence of input text. Users can interactively build sentences, either by selecting from four suggested options or typing their own input. The system updates predictions dynamically with each user interaction, creating an engaging experience.

---

## Key Features

- **Interactive Predictions**: Suggests four possible next words for user input.
- **Dynamic Sentence Building**: Users can construct sentences by selecting suggestions or typing their own words.
- **Machine Learning-Driven**: Built using a robust Bidirectional LSTM model for accurate and context-aware predictions.
- **Attractive UI**: Clean and visually appealing design for an enhanced user experience.

---

## Technical Details

### Model and Training

The system leverages a **Bidirectional Long Short-Term Memory (LSTM)** model, which processes text contextually by analyzing both preceding and following words in a sequence. This approach ensures predictions are relevant and aligned with the input.

### Data Preparation

- **Tokenization**: Converts text into numerical tokens.
- **Sequence Generation**: Splits text into input-output pairs for training.
- **Categorical Encoding**: Encodes outputs for compatibility with neural networks.

### Prediction Logic

- The model analyzes the input text and predicts the next words.
- Top four predictions are presented as suggestions based on their probability scores.

---

## Application Flow

1. **Input**: Users enter a starting phrase or sentence.
2. **Prediction**: The system generates four potential next words.
3. **Selection**: Users can click on a suggestion or input their own word.
4. **Update**: Predictions refresh based on the updated text.

---

## Use Cases

- **Creative Writing**: Helps writers generate ideas and complete sentences creatively.
- **Language Learning**: Assists learners in practicing and enhancing vocabulary.
- **Text Input Assistance**: Improves typing efficiency in messaging or note-taking.

---
