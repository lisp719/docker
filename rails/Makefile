.DEFAULT_GOAL := less

bash:
	docker-compose run app bash

init:
	docker-compose run app gem i rails
	docker-compose run app rails new . -d postgresql -m .docker/template.rb

less:
	less Makefile

setup:
	docker-compose run app ./bin/setup
