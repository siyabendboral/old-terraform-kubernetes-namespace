# usage 
### Please copy paste below code
``` 
module  namespace {
    source = "siyabendboral/namespace/kubernetes"
}
```
module testns {
    source = "siyabendboral/namespace/kubernetes"
    name = "testns"
    annotations = {
        new = "application"
    }
    labels = {
        createdby = "siyabendboral"
    }
}