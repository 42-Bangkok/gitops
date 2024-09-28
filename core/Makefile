recreate:
	docker compose up -d --force-recreate
logs:
	docker compose logs -f --tail=100
migrate-cadet:
	docker compose exec cadet node migrate.mjs
