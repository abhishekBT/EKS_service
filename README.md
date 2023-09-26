# EKS_service
Deploying Application in AWS EKS cluster

## Order to Deploy game-2048 application in eks service
Install and setup the Prerequisites
 ```
   Follow prerequisites.md file 
 ```
Create EKS cluster using fargate (serverless)

 ```
   Follow installing-eks.md
 ```
Then to deploy the application game-2048
 ```
   Follow 2048-app-deploy-ingress.md 
 ```
The above deployment have done deployment, service and ingress and to allow user to access the application need to use ingress-controller
### as using farget need to configure oidc-connector 
 ```
   Follow steps in configure-oidc-connector.md
   ```
### Follow to steps for aws alb as ingress controller
```
Follow alb-controller-add-on.md
```
