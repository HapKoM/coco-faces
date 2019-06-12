# coco-faces
Three files train2017.txt, val2017.txt and test2017.txt contain face labels for [COCO 2017](http://cocodataset.org) dataset.

Each file contain lines in format "file x1 y1 x2 y2", where file is name of image in the specific COCO part, (x1, y1) upper-left corner of face rectangle, (x2, y2) - lower-right corner. All coordinates are presented as floating point numbers in range [0, 1], relative to width and height of the specific image.

All images are labeled with [RetinaFace detector](https://github.com/deepinsight/insightface/tree/master/RetinaFace) (RetinaFace-R50 currently).
