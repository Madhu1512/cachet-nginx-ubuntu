TAG = 2.3.10
IMAGE_NAME = Madhu1512/cachet-nginx-ubuntu

build:
	docker build -t ${IMAGE_NAME} .
	docker tag ${IMAGE_NAME}:latest ${IMAGE_NAME}:${TAG}

push:
	docker push ${IMAGE_NAME}:${TAG}
