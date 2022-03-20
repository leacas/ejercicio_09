# ejercicio_09

Los pasos necesarios para desplegar el bot de telegram en Kubernetes son:

Para crear este Deployment, ejecuta el siguiente comando:
 <pre>$ kubectl create -f deployment.yaml</pre>
   
Para validar el deployment creado:
 <pre>$ kubectl get deployments telegram-bot-api-deployment
$ kubectl describe deployment telegram-bot-api-deployment</pre>

Para validar el estado del pod:
 <pre>$ kubectl get pods</pre>
