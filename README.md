# zeroconnectapi
Helm chart for zeroconnect api
helm repo add zeroconnect https://magikon.github.io/zeroconnectapi/charts/stable/
helm install my-zeroconnectapi zeroconnect/zeroconnectapi --version 1.9.0 --set secretsName={SECRET_NAME} --set ingress.certificateARN='{CERT_ARN}' --set image.tag={IMAGE_TAG}
