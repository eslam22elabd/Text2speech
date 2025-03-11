# Sentiment Analysis with TTS

This project performs sentiment analysis on Arabic and English text and converts the detected sentiment into speech using a TTS model.

## Installation

Run the following command to install the required dependencies:
```bash
pip install torch==2.5.0 transformers TTS langdetect
```

## Usage

1. Load the models for TTS and sentiment analysis.
2. Detect the language of the input text.
3. Perform sentiment analysis based on the detected language.
4. Map the sentiment to an appropriate emotion (happy, sad, or neutral).
5. Generate and save the speech output.

## Running in a Notebook

Simply execute the provided script inside a Jupyter Notebook. Make sure to have a sample `speaker.wav` file in the working directory.

## Notes
- Arabic sentiment analysis uses a combination of keyword-based detection and a pre-trained BERT model.
- English sentiment analysis uses a DistilBERT model fine-tuned for sentiment classification.
- The output audio file will be saved as `output.wav`.

Enjoy experimenting with sentiment-based speech synthesis! 🚀

