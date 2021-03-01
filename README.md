# modified-yolov4
This repository holds the trained models and results for our modified YOLOv4 architectre. The training is done using the official [DarkNet repository](https://github.com/AlexeyAB/darknet.git) on VisDrone train portion of the dataset and training files are present in training_code folder. The trained weights for original and modified YOLOv4 architecture are available on [Google Drive](https://drive.google.com/drive/folders/1ETRmejbZnB2BFs-ksw286VY0CHI5dCBt?usp=sharing). The modified YOLOv4 architecture is shown in the below figure.
<p align="center">
  <img width="600" height="550" src="https://github.com/sharoseali/modified-yolov4/blob/main/yolo_paper_image_Modified.png">
</p>


## Testing
The testing is carried out using the official [VisDrone DET Toolkit](https://github.com/VisDrone/VisDrone2018-DET-toolkit.git) on VisDrone Test-Dev dataset. Detection files are generated using darknet_images.py file and resultant detection  files are in the folders det_files_modified_yolov4 and det_files_original_yolov4. These detection files are passed into VisDrone DET Toolkit to get mAP results shown in the below figure.
<p align="center">
  <img width="500" height="320" src="https://github.com/sharoseali/modified-yolov4/blob/main/final_results.png">
</p>
