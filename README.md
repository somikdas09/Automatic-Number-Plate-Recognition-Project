Team Name: MARCOS

PSID: INTL-IVA-01

ANPR IN HIGH SPEED AND HEAVY TRAFFIC

Automatic Number-Plate Recognition is a technology that uses optical character recognition on images to read vehicle registration plates to create vehicle location data. Through the use of high speed image capture with supporting illumination, detection of characters within the images provides, verification of the character sequence as being those from vehicle license plate, character recognition to convert image to text; so ending up with a set of data that identifies an image containing a vehicle license plate and the associated text of that plate. ANPR system captures vehicle registration plates, both during day and night. It includes a digital image capture unit, an infrared lighting, a processing unit and different algorithms. ANPR provides an easy solution for measuring section-related traffic data. It also provides safety information system for road workers, also helps with crimes related vehicles or traffic.
Our aim: Our aim is to build an ANPR software that would work accurately even for high speed & heavy traffic. So here we have come up with a solution.
Outline steps:- 1.Installation & Setup->2.Input Reading with Open CV->3.TFOD-API->4.Image Capturing->5.Image segmentation->6.Cutting License Plate data->7.Training a OD model->8.Detecting license plate ->9.Applying Easy-OCR to text->10.Creating ROI  (region of interest) ->11.Data displayed & stored.

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


