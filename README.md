## Tracking Emerges by Colorizing Videos
#### Vondrick, C., Shrivastava, A., Fathi, A., Guadarrama, S., & Murphy, K. (2018). arXiv preprint arXiv:1806.09594.

Tracking specific objects in the image is a very important skill, but it is quite difficult to make artificial intelligence visually track objects.
Because collecting the large-scale tracking datasets necessary for high performance often requires extensive effort that is impractical and expensive.

###### This paper constrain the colorization model to solve this task by learning to copy colors from a reference frame.

##### Self-supervised Learning

![fig1](https://github.com/Oh-Yoojin/Tracking-Emerges-by-Colorizing-Videos/blob/master/pictures/fig1.png)

It is video colorization as a self-supervised learning problem for visual tracking.
Instead of trying to predict the color directly from the grayscale frame, It constrain the colorization model to solve this task by learning to copy colors from a reference frame.

![fig2](https://github.com/Oh-Yoojin/Tracking-Emerges-by-Colorizing-Videos/blob/master/pictures/fig2.png)

![model](https://github.com/Oh-Yoojin/Tracking-Emerges-by-Colorizing-Videos/blob/master/pictures/model.png)
