# object-detection

A Pen created on CodePen.

Original URL: [https://codepen.io/icecoffie/pen/dPyvQwZ](https://codepen.io/icecoffie/pen/dPyvQwZ).

This demo shows how we can use a pre made machine learning solution to recognize objects (yes, more than one at a time!) on any image you wish to present to it. Even better, not only do we know that the image contains an object, but we can also get the co-ordinates of the bounding box for each object it finds, which allows you to highlight the found object in the image. 

For this demo we are loading a model using the ImageNet-SSD architecture, to recognize 90 common objects it has already been taught to find from the COCO dataset.

If what you want to recognize is in that list of things it knows about (for example a cat, dog, etc), this may be useful to you as is in your own projects, or just to experiment with Machine Learning in the browser and get familiar with the possibilities of machine learning. 

If you are feeling particularly confident you can check out our GitHub documentation (https://github.com/tensorflow/tfjs-models/tree/master/coco-ssd) which goes into much more detail for customizing various parameters to tailor performance to your needs.