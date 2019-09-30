# A Game Recommendation System
A game recommendation system developed using Steam data

## Setting up the environment
To set up the conda environment necessary to run the code in these notebook, run the following command in your project directory
```
conda create --name game_recsys --file requirements.txt
conda activate game_recsys
```
## Project structure/workflow
The `data` directory contains the raw user-game ratings and game metadata files. These are used by the `data_processing.ipynb` to process and format the data, as well as construct the training and test sets (located in the `train_test_split` directory).

The `metadata_processing.ipynb` processes and formats the game metadata file.

The `baseline_models.ipynb` builds and test baseline models of the recommendation system using the *surprise* python package: https://surprise.readthedocs.io/en/stable/

Finally, the `modelling.ipynb` builds and test all the models used in this project. 
