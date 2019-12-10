# Image_Captioning

Description
===========
This is project Image Captioning developed by team Learning Machine composed of Teng Ma, Shengzhe Zhang, Huaijin Wang, Yuchen Tang. Image captioning is a process of generating descriptive captions for given images. In our project, we will implement Image Captioning by the following process: First feed the image into a CNN, then use a RNN to leverage the images and their description sentences to learn latent relationsamong visual data and natural language. Our project is inspired by two papers, *Show and Tell and Show, Attend and Tell.*

Requirements
============
Code organization:<br/> 
1.create_input_data.py<br/>
2.get_train_log.ipynb<br/>
3.image_caption.ipynb<br/>
4.evaluate.ipynb<br/>
5.eval_sample.ipynb<br/>

-- Run a demo of our code (reproduces Figure 3 of our report) -- Run the training of our model (as described in Section 2) -- Run the adversarial attack as described in Section 3.<br/>

**models.py**: contains encoders,decoders with attention and decoders without attention.<br/>
**solvers.py**: contains train, validate, backprop, clip_grad, save_checkpoint...functions<br/>
**create_input_data.py**: script used to fetch the MS COCO datasets.<br/>
**train_script.py**: script used to train our model.


