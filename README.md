## Tensorflow 2.0 Tutorials

**Note**: None of these tutorials are my own, they are available on [Tensorflow](https://www.tensorflow.org/tutorials/). The goal of this repository is to replicate these tutorials in a dockerized environment for educational purposes.

Any additions made to the content will be indicated within the corresponding notebooks.

## Getting Started

All tutorials are availble within a simple docker container environment. Assuming you have [`docker`](https://docs.docker.com/get-docker/) and [`docker-compose`](https://docs.docker.com/compose/install/) installed, you can start up the jupyter notebook server by running `docker-compose up` within this project directory. Note there is only a single service built on the `jupyter/tensorflow-notebook:latest` image called `tf-jupyter`, this is meant to be starting point/reference guide to a more complex tech stack.

In your browser, navigate to `localhost:8888` and you should see the familiar jupyter notebook interface.