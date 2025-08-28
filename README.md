TASK-5: Kubernetes NGINX Dashboard Deployment

This project deploys a customized NGINX web dashboard to a Kubernetes cluster using a single manifest file ([app.yml](app.yml)). The dashboard features updated HTML content and styles, served via NGINX, and exposed using a NodePort service.
Contents

app.yml: Kubernetes manifest containing:
  - ConfigMap with custom HTML (`index.html`)
  comments for creating kind cluster:
curl -Lo kind-windows-amd64.exe https://kind.sigs.k8s.io/dl/v0.26.0/kind-windows-amd64
Move-Item .\kind-windows-amd64.exe C:\Windows\System32\kind.exe -- admin 
kind --version
kind create cluster --name xops-cluster
screenshots:
<img width="991" height="496" alt="image" src="https://github.com/user-attachments/assets/a7f5202a-ed91-4162-a21a-7a9713f92683" />

    
