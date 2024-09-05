# longcompose
EN.553.689 course project

# Problem Setting
Compositional Image Retrieval with long text description. 

## Description
Composed Image Retrieval (CIR) is the problem of finding the correct target image given a sample image with a text query that describes a certain change to it.  For ex: Given an image of a dog and the query "playing with a red ball", the model should retrieve the correct image where a dog is playing with a red ball. 

In this project we try to address CIR, where the text query is not a short text, but a longer description. 

## Datasets and Compute
Exisiting datasets for CIR are CIRCO, CIRR and GeneCIS. These can be refined for longCompose. 

Exisiting CIR models can be used with a single GPU with 40GB memory. There are exisiting methods that train the model using a single GPU as well. 