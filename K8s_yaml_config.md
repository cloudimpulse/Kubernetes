The YAML configuration file for any onject in K8s will have 4 important parts.
- apiVersion
- kind
- metadata
- spec

All these are specific to the kind of object going to be created.

K8s_deployment.yaml
```
apiVersion: apps/v1
kind: Deployment
metadata:
	name: nginx-deployment
	labels: ...
spec:
	replicas: 2
	selector: ...
	template: ...
```
K8s_service.yaml
```
apiVersion: v1
kind: Service
metadata:
	name: nginx-service
spec:
	selector:
	ports:
```
