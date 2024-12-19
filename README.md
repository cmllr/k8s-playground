|Befehl|Beschreibung|
|--|--|
|kubectl get deployment/ pod/ service/ volume|Listet Elemente auf
|kubectl describe pod|Gibt Eigenschaften und Probleme des pod Objekts aus
|kubectl apply –f xy.yaml|Erzeugt die Objekte, die in xy.yaml definiert sind ODER aktualisiert diese
|kubectl create –f xy.yaml|Erzeugt die Objekte, die in xy.yaml definiert
|kubectl delete –f xy.xaml|Löscht alle Objekte, die in xy.yaml definiert sind
|kubectl delete deployment harald-schmidt|Löscht das Deployment „harald-schmidt“
|kubectl get xy –o yaml|Liefert die YAML-Definition für xy

# VS Code Plugin 

https://marketplace.visualstudio.com/items?itemName=ms-kubernetes-tools.vscode-kubernetes-tools


# Kubectl 

https://kubernetes.io/releases/download/#binaries

Linux/ Unix:  `chmod +x ./kubectl`

`kubectl config use-context docker-desktop`

`kubectl cluster-info`