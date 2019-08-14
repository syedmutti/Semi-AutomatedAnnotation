# Semi-AutomatedAnnotation

This Repository contains extension of Tensorflow Object Detection API for semi-automated annotation.
The network of choice needs to be trained on desired classes.
Output is xml files for corresponding images.
Additional functionality of skipping updation of exiting xml annotation files with "verified flag".


Usage: change returned parameters as per this script in vis_util.visualize_boxes_and_labels_on_image_array()
