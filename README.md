git clone https://github.com/Carvin-Yu/fastapi-observability.git

helm upgrade -n dev fastapi-observability fastapi-observability/ -f fastapi-observability/values.yaml --install --force

watch kubectl get all -n dev

https://likeadmin.osdl.cloud:32767

helm uninstall -n dev fastapi-observability
