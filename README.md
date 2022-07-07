# signoz

kubectl apply -f https://raw.githubusercontent.com/SigNoz/charts/main/charts/clickhouse/crds/clickhouse-operator-install.yaml

helm upgrade --install signoz -n platform signoz/signoz -f values.yaml
