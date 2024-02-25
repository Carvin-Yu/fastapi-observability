git clone https://github.com/Carvin-Yu/fastapi-observability.git

helm upgrade -n dev fastapi-observability fastapi-observability/ -f fastapi-observability/value.yaml --install --force

watch kubectl get all -n dev

https://likeadmin.osdl.cloud:33334

helm uninstall -n dev fastapi-observability
