# Cloud-E-Thon
This is a web application used to store the image in AWS S3 bucket which is captured from a webcam.

Here, To open the web application do the following steps:
1. Choose the python IDE of your choice
2. Add files app.py, create_data.py and face_recognize.py
3. To generate the dataset open create_data.py and follow the following steps:
    1.In the subdir write the name of yours -> This will create the folder of the name you have given and store the images which are captured while running this file
4. Then to verify that the face is recognized or not after creating the dataset run face_recognize.py
5. After that run app.py and go to the link in the output
6. There you can do the same things create a dataset and then recognize it after that if recognized than it will directly go to the recognized folder of cloudethon bucket which is been created in AWS S3 bucket service
7. If not recognized than it will be stored in non-recognized folder of cloudethon S3 bucket.
