# Multi-container-management
Multi container  based application management from docker compose. This is efective way of automating and managginggg multiple containers 
for the app to running all time available and scalable.  please take below steps ive made it.

Project Aim: netflix app consist of login form of diffferent genre( such as movies, web series  etc) as micoservices using docker technology we containerize and deploy this services/containers on single aws ec2 server.

1) install docker and verify version of it.
2) create docker file 
3) build images for each of genre such as movies, webseries , animations and documentaries.
   
   docker build -t movies:v1 .

   

5) install docker compose and neccessary commmands

![image](https://github.com/user-attachments/assets/e1437103-06e0-4636-ae99-fed5bfa46b47)


6) start docker compose, and verify ur containers names as service

   

![image](https://github.com/user-attachments/assets/356e4077-0e3a-4a05-9b07-60b43b7f4860)


   
 [ u can  try with each of genre during build process.  ]

  
  ![image](https://github.com/user-attachments/assets/2daff7ab-bcf7-40ca-9d16-6c4608c2525f)







  o/p 
  1. movies container service running on 91 port number 

  ![image](https://github.com/user-attachments/assets/30f5e91d-51c4-46fe-b991-9c327034c9d8)




2.animations container service running on 92 port number 

![image](https://github.com/user-attachments/assets/203d76d1-fb0a-46fe-9cc8-5b2483110f10)





<< Congrats! succesfully Automatically managed and deployed  multi containers on aws servers >>




     
