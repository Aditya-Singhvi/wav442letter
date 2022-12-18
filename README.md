# wav442letter
Fully convolutional speech-to-text model based on Facebook's Wav2Letter. 
Developed alongside Andrew Schallwig and Matt Palazzolo for EECS 442 at the University of Michigan.

The original paper can be found [here](https://arxiv.org/abs/1609.03193).

Our results are summarized below, with Facebook's original results on the left and ours on the right. 
Our goal was to try to replicate Facebook's results with far fewer computational resources; although clearly not successful, we certainly achieved a decent approximation given that we used 0.3% of the training data and 30% of the trainable parameters of the original model. 

<img width="665" alt="Screen Shot 2022-12-18 at 00 20 53" src="https://user-images.githubusercontent.com/50927446/208288349-7286abc1-b284-421d-850d-e22f9ef30945.png">

The model was built in PyTorch and trained on the *dev-clean* subset of the LibriSpeech ASR corpus, available [here](https://www.openslr.org/12). 
