# Weechat

## Source
https://weechat.org/

## K8s it
```
kubectl create secret generic weechat --from-literal=relay-password='<SUP@@h$3cRe7>'
kubectl apply -f weechat-pvc.yml weechat.yml weechat-ingress.yml
```


