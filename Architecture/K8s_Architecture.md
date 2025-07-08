# K8s Architecture
# K8s Components/Object
K8s has tons of components/objects but most of the times we would be using handful of them.
- Node
  - A physical or Virtual machine
- Pod
  - Smallest unit of K8s
  - Abstraction over containers
  - Recommended 1 app per pod  
- Services
- Ingres
- ConfigMaps
  - External configuration of your app, like DB URLs, DB UserIDs.
  - Dont keep credentials in configmaps instead use the K8s Secret.
- Volumes
  - K8s doesn't manage data persistance.
- Deployment
  - Deployments are for Stateless apps  
- Statefulsets
  - Satatefulsets are for Statefull apps like DBs.
