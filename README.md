# Automatic prompt-image generator
This is an automatic prompt image pair generator. 
We use transformers<sup>1</sup> to generate prompt which is later used as an input for StableDiffusionPipeline<sup>2</sup> for imaging.

<sup>1</sup>https://pypi.org/project/transformers/  
<sup>2</sup>https://huggingface.co/docs/diffusers/api/pipelines/stable_diffusion/overview  

Ref:  
https://www.kaggle.com/code/mvvppp/sd2-gpt2-prompt-image-gen-dataset-creation  
https://www.kaggle.com/code/andradaolteanu/img2text-image-generator-using-diffusers  

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

### Example
![image](https://github.com/tienhaohsieh/prompt-image-generator/blob/master/generatorImage.png)
