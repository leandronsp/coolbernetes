monitoring.setup:
	@bash monitoring/setup

monitoring.prometheus:
	@kubectl -n monitoring port-forward deploy/prometheus-pod 9090:9090

monitoring.grafana:
	@kubectl -n monitoring port-forward statefulset/grafana-pod 3000:3000

monitoring.kube-state-metrics:
	@kubectl -n kube-system port-forward deploy/kube-state-metrics-pod 8080:8080

monitoring.destroy:
	@kubectl delete -f monitoring/namespace.yml
