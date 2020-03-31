VERSION=$(shell git rev-parse --abbrev-ref HEAD)
IMAGE=digiklausur/k8s-hub

#release: VERSION=$(shell  git tag -l --points-at HEAD)

build:
	docker build -t $(IMAGE):$(VERSION) .

#push:
#	docker push $(IMAGE):$(VERSION)

#release: build push

