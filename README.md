# RetinaFace-for-Face-Detection

Retinaface is a single stage dense face detection model. This repo reproduces code available in [here](https://github.com/Linzaer/Ultra-Light-Fast-Generic-Face-Detector-1MB). Its a lightweight pretrained version of the model that uses ONNX and pytorch for the implementation. I also added the code to run the detector on video feed from webcam.

* Original paper is [here](https://arxiv.org/abs/1905.00641)
* A paper summary and explanation is available on my [Medium](https://medium.com/becoming-human/retinaface-face-detection-model-32a96abc12d1)
* excellant [resource](https://github.com/biubug6/Face-Detector-1MB-with-landmark)
* official code is [here](https://github.com/deepinsight/insightface)


## Paper Abstract
Though tremendous strides have been made in uncontrolled face detection, accurate and efficient face localisation in the wild remains an open challenge. This paper presents a robust single-stage face detector, named
RetinaFace, which performs pixel-wise face localisation
on various scales of faces by taking advantages of joint
extra-supervised and self-supervised multi-task learning.
Specifically, We make contributions in the following five
aspects: (1) We manually annotate five facial landmarks
on the WIDER FACE dataset and observe significant improvement in hard face detection with the assistance of
this extra supervision signal. (2) We further add a selfsupervised mesh decoder branch for predicting a pixel-wise
3D shape face information in parallel with the existing supervised branches. (3) On the WIDER FACE hard test set,
RetinaFace outperforms the state of the art average precision (AP) by 1.1% (achieving AP equal to 91.4%). (4)
On the IJB-C test set, RetinaFace enables state of the art
methods (ArcFace) to improve their results in face verification (TAR=89.59% for FAR=1e-6). (5) By employing light-weight backbone networks, RetinaFace can run
real-time on a single CPU core for a VGA-resolution image.
