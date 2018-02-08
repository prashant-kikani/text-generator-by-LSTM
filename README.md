# text-generator-by-LSTM

It predicts next word and generate the whole play in shakespeare style given the seed sequence. <br/>
Simple LSTM of 128 units is used with one Dense layer. <br/>
You can cut the dataset to half if your laptop or PC run out of memory while creating the train data for neural network. <br/>
Minimimum 20 to 25 epoch is required to generate a human like play. Which requires a great amount of time and computantional power (many GPUs)<br/>
<br/>
You can feed any dataset to it. It will learn from it. And will generate further.

## Alternatives to do the same task
We can use Markov chains to do the same. But it will only rely on the previous word, not on the whole previous line. And that will make output artificial rather than natural.<br/> 
LSTM model also considers previous 15 words to predict next word. That's why it's a better choice.
