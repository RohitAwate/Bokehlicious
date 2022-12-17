# Bokehlicious: : Shallow Depth of Field for Images using Portrait Segmentation and Depth Estimation

We present a method for using portrait segmentation and depth estimation
from monocular images to create a shallow depth of field in images, resulting in
a bokeh effect. This is widely known as portrait mode in modern smartphone
cameras. This technique allows for more artistic control over the focus of an
image, producing a more pleasing visual aesthetic. A combination of deep learning
techniques and image processing is applied to recreate images with a progressive
bokeh. The method is demonstrated through experimentation and comparison to
traditional techniques to recreate the effect using simpler model architectures. It
emulates the effect of a large aperture and/or focal length from bigger cameras and
lenses while blurring the background elements for aesthetic value as well as better
separation between the subject and the background. We propose an approach that
uses deep learning to perform segmentation for isolating the subject and a depth
estimation model on the background elements to understand the relative distance
between them which is then used to apply a progressively stronger Gaussian blur.


