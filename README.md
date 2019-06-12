## Lab2 For Data Mining 2018 Fall @ NTHU
This repository contains all the instructions and necessary code for Data Mining 2018 (Fall) lab session 2.

---  
#### Clone or Download this repository
* **Git clone:**    
    
        $ git clone https://github.com/EvanYu800112/dm_2018Fall_Lab2.git
        
* **Download zip file:**  [download link](https://github.com/EvanYu800112/dm_2018Fall_Lab2/archive/master.zip)

---
#### Libraries requirements
Here is a list of the new required python libraries necessary for this lab session:   
`tensorflow`, `keras`, `gensim`, `scikit-learn`    


#### Pre-trained model requirements

`GoogleNews-vectors-negative300.bin.gz`: [download link](https://drive.google.com/file/d/0B7XkCwpI5KDYNlNUTTlSS21pQmM/edit?usp=sharing)  
The data size is around 1.5GB, download it and put in `./GoogleNews/` directory. You **do NOT need** to decompress it.

---

#### Test script
Open a Jupyter notebook and run the following commands. If you have properly installed all the necessary libraries you should see no error.

``` python3 
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import itertools
import warnings
import sklearn
import gensim
import tensorflow
import keras
```

---
#### Preview of Complete Jupyter Notebook
* part 1  
https://nbviewer.jupyter.org/github/EvanYu800112/dm_2018Fall_Lab2/blob/master/Lab02_part1.ipynb
* part 2    
https://nbviewer.jupyter.org/github/EvanYu800112/dm_2018Fall_Lab2/blob/master/Lab02_part2.ipynb

---
#### Kaggle kernel version Jupyter Notebook
* part 1  
https://www.kaggle.com/evanyu800112/dm-2018fall-lab2-part1?scriptVersionId=7078126

* part 2   
https://www.kaggle.com/evanyu800112/dm-2018fall-lab2-p2?scriptVersionId=7081200 


---
#### References
* Deep Learning for NLP Python Notebooks in PyTorch and TensorFlow:    
https://github.com/omarsar/nlp_pytorch_tensorflow_notebooks

 
* Data Mining Lab Session 2 (Fall 2017):   
https://github.com/omarsar/data_mining_lab_fall_2



