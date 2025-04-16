This folder stores notebooks that evaluated Baselines as well as the initial feasibility study.

The feasibility study uses a lot of code from the official paper.

The code in Baselines-2 just contains baselines and some additional processing on the dataset.

Baselines-final-run uses the dataset from Baselines-2 and then finally runs the models on the dataset and obtains all the evaluations for the baseline models

The contributions in code for this section are:
1. Processing of the dataset
2. A very generalizable sklearn-style pipeline to train and evaluate several models on several responders on various metrics
