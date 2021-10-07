SHELL=/bin/bash

.PHONY: up
up:
	docker-compose up -d --build

.PHONY: down
down:
	docker-compose down

.PHONY: destroy
destroy:
	@make down
	docker rmi mailcatcher_php

.PHONY: open_mailcatcher
open_mailcatcher:
	open http://localhost:1080


.PHONY: open_web
open_web:
	open http://localhost:8080
