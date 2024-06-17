## Week 1
### Day 1

List all contexts
```
kubectl config get-contexts
```

Get names of all contexts
```
kubectl config get-contexts -o name
```

Write all context names into /opt/course/1/contexts
```
kubectl config get-contexts -o name > /opt/course/1/contexts
```
