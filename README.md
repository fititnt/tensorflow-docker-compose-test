# Tensorflow with docker-compose (test)

- Run `docker-compose up`.
- Access on your browser the URL that console will print out (something like
http://localhost:8888/?token=2fc9063261bd6ede0601a0cf9d0aa9c78711f03cb087691f)
- Press <kbd>Ctrl</kbd> + <kbd>C</kbd> to stop.

## Docker (no docker-compose)

`docker run -it -p 8888:8888 tensorflow/tensorflow`

## References

- https://www.tensorflow.org/serving/docker
- https://hub.docker.com/r/tensorflow/tensorflow/
- https://hub.docker.com/r/tensorflow/tensorflow/tags/
