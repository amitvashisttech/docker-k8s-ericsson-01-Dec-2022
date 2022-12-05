```
  481  kubectl  get pods
  482  kubectl  delete -f 06-Service/
  483  kubectl get pods
  484  kubectl  get ns
  485  kubectl  get pod -A
  486  ls
  487  cd 07-NameSpaces/
  488  ls
  489  cat 01-Namespace.yaml
  490  kubectl  apply -f 01-Namespace.yaml
  491  kubectl  get ns
  492  ls
  493  kubectl get pods
  494  kubectl run hello-k8s-2 --image=nginx --port=80
  495  kubectl run hello-k8s-2 --image=nginx --port=80 -n myspace
  496  kubectl get pods
  497  kubectl get pods -A
  498  vim 02-Deployment.yaml
  499  kubectl apply -f 02-Deployment.yaml
  500  kubectl  get deploy
  501  kubectl  get deploy -n myspace
  502  kubectl  get deploy,pods  -n myspace
  503  kubectl get pods -A
  504  kubectl  delete -f 01-Namespace.yaml
  505  kubectl  get ns
  506  kubectl get pods -A
  507  kubectl  get ns
```
