# NanoGPT
A very simple version of character-level Transformer model (GPT) trained on Shakespeare.

A much, much smaller version of a transformer model similar to the one ChatGPT uses trained on raw Shakespeare text.

The model learns which characters are likely to follow a sequence of previous characters based on text provided by https://raw.githubusercontent.com/karpathy/char-rnn/master/data/tinyshakespeare/input.txt.

# Training
Without training the model just spews a random sequence of characters.

After some training the model learns symbols are very rare and capital letters are only at the beginning of sentences.

With more training words begin to form but the sentences don't make any sense.

With a lot of training not only words but also sentences will begin to make sense.

However there is no real story and the model just continues generating characters that are likely to follow the previous set of characters.

A lot of training is required using a very good GPU.
