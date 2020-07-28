
Analysis of SIIM-ISIC Melanoma Classification Metadata and Images
Introduction
The Competition

Skin cancer is common cancer type and despite beign mostly non malignant, due to high case numbers it's pretty serious diasease and can lead serious cases if not detected, treated in time. It's usually diagnosed by eye for primarily and followed by further clinical analysis if needed. Even though the rares outcome is called melanoma it's the most deadly one, so early detection is pretty important. For this task using computer aided diagnosis might be helpful for primarily steps and early detections. Better detection might save thousands of lives.

This competition might help reaching that goal and I hope it can help people around the world...
Updates:
23/07/2020:

    Added adversarial validation,
    Updated metadata by removing biased features,
    Created simplier machine learning model.

25/07/2020:

    Added deep learning part
    Included EfficientNet modelling
    Ensembled metadata and EffNet predictions

About the Notebook

First of all this is pretty early version of this notebook, I decided to start part by part before I fully commit my submission, so for now this notebook covers such as:

    EDA of the metadata,
    Extracting basic image attributes like image size, colors etc.
    Creating new features from existing data,
    Design a machine learning model by using these simple features
    Make predictions using our model and tabular data
    Deep learning part will be added in future...

I think using metadata for understanding the problem is really important and plus side is we can use it to improve our scores, for now we only going to use tabular data for submissions. This way we can see it's power and it can help us with future CNN modelling. This notebook going to try answer questions like these:

    How's the data looking?
    Do we have complete dataset?
    How's the target distribution looking? Is it balanced?
    What are the effects of scan site on outcome?
    Does age effects skin lesion type?
    Is there difference between female and male patients in terms of target?
    How many unique patient data we have and how many scans they had? Is it important?
    Is image quality, colors, size have meaningful impact on the outcome?
    Can we see similar observations when we analyse both train and test dataset, if not why?
    And much more...

