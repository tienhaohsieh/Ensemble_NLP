# Ensemble NLP model
This is an example training an ensemble NLP models. 
The database (prompt-image pair) is from HuggingFace<sup>1</sup>
The script will training the model with different weighting at the 384 dimensional (encoding vector).

<sup>1</sup>https://huggingface.co/datasets/poloclub/diffusiondb


Ref:  
https://www.kaggle.com/code/mvvppp/sd2-gpt2-prompt-image-gen-dataset-creation  
https://www.kaggle.com/code/andradaolteanu/img2text-image-generator-using-diffusers  
https://www.kaggle.com/code/debarshichanda/pytorch-blip-training/notebook  

#### Requirments:
* PIL
* textwrap
* Numpy
* Matplotlib
* pathlib
* tqdm
* torch
* pandas
* diffusers
* transformers

### Example of trainning performance
![image](https://github.com/tienhaohsieh/Ensemble_NLP/blob/master/trainning.png)
### Analyse of weighting in between two NLP model.
![image](https://github.com/tienhaohsieh/Ensemble_NLP/blob/master/analyse.png)
### Example of prompt-image pairs (training dataset) from HuggingFace
![image](https://github.com/tienhaohsieh/Ensemble_NLP/blob/master/HF_example.png)
