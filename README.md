# Text-Description-to-Image-Generation-using-GAN
The process of translating text into images has been a hot topic of study recently. Synthesizing 
photorealistic graphics from natural language text descriptions is a great advancement. Text to picture 
is a standardised approach of automatically creating images from text. The use of conditional 
generative models to automatically generate text has several potential benefits. The most significant 
challenges arise from translating visual and textual information. High-quality images can be generated 
from text using a generative adversarial network, however there are challenges associated with 
accurately portraying the content of the sentence provided to the model. Text-to-image conversion 
strategies can produce examples that closely reflect the descriptions' intended meaning. The provided 
descriptions, however, are lacking crucial details. For the purpose of creating the conditioned text 
descriptions, this study employs a Attention Generative Adversarial Network to generate 256*256-pixel 
images that are image-sensitive. In the initial phase, known as GAN sketches, the input text 
descriptions serve solely to inform the basic form and colour scheme of the devices. The information 
gleaned from the first stage, along with the textual descriptions, is fed into a generative adversarial 
network (GAN), which subsequently generates images with high resolution and realistic detail. Using 
conditioning augmentation, the conditional GAN training may be stabilised, and the generated 
samples can have higher quality. By using Style based Generator it is possible to make image 
transformation as the way you want to draw the sample for each style of images generated for the 
Attention GAN .By inputting textual descriptions of an object into a GUI or online app, photorealistic 
visuals of that object can be generated.


# # Text Description to Image Generation using Generative Adversarial Network 


----
## Description
This repository contains files related to my project on Text Description to Image Generation using Generative Adversarial Network .

----
## Dataset
CUB-200 Dataset has been used for the training of model.
   [CUB-200](https://www.kaggle.com/datasets/veeralakrishna/200-bird-species-with-11788-images)

## Requirements
* Python 3.7
* Tkinter
* Pandas
* Numpy
* Torchvision.transforms
* Anaconda prompt 



## Run Model in steps
---
$ python3 sampletexts.py
```
*Text feature Extraction*
--------------------------
```
$ python3 Global Attention.py
```
*Image Generation*
--------------------------
```
$ python3 DAMSM.py
```
*Identification for real/fake images *
-------------------------------------
```
$ python3 data.py
```
*Training & testing  the data*
--------------------------
```
$ python3 vocabulary.py
```
*Training of the Model*
--------------------------
```
$ python3 model.py
```
*Test model*
--------------------------
```
$ python3 gui.py

this gui is made using python Tkinter package 
```

## Testing The Model
 
to run gui write the command python guirun.py
```

*Test Results*
--------------
When you run the guirun.py using above command it will show you welcome screen and will ask you to give the text description.


# Conclusion:
In this project, I'm presenting an updated version of the neural network with information flow, called 
"Captioner," that is an integral part of the GAN architecture. Our network architecture may be 
thought of as a chain: text > picture > text, with the central idea being to use the restored 
original text as input to the network. We base our comparison of the existing StackGAN 
framework to our four different variant implementations. According to our tests, the Captioner 
module can generate images with more authentic expressions and preservations of primitive 
elements. To further enhance the image data quality, the embeddings are used in error 
calculation. Moreover, both synthesised image data and real picture data are useful for 
bolstering quality assurance.

# To run GUI
1) Open Anaconda Prompt

2) Copy and Paste the below command (use mouse  operation to copy and for paste right click)
This commmand is to move into the text to image gan conda environment

 				conda activate textimggan




3) Same copy and paste below command
This command is move into the project folder

			cd C:\Users\yegne\Desktop\TextImgGan\code


4) To Run with gui use below commandC

			python guirun.py
      
