# Face emotion recognition using Azure ML studio y Azure Cognitive Service
First we need to create a resource group and a ML workspace in Azure ML, then in Azure ML we create a compute process the standard cpu VM.
![Images](Images/1.png)\
\
Now we create a notebook to put our code and consume the API.

![Images](Images/2.png)\
\
In the python notebook we write our code .

![Images](Images/3.png)\
\
We need to create a new resource, the Face API, standard cration.
 
![Images](Images/4.png)\
\
We create it and confirm the resource

![Images](Images/5.png)\
\
Now we will need to go to keys in Face API

and copy the 1st key and the endpoint, then paste it in the python code.

![Images](Images/6.png)\
\
Finally we search a picture and paste the url in the code, and run it, and we have the face emotion recognition.

![Images](Images/7.png)