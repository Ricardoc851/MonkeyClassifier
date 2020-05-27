# MonkeyClassifier
Classifies 10 different monkey species

# Prerequesites 
Delete current Pytorch and reinstall torch==1.4.0 in order to use Fast.AI

# Installation 
Import fastai.
set up kaggle and use the 10-monkey-species data.
transform data into 128 x 128 and add data augmentation.
Add data with parameters when using image_net dataset.
Get a batch size 32 x 32 to find internals of the data.
Load learner first where we add AUROC as our metric and Vgg16_bn as our model.
Learn.recorder.plot gives us the learning rate from a minimum gradient and we train the value for 2 cycles.

# Test Runs
Test a bad prediction with Prediction/Actual/Loss/Probability as our categories.
Test on single images.
Create a good prediction.

# Results
Get a very high percentage (99%-100%) of an actual monkey specie predicted from an image.
