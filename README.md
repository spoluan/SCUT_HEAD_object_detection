**Project Descriptions**

![alt](head_detection.png)

For this project, I will be implementing object detection using the SCUT-HEAD-Dataset. This dataset has two releases, A and B, which I will be combining to build my model. The dataset includes a large-scale head detection dataset, with a total of 4405 labeled images and 111251 heads. Part A contains 2000 images sampled from monitor videos of classrooms in a university, with 67321 heads annotated. Part B contains 2405 images crawled from the internet, with 43930 heads annotated. Each visible head is labeled with xmin, ymin, xmax, and ymax coordinates to ensure that the annotations cover the entire head, including the blocked parts but without extra background. Both Part A and Part B are divided into training and testing parts, following the standard of Pascal VOC.

The datasets can be found and downloaded from https://www.kaggle.com/datasets/fabozi/student-head.

To implement the object detection, I will be using the detecto library which is based on the popular PyTorch framework. detecto provides an easy-to-use interface for object detection and is based on the Faster R-CNN ResNet-50 FPN architecture. This makes it a powerful tool for detecting objects in images and is well suited for our project.