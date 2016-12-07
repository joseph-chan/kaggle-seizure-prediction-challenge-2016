## Reproduce the solution

install python 2.7 with the following dependencies:

- numpy
- scipy
- pandas
- scikit-learn
- pyriemann
- mne-python
- progressbar
- pyyaml


`pip install numpy scipy pandas scikit-learn pyriemann mne progressbar pyyaml`

## Run the solution

to generate features :

`sh batch_features.sh`

to generate models

`sh batch_submission.sh`

output files will be placed in the `submission` folder at the root of the repository