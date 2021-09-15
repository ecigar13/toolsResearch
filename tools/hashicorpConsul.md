# HashiCorp Consul (Kubernetes)

### What is it?
A service mesh tool, similar to Istio and Linkerd

### Pros
- Service discovery, not simply a proxy mesh.
- Less resource usage per pod compared to Istio
- Handles VM + Kubernetes

### Cons
- Manage high availability of leaders and followers

### Compared to similar tools
To Istio: this' a more complex solution, adding service-discovery function, but requires a separate server. Not simply a proxy.