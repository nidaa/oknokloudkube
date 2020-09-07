# flask-k8s-app
to deploy flask python okno app in k8s
 you need to change the following

1) you need to change IP Address of nodeport in  okno-app-service

2) run the following commands
1-  sudo kubectl create -f  okno-app.yaml
2-  sudo kubectl create -f  okno-app-service.yaml
