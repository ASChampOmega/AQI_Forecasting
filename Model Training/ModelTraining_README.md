# Model Training

These notebooks are the final model training notebooks. They were downloaded straight off my final run on Kaggle. These contain all the code for:

1. Several Custom Pytorch datasets -
   a. For GRU + RNN
   b. For GRU + RNN with Satellite Images
   c. For STGNN
   d. For STGNN with Satellite images
   e. For ConvGRU
2. Customized metrics loggers
   a. Logs training loss and create a tensorflow-esque progress bar from scratch
3. Model validation and training functions
4. Model evaluation on both classification and regression
5. Code to run and store results of all Ablation Study experiments
   a. Model Size and Run grid search on model params
   b. Input sequence length ablation
   c. Forecast horizon ablation
   d. (For graphs) Number of neighbors ablation study

RNNs and GRUs are grouped together
RNNs and GRUs with images are grouped together
GCNs and GATs are grouped together
GCNs and GATs with images are grouped together
ConvGRUs are separate
