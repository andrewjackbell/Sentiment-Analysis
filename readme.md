

# Sentiment Analysis  (SemEval 2017 Task 4a)

## Instructions

1. Install required packages (Conda environment recommended)
2. Set `data_dir` in the notebook to appropriate directory
3. Add all required files into this directory
4. Change device with `DEVICE = torch.device('...') ` in user-defined constants section
5. Set `train=True` in the cell for the desired model you want to train
6. Run Notebook

## Required Files

* Training and development sets from SemEval 2017 Task 4(a)
* Any desired test sets, in the same format as the training data
* Emoji Dictionary `Emoji_Dict.p`, from https://www.kaggle.com/datasets/divyansh22/emoji-dictionary-1?resource=download
* Slang Dictionary `slang.txt`, from https://www.kaggle.com/code/nmaguette/up-to-date-list-of-slangs-for-text-preprocessing/notebook
* GloVe Vectors `glovee.6B.100d.txt`, from https://nlp.stanford.edu/projects/glove/

##  Required Packages

* Pytorch (tested on 1.13.1+cu117)
* Transformers (https://huggingface.co/docs/transformers/installation)
* NLTK
* Scikit-learn
* Numpy
* Matplotlib (for plotting results)
* Tabulate (for printing results)
* Tqdm (for progress bars)

