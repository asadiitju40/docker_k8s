Here host operating system is linux

download and keep the files into "python_http-req_ubuntu_img" directory and goto in it.
	cd python_http-req_ubuntu_img

Creating image from dockerfile:
	docker build -t simple_httpd:v1 -f Dockerfile .
For initialize a container:
	docker run --name simple_web -p 5000:5000 simple_httpd:v1
to restart the container:
	docker start container_ID
