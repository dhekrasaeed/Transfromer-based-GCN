# Transformer-based-GCN
## Requirements
- Python 3.7
- NLTK 3.4
- [PyTorch 1.0](https://pytorch.org)
- [Huggingface transformer 0.6.2](https://github.com/huggingface/transformers/releases/tag/v0.6.2)
- [SST-2](https://github.com/kodenii/BERT-SST2)
- [CoLA](https://github.com/nyu-mll/GLUE-baselines)

## Directory Structure
The *data/* directory contains the original datasets and the corresponding pre-processed data. The *output/* directory saves the model files while training the models. The *pytorch_pretrained_bert/* directory is the module of Huggingface transformer. The other files with the *.py* suffix are models, utility functions, training programs, and prediction programs.

## Running the code

### Pre-processing datasets
Run *prepare_data.py* to pre-process the dataset and generate the vocabulary graph. 
