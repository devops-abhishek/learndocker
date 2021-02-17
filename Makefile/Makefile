build: ## build docker image
	docker build --build-arg PARENT_IMAGE=${PARENT_IMAGE}  -t ${DOCKER_IMAGE}:latest .

push: ## push docker image
	docker image push ${DOCKER_IMAGE}.latest

.EXPORT_ALL_VARIABLES:
DOCKER_IMAGE       ?=  achordia/sample-ubuntu
PARENT_IMAGE       ?=  ubuntu
