# Despliegues servidor TeamSpeak 3

**Despliegue en docker**
```console
docker compose up
```

**Despliegue en Kubernetes**

```console
cd kube-manifests
```
```console
k apply -k .
```