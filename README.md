# practical_task5.1
Coding exercises made to practice the different CD for DevOps path
This is another way to deploy the Sock Shop locally on minikube, as a side note this doesn't work on Mac M1 

##Deploy sockshop locally

The first step is to clone the repo below and and go into the deploy/kubernetes folder.
´´´
git clone https://github.com/microservices-demo/microservices-demo
´´´

Create the namespace of the sockshop
´´´
kubectl create namespace sock-shop
´´´

Finally deploy the application
´´´
kubectl apply -f complete-demo.yaml
´´´
