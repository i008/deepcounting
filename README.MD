### Idea

The question is simple, what happens if we generate images with some kind of objects on them (circles for example) and train 
a CNN giving it only the count of the objects as the target variable. Will it learn to count? will it learn to segment properly?  
The biggest challange of the image-generation part is to avoid data-leakage  for example the network fitting to the total-area of the foreground instead of the object count.
