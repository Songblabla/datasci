.PHONY: run docker_build down clean

run:
	docker-compose -f docker-compose.yaml up

down:
	docker-compose -f docker-compose.yaml down

docker_build:
	docker-compose -f docker-compose.yaml build

clean:
	docker-compose -f docker-compose.yaml down --rmi all --volumes --remove-orphans

logs:
	docker-compose -f docker-compose.yaml logs -f

restart:
	docker-compose -f docker-compose.yaml restart

ps:
	docker-compose -f docker-compose.yaml ps

rebuild: clean docker_build run
