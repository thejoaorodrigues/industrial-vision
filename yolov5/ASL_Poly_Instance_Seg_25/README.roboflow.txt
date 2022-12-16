
HHN-Components - v6 2022-12-16 12:46pm
==============================

This dataset was exported via roboflow.com on December 16, 2022 at 12:49 PM GMT

Roboflow is an end-to-end computer vision platform that helps you
* collaborate with your team on computer vision projects
* collect & organize images
* understand unstructured image data
* annotate, and create datasets
* export, train, and deploy computer vision models
* use active learning to improve your dataset over time

It includes 717 images.
Industrial-Assembly-Components are annotated in YOLO v5 PyTorch format.

The following pre-processing was applied to each image:
* Auto-orientation of pixel data (with EXIF-orientation stripping)
* Resize to 640x640 (Stretch)

The following augmentation was applied to create 3 versions of each source image:
* 50% probability of horizontal flip
* 50% probability of vertical flip
* Randomly crop between 0 and 17 percent of the image
* Random rotation of between -11 and +11 degrees
* Random exposure adjustment of between -11 and +11 percent


