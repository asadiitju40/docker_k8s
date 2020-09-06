Creating image from dockerfile:
	docker build -t my-python-app -f Dockerfile .
For initialize a container:
	docker run --name python-app -p 5000:5000 my-python-app
to restart the container:
	docker start container_ID
