
# Brigade simple hello_world test

Install brigade
```
helm upgrade -i --set rbac.enabled=true brigade brigade
```


Install project 
```
helm upgrade -i -f brigade-test.yaml --set github.token=<oath_token> brigade-test brigade/brigade-project
```
