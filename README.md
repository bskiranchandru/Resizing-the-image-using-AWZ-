# Resizing-the-image-using-AWZ-
 Serverless Computing with AWS Lambda main part is to resize the image
We used the AWS lambda Platform to work on all 4 tasks. 
Site:-Qwiklabs 
Aim:- Main work on this week to make the resize the image from the original one. 
TASK 1:- Here we need to create the bucket to insert and check the the resized image  
Name original-bucket as name:- pes2ug19cs186 
Resized-bucket name-pes2ug19cs186-resized 
TASK2 :- UPLOAD THE IMAGE TO THE BUCKET AND CREATE THE LAMDA FUNCTION  
I am uploading the HappyFace.jpg file to orinal bucket that should be in proper format 
there  need to create the_ Thumbnail floder and add a trigger to s3 buket. And select python 3.7 language 
We edited the Runtime setting and genral configuration: 
Handler:- CreateThumbnail.handler 
Description:- Create a thumbnail-sized image 
 
TASK3:- TEST THE FUNCTION:- 
Here we need to change the name our file  
Name:-pes2ug19cs186(bucket name) Key:- HappyFace.jpg arn:-arn:aws:s3:::pes2ug19cs186 
after the execution We can check the rezised folder  
The original file is 128kb that reduced to 2.6kb 

TASK4 :-MONITORING AND LOGGING 
We need to lamda file in that path we need to open log stream file to view the stream result . 
 the final result:- 128kb image to 2.6 kb image
 and the second mointoring file thriugh graph is :-Duration graph:- 9min wth 1.04kmsec 
Invocations:-1 in 9min 
Thorttle:-9min 
There is no Asyc delivery failures 
Error count:-0.5 % 
Success rate:- 99.5% 
