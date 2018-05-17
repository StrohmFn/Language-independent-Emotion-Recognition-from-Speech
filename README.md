# Neural Network for Emotion Recognition from Speech

Mono- and cross-lingual emotion classification in recorded speech through a convolutional neural network.

For detailed information of this work you are welcome to read my [PAPER](https://github.com/StrohmFn/Language-independent-Emotion-Recognition-from-Speech/blob/master/language-independent-emotion.pdf).

### Data
This model was trained and tested on a collective dataset, 
consisting of the english [IEMOCAP](https://sail.usc.edu/iemocap/)
and the french [RECOLA](http://diuf.unifr.ch/diva/recola/index.html) datasets.
We use [openSMILE](https://mediatum.ub.tum.de/doc/1082431/1082431.pdf) to extract features.
The used config files and the resulting features can be found in the 'openSMILE' folder.
The Python script in the 'Preprocessing' folder transfers this extracted information into the right format to feed our neural network.

## Getting Started
You can view the notebook [here] (https://github.com/StrohmFn/Language-independent-Emotion-Recognition-from-Speech/blob/master/CNN%20SpeechRecognition.ipynb) on github. 
### Run the notebook
#### Prerequisites
- Python 3
- Tensorflow
- Jupyter

#### Starting the notebook
Simply open a new terminal in the directory and type:
```bash
> jupyter notebook
```
#### Setup model
make sure you run all codeblocks from top to bottom to setup the network

### Running the tests
To test the model, you need only to run the last codeblock.
This will evaluate the model and print the accuracy for each testset.


## Built With

* [Tensorflow](https://www.tensorflow.org/) - The framework to create the model
* [Project Jupyter](https://jupyter.org/) - Nice and easy python notebooks


## Contributors

* **A. Kaplan** - [nymvno](https://github.com/nymvno)
* **C. Tasci** - [StraysWonderland](https://github.com/StraysWonderland)
