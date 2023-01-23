# Autoscaling-Image-Recognition-System-on-Cloud
This project is part of the course Cloud Computing (CSE 546) at Arizona State University. The project was aimed at utilizing the IaaS resources offered by Amazon Web Services (AWS) to automatically scale the RESTful application based on the number of concurrent requests to classify images according to the deep learning model provided.

Autoscaling can be achieved by Elastic Load Balancer, but we were required to design our own autoscaling algorithm for this project. The autoscaling function launched Elastic Cloud Compute (EC2) virtual instances according to the requests in the Simple Queue Service (SQS), and terminated instances when the number of active requests in the SQS declined. The results of image recognition were stored in a Simple Storage Service (S3) bucket, along with the name of the image provided by the workload generator in the form of a request. 

The next stage of the project involved deploying the web tier with the autoscaling function on to a hybrid cloud environment using OpenStack services.

Since this project is part of coursework, the code and system design has been hidden. 
![arch_diag final](https://user-images.githubusercontent.com/74524978/214172685-60f0773b-648f-4df4-ac4a-dc8c76af98be.PNG)
