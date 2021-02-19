# Exo Model Creation

This repository is to be used in conjunction with the [Exo](https://github.com/casuallyexisting/exo) repository to create a model to run it with.

## Installation

- Download the 'data' folder from this repository (if using iMessage data, see Usage)
- Open the Google Colab notebook found [here](https://colab.research.google.com/drive/1wgfCBnebdW1jDZavbtnWuig5-Io63KpF?usp=sharing)

## Usage
### Data Formatting
Start by formatting your data in the format found [here](https://github.com/casuallyexisting/exo-model-creation/blob/master/data/data_format.md)
- You also need a file with the names of the people in the data, and a set of testing data.

If you have access to a mac, you can download iMessage transcripts to use with the trainer. Download it from [here](https://github.com/dsouzarc/iMessageAnalyzer), and select Export > Export Conversation As > (.csv)
- Run that through parse.py in the data folder you downloaded earlier, and take note of the 'output' folder.
### Training the Model
Go to the Colab notebook and follow the instructions. once the model is downloaded, you're free to use it with the Exo repo!
## Contributing
Contributing is greatly appreciated, please open an issue in the 'Exo' repo to get started.

## Todo
- Add more ways to get formatted data
- Create public datasets to use in models
