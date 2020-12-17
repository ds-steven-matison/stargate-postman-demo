# stargate-postman-demo
 A Postman demonstration of all of the Rest, Document, and GraphQL API Calls in Stargate Documentation.

 Check out my [Stargate](https://ds-steven-matison.github.io/stargate/) blog.

This collection and environment is tested against stargate docker:

```
docker pull stargateio/stargate-3_11:v1.0.0
docker run --name stargate \
  -p 8080:8080 \
  -p 8081:8081 \
  -p 8082:8082 \
  -p 127.0.0.1:9042:9042 \
  -d \
  -e CLUSTER_NAME=stargate \
  -e CLUSTER_VERSION=3.11 \
  -e DEVELOPER_MODE=true \
  stargateio/stargate-3_11:1.0.0
```

# Get Postman
- https://www.postman.com/downloads/

# Stargate Documentation
- https://stargate.io/docs