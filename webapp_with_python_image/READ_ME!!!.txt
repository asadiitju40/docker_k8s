Here host operating system is linux

download and keep the files into "webapp_with_python_image" directory and goto in it.
	cd webapp_with_python_image
Creating image from dockerfile:
	docker build -t my-python-app -f Dockerfile .
For initialize a container:
	docker run --name python-app -p 5000:5000 my-python-app
to restart the container:
	docker start container_ID
