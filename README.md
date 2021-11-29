# DYOM_Computer_Vision
Design Your Own Module - Computer Vision/ Deep learning project

-- Note for DYOM Notebook-- 
If you are running the notebook submitted, do take note that it is best run on google colabs and that the training time can sometimes take hours. 
Do also note to change the directories and filepaths of the Dataset when using flow_from_directory, the filepath to save and load model, and the filepath to load an image of your choice.


-- Inference function Script in python(testcommandline.py)-- 

##Important note is that can only run in anaconda or virtual environment where python version is 3.6 or lower. Must have tensorflow libraries, PIL and opencv installed in environment.

## Instructions for using testcommandline.py 
-> Download testcommandline.py, model.json and model.h5 and make sure it is in the same directory as your working environment
-> testcommandline script depends on model.json and model.h5 to load the trained cnn model
-> Make sure you run CMD.exe prompt from within anaconda navigator with your environment of python <3.6 
-> Then search for the working directory of the env
-> In this instance, my working env is named weird 
-> finally execute python testcommandline.py with your image filepath as a string (eg is given below)

(weird) C:\Users\yaoz\anaconda3\envs\weird>python testcommandline.py "C:\Users\yaoz\anaconda3\envs\weird\doggo4.jpg" 

#Returns predicted object class and probabilities 
['Long Exposure', 'Hazy', 'Ethereal']
[0.62127835, 0.10036139, 0.07239037]   


--Submissions-- 

1)DYOM Assignment 2 Submission notebook.ipynb(best run in google colabs)
2)model.h5
3)model.json
4)testcommandline.py
5)Dataset.zip
6)README 
7)Second notebook** 

**Note: The second notebook is run on a different dataset using CIFAR-10 images that is of 32 x 32 pixels but features using an almost identical model architecture in the submission notebook
but the second notebook features an extremely high accuracy and optimal loss using the same model architecture compared to the submission notebook. And can generalize very well. 


