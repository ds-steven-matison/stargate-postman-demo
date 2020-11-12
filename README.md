# stargate-postman-demo
 A demonstration of all of the Rest, Document, and GraphQL API Calls in Stargate Documentation

This collection and environment is tested against stargate docker:

```
docker pull stargateio/stargate-3_11:v0.0.8
docker run --name stargate \
  -p 8080:8080 \
  -p 8081:8081 \
  -p 8082:8082 \
  -p 127.0.0.1:9042:9042 \
  -d \
  -e CLUSTER_NAME=stargate \
  -e CLUSTER_VERSION=3.11 \
  -e DEVELOPER_MODE=true \
  stargateio/stargate-3_11:v0.0.8
```

# Get Postman
- https://www.postman.com/downloads/

# Stargate Documentation
- https://stargate.io/docs/stargate/0.1/quickstart/quickstart.html