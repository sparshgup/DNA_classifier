# DNA_classifier
## Ultimate objective: Use DNA sequence to determine the superpopulation of a person

### As of 2021/07/20 1917hrs:
* **master.py** - Main file of the project, run this. This calls everything. Should have no complex code.
* **ML.py** - This file contains the LSTM creation and training function.
* **trainingData.py** - Contains generator function: Reads .bin files and stores data in one hot vectors.
* **parseSequence.py** - Reads the data in all unzipped data files (.filt.fastq) and encodes the raw sequences in a binary file (.bin)
* **unzipAllGz.py** - Unzips all .gz files
* **downloadData.py** - Downloads all sequence reads (.filt.fastq.gz) of all samples and stores it into ./phase3_data/sampleName/
* **samples_population.csv** - CSV file summarizing the samples of 3202 people, their genders, population code and the superpopulation code.
* **next to do**:
  * train model for subsets of data seperately and store trained weights
  * combine the weights trained on different subsets
