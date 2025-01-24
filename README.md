# ShortThirdMan Docker Base Images


```shell
docker build -f Dockerfile-jdk17-otel --platform linux/amd64 --progress=auto --compress --rm -t shortthirdman/catos-base-java:1.0-jdk17-otel .

docker build -f Dockerfile-jdk17 --platform linux/amd64 --progress=auto --compress --rm -t shortthirdman/catos-base-java:1.0-jdk17 .

docker build -f Dockerfile-jdk21-otel --platform linux/amd64 --progress=auto --compress --rm -t shortthirdman/catos-base-java:1.0-jdk21-otel .

docker build -f Dockerfile-jdk21 --platform linux/amd64 --progress=auto --compress --rm -t shortthirdman/catos-base-java:1.0-jdk21 .
```