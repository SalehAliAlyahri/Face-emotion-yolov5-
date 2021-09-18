# Face-emotion-yolov5-
In this project, I used the Yolov5 object detection algorithm to detect a person's feelings through a face if he is happy, normal, or sad.  The steps of this project      First, I started collecting datasets from google, focused on three categories happy, sad, and normal and each category collected about 200 images.  Second, I uploaded the dataset to the Labelbox and then put a boundary box on all the image  Third: - I have exported the Jason file that contains the boundary box information then I uploaded it to roboflow so that I can convert the Jason file  to Yolov5 annotation format   Fourth: - I used this colab  https://colab.research.google.com/drive/1gDZ2xcTOgR39tGGs-EZ6i3RTs16wmzZQ to help me to train YOLOv5 on Custom Objects   fifth: - after I finished my train I saved my model and created a new  notebook to use my model by upload image or video or use Webcam  