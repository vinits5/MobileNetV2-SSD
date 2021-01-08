# MobileNetV2-SSD

#### Create Dataset
1. Keep both the files in the same folder.
2. *mkdir data*
3. Run the code to create dataset.
4. Two files named *mnist_obj_detection_100_test.tfrecords* and *mnist_obj_detection_2000_train.tfrecords* will be created in data folder.

#### Training the SSD Network
1. Provide proper path for the dataset.
2. Run MobileNetV2-SSD.ipynb file.


#### References
1. Negative Hard Mining: [[Blog]](https://becominghuman.ai/tensorflow-object-detection-api-basics-of-detection-7b134d689c75), [[code]](https://github.com/ChunML/ssd-tf2/blob/master/losses.py)
2. TFRecord: [[Blog]](https://dzlab.github.io/dltips/en/tensorflow/tfrecord/)
3. Single Shot Detection: [[Blog]](https://jonathan-hui.medium.com/what-do-we-learn-from-single-shot-object-detectors-ssd-yolo-fpn-focal-loss-3888677c5f4d)