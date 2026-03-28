# Creating New Sea Animals Using a Generative Adversarial Network (GAN)

## This GAN was used for my final for CS312 - AI & Machine Learning

#### My goal of this project was to create new realistic images of sea animals using a downloaded dataset from Kaggle that contains 13000+ images of sea animals and a GAN model. I initally tried to use the entire dataset inside the model, but the buffer time was way too long. So I still included that code for organizing the entire dataset into the model, but for mine specifically I only loaded one animal subtype. 

## ML methods 
#### I trained a Generative Adversarial Network model to take in real images and create spoof images based off of them. I fed the model, a resized 128 x 128 grayscale image of real sea animals and had it reproduce the same using a generated image.

## Limitations
#### The first limitation I ran into was that the epoch length was nowhere near the length needed for accurate sea animal image replication. And my current hardware specifications limited the speed of training for the GAN. 

## Data Source
#### https://www.kaggle.com/datasets/vencerlanz09/sea-animals-image-dataste
