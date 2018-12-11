# Neural Machine Translation with Attention Model

The goal is to build a Neural Machine Translation (NMT) model to translate human readable dates ("25th of June, 2009") into machine readable dates ("2009-06-25").I will do this using an attention model.
Attention is a mechanism that was developed to improve the performance of the Encoder-Decoder RNN on machine translation.
Attention is proposed as a method to both align and translate.
Alignment is the problem in machine translation that identifies which parts of the input sequence are relevant to each word in the output, whereas translation is the process of using the relevant information to select the appropriate output.
Instead of decoding the input sequence into a single fixed context vector, the attention model develops a context vector that is filtered specifically for each output time step.
(This mini-project is a part of Deep Learning specialization course. The dataset, any pre-trained weights/models and Model Architecture used were provided by Coursera.)
