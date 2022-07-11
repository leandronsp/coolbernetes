apps.setup:
	@kubectl apply -f apps/postgres/

apps.psql:
	@kubectl exec -it statefulset/postgres-pod -- psql -U postgres

apps.destroy:
	@kubectl delete -f apps/postgres/
