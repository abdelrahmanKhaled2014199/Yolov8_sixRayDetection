#Dataset: Sixray > Yolo_data_640
classes = ['Gun', 'Knife', 'Pliers', 'Scissors', 'Wrench'] 
images = 8312
https://universe.roboflow.com/siewchinyip-outlook-my/sixray


This is a custom trained yolov8 model that uses the SIXray dataset which contains an imbalance 
in the positive and negative samples making it the ideal choice for real time detection.
How ever the purpose of this implementation is to test the newly created YOLOv8 CNN model.

by manipulating the following parameters: 
	- batch size
	- epochs
	- optimizers 
	- image size 
And comparing the results across multiple iterations and noticing the improvement. 

To manipulate the parameters you can check the args.yaml file in the args folder 
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


![image](https://github.com/abdelrahmanKhaled2014199/Yolov8_sixRayDetection/assets/154362798/b67768ce-5e1c-4e0c-875a-9b3ee5df3382)

This is a details architecture link containing the layers: https://ibb.co/xgQwKKV 

The following images is the results that we acuired at the third iteration (30 epochs)
![confusionMatrix](https://github.com/abdelrahmanKhaled2014199/Yolov8_sixRayDetection/assets/154362798/3b113e4f-5030-4b09-8ca5-b75afe051709)
![evaluation materices](https://github.com/abdelrahmanKhaled2014199/Yolov8_sixRayDetection/assets/154362798/1280e70a-bc87-4831-8abf-03de86f37c40)
![F1_Curve](https://github.com/abdelrahmanKhaled2014199/Yolov8_sixRayDetection/assets/154362798/56203cc7-71b5-4c8c-9995-1de546eb0326)
![PR_Curve](https://github.com/abdelrahmanKhaled2014199/Yolov8_sixRayDetection/assets/154362798/2b52aabd-6790-40f2-89af-13cf432740e3)
![P_Curve](https://github.com/abdelrahmanKhaled2014199/Yolov8_sixRayDetection/assets/154362798/beb576ea-3e33-48ec-baa0-caff10b35888)


The following images is the detection results on some input images after the model have been trained  

![Screenshot_4](https://github.com/abdelrahmanKhaled2014199/Yolov8_sixRayDetection/assets/154362798/f23cfbee-874d-46e5-a67c-d1b6ac040614)
![Screenshot_3](https://github.com/abdelrahmanKhaled2014199/Yolov8_sixRayDetection/assets/154362798/1256006e-1f9b-4717-ac74-186badf508e3)
![Screenshot_2](https://github.com/abdelrahmanKhaled2014199/Yolov8_sixRayDetection/assets/154362798/2094715e-376a-400d-bfbd-98ffd383e7b8)
![Screenshot_1](https://github.com/abdelrahmanKhaled2014199/Yolov8_sixRayDetection/assets/154362798/4c77c66c-96f2-41c5-acc6-c53898ecd43d)






