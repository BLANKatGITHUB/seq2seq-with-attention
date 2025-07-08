# English to French Translation using Seq2Seq with Attention

This notebook implements seq2seq model from scratch using custom attention mechanism Bahdanau and Luong.

## Notebook

1.  **Data Loading and Preprocessing**: Loads the dataset and prepares it for training.
2.  **Text Vectorization**: Converts text data into numerical format.
3.  **Model Building**: Defines and builds the Seq2Seq model with an attention mechanism.
4.  **Training**: Trains the model on the preprocessed data.
5.  **Inference**: Uses the trained model to translate new English sentences.
6.  **Evaluation**: Evaluates the model performance using BLEU score.
7.  **Saving Models**: Saves the trained encoder and decoder models.

## Model

The model consists of an encoder and a decoder, both using LSTM's. Custom attention mechanism are written from scratch.

The trained models are saved in the `models/` directory:

- `encoder.keras`
- `decoder.keras`

## Dataset

The model is trained on the [English-French translation dataset](https://www.kaggle.com/datasets/devicharith/language-translation-englishfrench) from Kaggle.
