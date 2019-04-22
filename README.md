This Dockerfile will implement CBI's modifications to the [official MRIQC distribution](https://github.com/poldracklab/mriqc).

It takes the poldracklab/mriqc docker image as Base Image, and modifies a python function using "sed"

To build the docker image, run:

```
docker build -t cbi_mriqc .
```

To pull the official cbinyu/mriqc docker image:

```
docker pull cbinyu/mriqc:latest
```
