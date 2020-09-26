EKG-Kubernetes AKS
Solucion para el despliegue de la solucion archivo por archivo numerado

kubectl apply -f #file -n elk

despues del paso 6 

ejecutamos 
kubectl exec -ti sample-elasticsearch-0 bash 

Ingresamos y ejecutamos el siguiente comando 

bin/elasticsearch-setup-passwords interactive

Con este seteamos las contraseñas que van a ser utilizadas como configuracion de comunicacion y demas y continuamos con el proceso de instalacion