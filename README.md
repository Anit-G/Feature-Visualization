# Feature-Visualization

## NST or Neural Style Transfer
This implementation is an imporved implementation over the provided Pytroch Implmentaion and follows a closer approach to the problem\
as stated in the orginial research paper.

"
The principal is simple: we define two distances, one for the content(Dc: it measures how different the content is btw the two images) and one for the style(Ds: measures how different the style is btw the two images). Then, we take a third image, the input, and transform it to minimize both its content-distance with the content-image and its style-distance with the style-image.
"

Along with the implementaion of the NST I have also defined function for feature visualization particularly Feature visualization through Optimization and Feature Visualization using Hooks on the training Neural Network. In an attempt to better understand what the layers are learning as well as what features the CNN of the imported VGG19 is capable of extracting with respect to the depth of the network.
