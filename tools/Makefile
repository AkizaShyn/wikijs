start:
	$(DOCKER_COMMAND) up -d --pull always
stop:
	$(DOCKER_COMMAND) down
remove:
	$(DOCKER_COMMAND) down -v
build:
	$(DOCKER_COMMAND) build
command:
	@echo $(DOCKER_COMMAND)
pull:
	$(DOCKER_COMMAND) pull
logs:
	$(DOCKER_COMMAND) logs -f --tail=100