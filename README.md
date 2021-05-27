# marvelcharacters


Marvel_k8s 
 This repo has the direct k8s files where we have to run the following to test it.
 
 kubectl create -f stable-deployment-service.yaml
 
 kubectl create -f beta-deployment-service.yaml
 
 kubectl create -f hpa-stable.yaml
 
 kubectl create -f hpa-canary.yaml
 
 kubectl create -f ingress-stable.yaml
 
 kubectl create -f ingress-canary.yaml
 
 Now map the domain in your /etc/hosts and run it on the browser, For every 10 runs it make a call to beta app.
