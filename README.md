# lfw
In the first attempt, I used residual blocks for the embedding layer. As I started training it, I felt that the model is unnecessarily complex, and then moved to a simpler convnet. In this one, I have used contrastive loss to make the model map similar images close to each other and dissimilar ones farther apart. You can see from the loss trend that it is training better than the first one.

One major assumption made is that the face lies within a 180x180 crop of the original image. I arrived at this by looking at some random images, and then formally by plotting average image. 
