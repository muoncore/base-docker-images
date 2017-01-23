
docker:
	docker build . -t simplicityitself-muon-image.jfrog.io/ubuntu:yakkety

docker-release: docker
	docker tag simplicityitself-muon-image.jfrog.io/ubuntu:yakkety simplicityitself-muon-image.jfrog.io/ubuntu
	docker push simplicityitself-muon-image.jfrog.io/ubuntu
