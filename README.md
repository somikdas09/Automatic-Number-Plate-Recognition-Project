Automatic number Plate Recognition System

Things that we have added apart from just number plate reading

1. Colour Recognition 
2. Prediction of the Speed and Direction
3. Prediction of the size 

Steps that are followed to do the above activities:-

1. Read Input Video Frame by Frame with OpenCV
2. The frame is sent to TensorFlow Object Detection API
      Detected Vehicle Image is Sent for 
         a.Colour Recognition which is done using k-Nearest Neighbour Algorithm
         b.Prediction of the size using Image Area
      
      Detection Vehicle Image Location is sent for\
         a.Prediction of the Speed and Direction which is done using Pixel Loaction
         

Steps being followed to build the Number Plate Reading System

1. Setup of the Path
2. Download the Tensor Flow Pretrained Models from the Tensor Flow Model Zoo
3. Install the Tensor Flow Object Detection
4. Create a Label Map
5. Create TF Records
6. Copy Model Config to Training Folder
7. Update the Config for Transfer Learning
8. Train the Model
9. Evaluate the Model
10. Load Train Model from Check Point
11. Load Train Model from Check points
12. Detect from an Image
13. Apply OCR to Detection
14. OCR Filtering
15. Real Time Detections from your Webcam
16. Conversion to TFJS
17. Zip and Export Models

Dependencies and Documents to be Prepared

Open CV
Ipy kernel (virtual environment)
Jupyter Notebooks
Wget (data retriever)
Tensorflow 2.4.1 
TensorflowGPU 2.4.1
Protobuf
Matplotlib 3.2
Pillow
Pyyaml
Pytz(for timezone)
Easy OCR
Pytorch
TFJS(tensorflowJS)


