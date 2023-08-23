# k8s-react-node-deployment
A simple React JS frontend with Node JS backend deployed on Kubernetes.


Docker cmnds used - <br/>
Dockerfiles in /backend and /frontend
docker build -t sharmaakshat37/frontendimg:latest . <br/>
docker build -t sharmaakshat37/backendimg:latest . <br/>

Kubernetes cmnds used -
<br/>
• minikube start --driver=vmware <br/>
• kubectl apply -f .\frontEndDeploy.yml <br/>
• kubectl apply -f .\backEndDeploy.yml <br/>
• kubectl apply -f .\frontEndSvc.yml <br/>
• kubectl apply -f .\backEndSvc.yml <br/>
