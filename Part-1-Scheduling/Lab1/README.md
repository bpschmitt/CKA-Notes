# CKA-Notes

## Lab 1
```
k run web --image=nginx --labels="Tier=Web"
k run app --image=nginx --labels="Tier=App"
k get pods -l Tier=Web
k get pods -l Tier=App
```