# LICENSE PLATE DETECTION AND RECOGNITION

#### Introduction
Automatic License Plate Recognition technology has been popular due to its wide range of applications in intelligent transportation systems, traffic management, toll automation, journey time analysis, etc. Due to the variation in the background and font color, font style, size of the license plate, and non-standard characters, license plate recognition is a great challenge in many countries. To overcome such issues, this study applies a deep-learning strategy to improve license plate recognition efficiency. We hope to understand and utilize the computational photography concepts that aid in detecting and recognizing license plate numbers. We also intend to learn and implement supervised machine learning algorithms to achieve the stated outcomes.

#### Project Implementation 
We completed this project on Google Colab and hence the project directory structure is from the google drive.
#### Project Folder Description
 - root- CS445_FinalProject 
    - LicensePlateDataset 
    - Models 
    - Resnet_ANPDR.ipynb
    - YOLO_ANPDR.ipynb
    - CS445_Final_Project_Proposal.pdf
    - CS445_Final_Project_Report.pdf
- LicensePlateDataset 
    - images
       - Cars0.png
       - Cars1.png
       - ......
    - annotations
        - Cars0.xml
        - Cars1.xml
        - ...... 
    - test_images
        - car1_test.png
        - car2_test.png
        - ......
        - traffic_test.mp4
        - traffic_test_YOLO_results.avi
        - traffic_test_Resnet_results.avi
        - LicencePlateDetectionRecognition_Results.mp4 
- Models
    - object_detection_epoch500.h5
    - object_detection_epoch200.h5
    - ......
    - yolov5
        - runs/train/Model2

#### Running the project
- Download the zip file, unzip and upload the root directory on your google drive.
- The ipynb files for each of the model has description and comments of the flow and code.
- You can run the Resnet_ANPDR.ipynb cell by cell by connecting to the runtime to the GPU for training the model. To only check the results using the model, follow commands on the ipynb to load the saved model from the directory and use it on test data.
- You can do the same for YOLO_ANPDR.ipynb.

#### Results
Check a small video of our results here - https://vimeo.com/779004724
You can also find results of our experiments on the output cells of the colab notebooks and our report.

