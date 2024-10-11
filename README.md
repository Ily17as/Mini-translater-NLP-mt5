# Mini-translater
The translater based on the study material. Works with 'ru' to 'en' and wiseverse (in the second scenairon need to be modified). Can be run on the local setup, 
but more recomended to use some cloud calculation systems because of complexity and memory capacity. Using MT5 open source Google model and open source database of languages. 

This is the project directed to the study in NLP field. 
The project easyly can be extented to more complex translation model by extending dataset and adding new languages.

The source of the content is the study course of N.E. Bauman Moscow State Technical University:

Sourse: [Youtube](https://www.youtube.com/playlist?list=PLgtntV-BLRqgJRhcZHz8GtFC3j_F27IDg)

Code: [GitHub](https://github.com/averkij/mstu-nlp-course)

## Agenda
- [Tech](#tech)
- [Beggining](#beggining)
- [Dev](#dev)
- [Tests](#tests)
- [Contributing](#contributing)

## Tech
- Python
- Pytorch
- Cuda
- MT5
- OPUS Database
- Transformers

## Beggining
1. Before execution need to extract the data from the en-ru.tmx.gz zip file (in the code I provided the line for it but it some times work improper)
2. Install the requirements.txt
3. Configure the env to the cloud system
4. Set up nvidia cuda env
5. Execute step by step

P.S. provided the terminal commands if any deficulties with IDE.

## Dev

### Demands
For running project will be needed [Jupyter Notebook](https://jupyter.org/) access it via [Pycharm](https://www.jetbrains.com/pycharm/), [Colab](https://colab.google/), [Anaconda](https://www.anaconda.com/) or others.

### Installing requirements
For installing requirements use:
```sh
pip install -r requirements.txt
```


## Tests
Tests of the model provided in the source notebook at the last stages. 

I used to devide the database into train and test dataset and tested the model after training.



## Contributing
You can help to the project by extending funcianality making interface and other stuff, or extend the database and NN-model.

### Why I created this?
I created this project for study transformers and NN.

## Sources
Sourse: [Youtube](https://www.youtube.com/playlist?list=PLgtntV-BLRqgJRhcZHz8GtFC3j_F27IDg)

Code: [GitHub](https://github.com/averkij/mstu-nlp-course)

Sourse: [A Massively Multilingual Pre-trained Text-to-Text Transformer](https://www.google.com/url?q=https%3A%2F%2Faclanthology.org%2F2021.naacl-main.41%2F)

Code: [GitHub](https://github.com/google-research/multilingual-t5)

Data: [Opus](https://www.google.com/url?q=https%3A%2F%2Fopus.nlpl.eu%2F)

### License
- MIT License
