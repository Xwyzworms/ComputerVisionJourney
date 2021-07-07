## Image Processing
Image processing Levels : 
- Low-level Process , The output is Image : 
	- Noise Removal
	- Image Sharpening
	- Illumination Normalization
	- Perspective correction
- Mid-level Process, The output is number representation :
	- Rectangle point (x,y)
- High-level Process , The output is the **Final Process** :
	- Cat, Dog, Car, Object detection
	-  Face recognition
	-  Emotion Recognition

image-Formulation
Image can be described as **2D** function i.e ***(x, y)*** as the coordinates and the pixel can be described as ***f(x,y)*** :
- *x* $\epsilon$ [0, h-1]  where h is the height of the image
- *y* $\epsilon$ [0, w-1] where w is the width of the image
- *f(x, y)* $\epsilon$ [0, L-1] where L = 256 (8 bit image) 