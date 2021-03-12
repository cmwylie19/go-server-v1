# go-server-v1

## Generate Manifests for demo profile of istio operator 
```
istioctl manifest generate --set profile=demo --set vlues.gateways.istio-ingressgateway.sds.enabled=true > generated-manifest-demo-profile.yaml
```

## Istio profile dump 

```
istioctl profile dump demo > profile_demo_config.yaml
```