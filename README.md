# Cox-PASNet
### Cox-PASNet is a pathway-based sparse deep neural network for survival analysis. 
# Get Started
## Example Datasets
To get started, you need to download example datasets from URLs as below:



<p><a href = "http://dataxlab.org/Cox-PASNet/train.csv" download  target="_blank">Train data</a></p>

<p><a href = "http://dataxlab.org/Cox-PASNet/validation.csv" download target="_blank" >validation data</a></p>
<p><a href = "http://dataxlab.org/Cox-PASNet/test.csv" download >Test data</a></p>
<p><a href = "http://dataxlab.org/Cox-PASNet/pathway_mask.csv" download >Pathway Mask data</a></p>
<p><a href = "http://dataxlab.org/Cox-PASNet/entire_data.csv" download >Entire data</a></p>


## Training, Validation and Evaluation of Cox-PASNet
Run.py: to train the model with the inputs from train.csv. Hyperparmeters are optimized by grid search automatically with validation.csv. C-index is used to evaluate the model performance with test.csv.
## Interpretation
Run_for_Interpret.py: to interpret the model with entire_data.csv.
