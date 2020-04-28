# dockerfiles-ubuntu-user-adderable
FROM ubuntu
add: net-tools,curl,tree

# Building & Running

Copy the sources to your docker host and build the container, and to run.
```
	docker build --rm -t sennes2/ubuntu .
	docker run -it --name u1 sennes2/ubuntu
```
