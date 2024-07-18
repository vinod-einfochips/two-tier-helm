## Build and Install helm chart 
1. Create Helm chart
```bash
helm create flask-app-chart
```
2. Build helm package
```bash
helm package flask-app-chart
```
3. Install and Run clusters
```bash
helm template flask-app-chart
helm install flask-app-chart ./flask-app-chart
```
4. Check all running podes and serivce 
```bash
kubectl get all 
```
5. Uninstall and Kill Cluster
```bash
helm uninstall flask-app-chart 
```
