# docker_example_node_app

docker build -t node-web-app .

docker run --rm -it -p 8080:8080 -v ~/projects/docker_example_node_app:/usr/src/app node-web-app
