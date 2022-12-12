## Implementation

This plugin will add the component below in the OAM file informed through the
inputs:

```yaml
    - name: runtimes-microservice
      type: runtimes-microservice.microservice.x.y.z
      properties:
        image: my-image
        clusterOidc: "123456789"
        accountId: "123456789"
```