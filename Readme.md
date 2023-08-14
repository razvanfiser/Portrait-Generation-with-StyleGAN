# Generating Portraits with the WikiArt Dataset and StyleGAN
## About this Project
This is a subset I built based on the [WikiArt Dataset from the Internet Archive website](https://archive.org/details/wikiart-dataset) in order to generate unique portraits using the StyleGAN technology. For the training part I used this [StyleGAN Google Collab Notebook](https://colab.research.google.com/github/dvschultz/stylegan2-ada-pytorch/blob/main/SG2_ADA_PyTorch.ipynb). The subset is built as such that it contains portraits coresponding to three art styles:

* Impressionism
* Post-Impressionism
* Expressionism

Additionally, all of the images are reduced to a square (512x512) format in order to be properly fed to the StyleGAN model, such that the typical image in the dataset looks somewhat like this:

![Alt Text](/Portraits_dataset/Impressionism/5132.jpg)

As you can see all the non-square images have been reflected on two sides in order to conform to the (512x512) image-size standard that I have chose for this projects.

## Results
Below are some results that I have selected after running the StyleGAN for a couple of hours per day for three days in a row:

![Alt Text](Results\compil_2.jpg)

## How to Run this Project
This project contains the file <code>Portraits_StyleGAN.ipynb</code> which can pe pulled and ran and editted in order to produce your own subset of the WikiArt dataset (provided that you have downloaded the data from the link above).