#Dataset: Sixray > Yolo_data_640
classes = ['Gun', 'Knife', 'Pliers', 'Scissors', 'Wrench'] 
images = 8312
https://universe.roboflow.com/siewchinyip-outlook-my/sixray


About Yolo

Ultralytics YOLOv8 is a cutting-edge, state-of-the-art (SOTA) model that builds upon the success of previous YOLO versions and introduces new features and improvements to further boost performance and flexibility. YOLOv8 is designed to be fast, accurate, and easy to use, making it an excellent choice for a wide range of object detection and tracking, instance segmentation, image classification and pose estimation tasks.

This is a custom trained yolov8 model that uses the SIXray dataset which contains an imbalance 
in the positive and negative samples making it the ideal choice for real time detection.
How ever the purpose of this implementation is to test the newly created YOLOv8 CNN model.
--------------------------------------------------------------------------------------------------------------------
by manipulating the following parameters: 
	- batch size
	- epochs
	- optimizers 
	- image size 
And comparing the results across multiple iterations and noticing the improvement. 

To manipulate the parameters you can check the args.yaml file in the args folder.

To manipulate the data and add preprocessing or integrate it with a transformer.
	then check the .ipynb (google colab) and .py file if you want to do the job on your pc.  

#This is some detaild info about the datset in json format


    "info": {
        "year": "2023",
        "version": "4",
        "description": "Exported from roboflow.ai",
        "contributor": "",
        "url": "https://public.roboflow.ai/object-detection/undefined",
        "date_created": "2023-02-07T13:41:12+00:00"
    },
    "licenses": [
        {
            "id": 1,
            "url": "https://creativecommons.org/licenses/by/4.0/",
            "name": "CC BY 4.0"
        }
    ],
    "categories": [
        {
            "id": 0,
            "name": "TIP",
            "supercategory": "none"
        },
        {
            "id": 1,
            "name": "Gun",
            "supercategory": "TIP"
        },
        {
            "id": 2,
            "name": "Knife",
            "supercategory": "TIP"
        },
        {
            "id": 3,
            "name": "Pliers",
            "supercategory": "TIP"
        },
        {
            "id": 4,
            "name": "Scissors",
            "supercategory": "TIP"
        },
        {
            "id": 5,
            "name": "Wrench",
            "supercategory": "TIP"
        }
    ],







![image](https://github.com/abdelrahmanKhaled2014199/Yolov8_sixRayDetection/assets/154362798/ac75b218-6c1a-42ca-9169-7912d69390ee)


Access the results folder to see the evaluation metrics and predicted output detections for each iteration





