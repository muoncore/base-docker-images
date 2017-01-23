
docker:
	docker build . -t simplicityitself-muon-image.jfrog.io/node:7

docker-release: docker
	docker tag simplicityitself-muon-image.jfrog.io/node:7 simplicityitself-muon-image.jfrog.io/node
	docker push simplicityitself-muon-image.jfrog.io/node
