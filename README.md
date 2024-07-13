# Intel_Train
Inorder to acess the complete intex extension for transformers folder the user needs to login in this link 
https://jupyter-batch-us-region-1.cloud.intel.com/hub/user-redirect/lab/tree/intel-extension-for-transformers
In certain cases the user needs to create an external kernel in a local ennvironment which can be done with an anaconda package the entire procedure for creating a conda package as well a kernel has been included as a pdf in the repository
For the fine tuning section huggingface-cli login is required which can be installed with the the following cmd :
pip install huggingface_hub
from huggingface_hub import notebook_login
notebook_login()
The complete  step  by step procedure for huggingface login as well as the creation of tokens has been included in the single_node_finetuning_on_spr pdf 
Once the login is sucessful the user can run the fine tuning notebooks by either loading the meta lama model offline or by connecting it with the huggingface token
Once the model is loaded the user should download the different datsets required  for different type of finetuning such as alpaca dataset meant for text generation similarly cnn_dailymail dataset required for summarisation
The complete step by step by downloading of the dataset and unzipping of  the file in the terminal has been included in the single_node_finetuning_on_spr pdf
Once all the datasets have been unzipped and the lama model is loaded the user can finetune the 3 notebooks

