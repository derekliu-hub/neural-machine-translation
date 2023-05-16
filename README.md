# Translate Spanish to English Using Deep Learning
In this project, two different models were developed to translate sentences from Spanish to English. One was based on recurrent neural networks while the other was based on transformers. The notebook.ipynb file walks through all the code written to set up the data and train/test the models. You can download the dataset used [here](http://www.manythings.org/anki/spa-eng.zip). It has also been included in the repository as the spa.txt file. The source website, http://www.manythings.org/anki, provides resources for ESL students and the particular dataset here contains 13,000+ examples of English sentences and their translations in Spanish. Saved versions of the encoder and decoders as .pt files are also present. Note that the notebook code was run on Google Colab with the free GPU compute for faster training. Both models achieved BLEU scores above the following benchmarks:
    
    BLEU-1 > 0.290
    BLEU-2 > 0.082
    BLEU-3 > 0.060
    BLEU-4 > 0.056