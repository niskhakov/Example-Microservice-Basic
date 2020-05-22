## Requirements

1. minikube
2. skaffold

## Initial Steps

1. Run `minikube start`
2. Get minikube ip from `minikube ip`
3. Add line `<minikube ip> posts.com` to /etc/hosts
4. Clone this repo
5. Go to the project root directory
6. Run `skaffold dev`
7. Go to `http://posts.com`
