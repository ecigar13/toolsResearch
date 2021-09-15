# Istio (Kubernetes)

### What is it?
Layer 7 TCP proxy (service mesh). Instead of kube-proxy for all pods, it'a sidecar container in every pod. Exposes pod using an Envoy service. It wasn't possible back in the day because lack of container, container management technology. But now, it's possible.

### Pros
- Centralize service-to-service communication, so app team doesn't need to code it.
- Interceps traffic at the pod level
- Can collect finer data for monitoring

### Cons
- Speed: adding one more layer of proxy. 
- Adding many proxies.
- Only works with service architecture
- Consumes pod resources to run.

### Compared to similar tools
Replacement for kube-proxy. More fine-grained control. 