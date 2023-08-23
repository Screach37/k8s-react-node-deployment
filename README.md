# k8s-react-node-deployment
A simple React JS frontend with Node JS backend deployed on Kubernetes.

Docker cmnds used -

docker build -t sharmaakshat37/frontendimg:latest .
docker build -t sharmaakshat37/backendimg:latest .

Kubernetes cmnds used -

• minikube start --driver=vmware
• kubectl apply -f .\frontEndDeploy.yml
• kubectl apply -f .\backEndDeploy.yml
• kubectl apply -f .\frontEndSvc.yml
• kubectl apply -f .\backEndSvc.yml
