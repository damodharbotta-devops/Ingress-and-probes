# Ingress-and-probes

### Command to install Ingress:
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.11.0/deploy/static/provider/cloud/deploy.yaml

**Website Url** : https://www.google.com/search?q=Install+ingress+commands&oq=Install+ingress+commands&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIHCAEQIRigATIHCAIQIRiPAjIHCAMQIRiPAtIBCTE4NTMwajBqN6gCALACAA&sourceid=chrome&ie=UTF-8



## **Commands:**

kubectl create -f .
kubectl apply -f .

kubectl get ing

kubectl create -f one.yml
kubectl create -f tw0.yml
kubectl create -f three.yml

kubectl get deploy
kubectl get svc
kubectl get po
kubectl get ing


kubectl create -f probes.yml
kubectl get po
kubectl exec -it liveness -- bash
ls tmp/

rm -rf tmp/flm
ctrl+c --> exit

