# SEM Layer decetion

## Use Case:
Automatically detect SEM cross section layer for plotting or further SEM image processing.

## Model:
Use YOLOv4, train the model with SEM cross-section images with layers. Pre-trained weights is saved as yolov4-custom_best.weights in model folder.
It's trained on only one class (Layer), but can be generalized for multiple useages since the weights is obtained by training the COCO dataset.

## Example:
### original SEM cross section image:
![origin]

[origin]: https://github.com/tkm22/SEM-Layer-Detection/blob/master/data/test/CS-MA-FA.jpg
  



### SEM cross section image with layer detection:
![SEM]

[SEM]: https://github.com/tkm22/SEM-Layer-Detection/blob/master/data/test/CS-MA-FA-bbox.jpg


### Recreation notebook.
To use the Layer Detection, see Example.ipynb, which can be opened using Colab.

Example: https://github.com/tkm22/SEM-Layer-Detection/blob/master/Example.ipynb




 
