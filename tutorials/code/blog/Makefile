## Builds main Dockerfile
build: 
	docker build -f ../../../Dockerfile.alpine -t vlang:alpine .
## Up services web and database
up:
	docker-compose up -d

## Starts only database service
database:
	docker-compose up -d database
