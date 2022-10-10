# zeroconnectapi
[![Artifact Hub](https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/zeroconnect)](https://artifacthub.io/packages/search?repo=zeroconnect)
```
Helm chart for zeroconnect api
helm repo add zeroconnect https://magikon.github.io/zeroconnectapi/charts/stable/
helm install my-zeroconnectapi zeroconnect/zeroconnectapi --version 1.9.0 --set secretsName={SECRET_NAME} --set ingress.certificateARN='{CERT_ARN}' --set image.tag={IMAGE_TAG}
```
