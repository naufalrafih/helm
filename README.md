# helm
Deploy kubernetes using Helm <br>
Step by step:

1. Create new Helm chart <br>
```helm create mychart```

2. Edit values.yaml

3. Deploy Helm chart <br>
```helm install release-name mychart/ --values mychart/values.yaml```

4. To stop: <br>
```helm uninstall release-name```
