# Docker_commads

docker build - < Dockerfile




gcloud auth application-default login


gcloud config set project PROJECT_ID

gcloud init


gcloud components install kubectl
kubectl cluster-info
kubectl cluster-info dump
gcloud components install kubectl
gcloud container clusters create hello-cluster --num-nodes=3
gcloud compute instances list


installing docker

apt-get install curl
curl -sSL https://get.docker.com/ | sh


 sudo apt install openjdk-8-jdk
 
 sudo vim /etc/profile.d/java.sh
 
 export JAVA_HOME=/usr/bin/java
export PATH=$PATH:$JAVA_HOME/bin


Docker commands

sudo usermod -a -G docker $USER

docker build -t gcp_app .

docker images

docker build -t tmaheshreddy/gcp_app:ver2 .

docker push tmaheshreddy/gcp_app:ver1


maven install

sudo apt install maven
