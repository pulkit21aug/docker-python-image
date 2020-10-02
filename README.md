# docker-python-image
Docker Image for  data science projects - python libraries 

This docker image is for data scientists  who are looking to run 
their code on AWS Fargate or AWS ECS or some other service using containers.
This image is ready to be deployed and execute any machine learning or deep learning code.
Image has pre-installed python runtime along with common libraries which I use for machine learning 
and deep learning. Have also included libraries for managing video content like splitting video files.

Looking forward for others to try this image and contribute , If you want any other libraries feel free to add
and check in the github repo https://github.com/pulkit21aug/docker-python-image.git



#Build the container and install

For build the docker image locally
docker build --tag dev:data-science .

Once the build is successful , install the container
docker run -it --name data_science dev:data-science 

or for detached mode
docker run -dit --name data_science dev:data-science 





