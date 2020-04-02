# NST_application_001


In this project, taken from the end of the Convolutional Neural Networks course from Coursera, taught by Andrew NG, we are going to implement the Neural Style Transfer algorithm. This algorithm was created by Gatys et al. (2015)
Most of the algorithms optimize a cost function to get a set of parameter values, while here we'll optimize a cost function to get pixel values!

We will merge two images: a "content" image (C) and a "style" image (S), to create a "generated" image (G). The generated image G will combines the "content" of the image C with the "style" of image S. In this example, we are going to generate an image of my birthcity, Acireale, located in the south of Italy, mixed with the famous painting by Vincent Van Gogh, Starry Night (style image S).
