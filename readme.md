# Drug review rating classification

Model for classifying consumer reviews on a wide range of medicines.
In the notebook it is possible to find a baseline based on **Bert finetuning** for the previously described task, with further hints at the end for possible further improvements.

## Quick start:

> python3 -m venv env

> source env/bin/activate

> pip3 install -r requirements.txt

(wait a while for installation then ) run drugreview.ipynb

**Google Co-lab option**: just git clone and run 'drugreview Co-lab.ipynb' in Co-lab.

## Note:
- the code works both for cpu and gpu (but training witch CPU is not feasble)
- in the local code the parameter 'training_subset' is 3 by default, change to train/evaluate on more than 3 samples
