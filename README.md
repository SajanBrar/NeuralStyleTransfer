# NeuralStyleTransfer
Neural Style Transfer to create paintings in style of a different artist.

Official Documentation:
https://www.tensorflow.org/tutorials/generative/style_transfer

In the code below, I am taking two of my favourite paintings and using deep learning and tensorflow to visualise how one of them can be made in the style of the other.

The two paintings taken here are:
1. 'The Starry Night' by Vincent van Gogh (1889)
2. 'Girl With A Pearl Earring' by Johannes Vermeer (1665)

The model can be used to adapt an existing work to resemble original aesthetic of any artist as required in the assignment.

### Pros:


*   The above model is simple to understand and easy to implement. (Guidelines for implementation can be easily found on the official TensorFlow tutorials website.)  
*   The model works quite well for most selection of images and/or paintings with minimal computational cost. (The selection of a work and the frequency of signature artefacts in it, highly affect the quality of the images.)



### Cons:


*   This model produces a lot of high frequency artifacts, as is clear in the above demonstration where the 'Starry Night Spirals' appear with too high frequency in the resultant image.
*   Some bounding components of the content image can be lost completely, such as the half ear and cheek bone boundary of the 'Girl with a Pearl Earring' in the above demonstration.
