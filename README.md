Kaggle Contest Template
========================

This repository can be used as a starter for contests on kaggle. It has placeholders for the most commonly encountered functionalities which can be implemented and extended as seen fit.

## Directory Structure:
- data
    -  file_list.md
- src
    - utils.py
    - train.py
    - valid.py
    - models.py
    - config.py
    - create_folds.py
- saved_models
    -  model_list.md
- notebooks
    - check_logging.ipynb
    - eda.ipynb
- references
    - list.md
- requirements.txt

### Content:
- The `data` folder contains the input files, images, etc for the contest
- The `src` folder contains all source code for the project except any jupyter notebooks 
- The `saved_models` folder contains weights and checkpoints for models we would like to use for inference 
- The `notebooks` folder contains jupyter notebooks used for quick debugging, exploratory data analysis, etc
- The `references` folder contains a list of reference papers, articles, etc relevant to the contest
- The `requirements.txt` is an optional file that can contain a list of requirements to run the code in the repository