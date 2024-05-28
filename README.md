# marathon-bib-detector

Racing Bib Number (RBN) detection and recognition contain the interesting tasks of both finding the location of bib attached to a person in a natural scene & then inferring the text detection on the bib itself. To break these tasks down further, text recognition requires training steps, including finding the area of the bib on a person and then inferring the numbers on the bib. This project uses the research & experience from prior implementations to apply a working Convoltuional Neural Network (CNN) to detect race bib numbers in images.

This repo investigates the use of Convolutional Neural Networks (CNN) and specifically, NVIDIA's cuDNN & Darknet's You Only Look Once ver. 4 (YOLOv4), to detect Racing Bib Numbers (RBNR) in a natural image scene. Leveraging publically available & labeled datasets from previous research (please see reference section below for addt'l information), I achieve a mean average precision (mAP) on the following:
<br>
99% mAP on Race Bib Detection in Natural Scene dataset training
<br>
Dataset Link : https://people.csail.mit.edu/talidekel/RBNR.html

<br>

Also the use of Tesseract ocr can be used to detect the image number after yolo model has cropped the bib

to install , run all the documents one after the other , else upload the files in the G-drive dir/../bib-project
and upload the dataset in RBNR upload the yolo model and test and train model 

