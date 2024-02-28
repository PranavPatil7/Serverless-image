# Image Classification Tutorial - TensorFlow Serverless!
This tutorial uses Tensorflow image classification feature using TensorFlow JS. It uses Serverless environment by leveraging the [Serverless](https://serverless.com/) framework.

**Serverless TensorFlow Architecture**
![serverless_architecture](https://github.com/PranavPatil7/Serverless-image/assets/30521517/5b7b746c-ea78-4158-b6ad-bbc32560a6e1)




Image recognition process using the MobileNet model in serverless cloud functions. 

 ## Setup and Install

 **TensorFlow REST API - Runs in Serverless Environment**
 - Node js 8 & above required!
 - Download and install/update the Serverless framework in your machine. Refer this Serverless doc link for installation help - https://serverless.com/framework/docs/getting-started/
  
 - clone the project 
   > git clone git@github.com:RaghavPrabhu/Deep-Learning.git 

 - cd Deep-Learning/serverless_image_tensorflow/

 - export AWS_ACCESS_KEY_ID=<YOUR AWS ACCESS KEY>
 - export AWS_SECRET_ACCESS_KEY=<YOUR AWS SECRET KEY>

 - npm install
 
 - sls deploy

 **TensorFlow Frontend UI Deployment** 
 - Go to the folder "frontend_client"
 - npm install
 - Open the config/default.json file and update the API URL
 - Run the command - node server.js
 - Open the browser and enter the URL - http://localhost
 - You will see the below screen 
 
 - UI Home Screen
![home_screen](https://github.com/PranavPatil7/Serverless-image/assets/30521517/d19b149b-3d66-4ee5-b26d-6a9b2dabfbc1)
    

 - UI Input Screen
![upload_screen](https://github.com/PranavPatil7/Serverless-image/assets/30521517/c5b082fb-465e-4a83-82f3-ec6b561849f9)
![output_screen](https://github.com/PranavPatil7/Serverless-image/assets/30521517/2bd15f60-18f7-4602-ac41-60840c4f2f2a)   


 - UI Output Screen
 ![Tensorflow Image Output Screen](https://github.com/RaghavPrabhu/Deep-Learning/blob/master/serverless_image_tensorflow/img/output_screen.png)  

 ## Done.
  
  
 
