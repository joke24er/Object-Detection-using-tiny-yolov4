# Object-Detection-using-tiny-yolov4
Object detection task of items present on a shelf in a shopping mart.
Initally it was supposed to be trained with a transfering pretrained weights of CNN architecture like VGG,resnet,inception by having an output fc layer with 4 outputs ie. regression of 4 points for the bounding box looking at only one class of objects. Since there can be muliple objects in the same image the previous idea was scrapped and it was decided to go after an advanced object detection methodology. With the help of darknet repo the training was done with Yolo weights.
colab link: https://colab.research.google.com/drive/1UWWh8PZle7icfU_cg7lgVUV6sFjywQOP?usp=sharing
