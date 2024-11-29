Name:

Q1:
Create a deployment named nginx in the qq2 namespace using the nginx image with 3 replicas.


Q2:
Create a new deployment name lab-deployment in the qq2 namespace. With one replica in the manifest then scale the deployment to 4 replicas.

Q3:
Create a deployment names nginx-deployment in the qq3 namespace. Perform a update to the deployment by setting the image to nginx:alpine.

Q4:

Create a new deployemnt called Python in programming namespace use the following image:

python:3.9.20-slim-bullseye

Make sure the cloud system can access it using port 9797

Q:5
Create a pod named limit with two images one is  redis and another one is nginx in the qq3 namespace.

Q6:
Create a Deployment named web in the ca1 namespace with an image of nginx:latest. Create a new Service named web-svc that sits in front of this deployment.  All changes should be performed in the ca1 namespace. 



Q7:

Execute the following requirements in the prod namespace. Create a new Deployment named app01 using the nginx:latest container image and have it listen on port 80. The deployment should consist of 2 replicas. Create a new Service named app01-svc and expose the newly created deployment using a NodePort. Confirm that you can access the nginx home (index) page using the NodePort service.

Q8:
Create a new Deployment named cloud-app01 in the ca2 namespace consisting of 2 replicas. The deployment should use image nginx:1.23.3-alpine. Create a new Service resource named cloud-app-svc to expose the cloud-app01 deployment on port 80 in the same namespace. Finally use the following kubectl run command to spin up a utility pod which tests HTTP connectivity through the new service. Confirm that the following command returns an HTTP 200 response code:

kubectl run -n ca2 -i --tty --restart=Never --rm netutil --image cloudacademydevops/networkutils:v2 -- curl -I cloud-app-svc

Q9:
Create a deployment named class using httpd:alpine3.20
image configured with the following settings:

use the proper service type and service to expose it for ports 443 and 80



Q10:
Create a deployment names busybox with an image of busybox:uclibc in the namespace busybox

Show the output and logs for the adminstrator to see

Q11:

Create a deployment names db in the database namespace which uses mysql:oraclelinux9. All teh enviromental variable must be set and the deployment myst be fully operational


Q12:
Deploy a pod named nginx using the nginx image in the qq3 namespace with Create a service related to this pod which is going to expose the pod with port 80 just within the Kubernetes

Q13:

Show the nodes associated with the current deployment of Kubernetes in your machine.

Q14:

Create a deployment names nginx-deployment in the qq3 namespace. change the image to nginx:alpine and apply the change.

Q15:
Create a new deployment name apache-deployment with an image of caleed httpd:latest

 in the qq3 namespace. Change the image to httpd:bookworm and then print the change.


Q16:
Deploy  postgres by using Deployment with the following image:

https://hub.docker.com/_/postgres





Q17:

Then use elastio/pgadmin to create a database and change for the previous question

https://hub.docker.com/r/elestio/pgadmin



