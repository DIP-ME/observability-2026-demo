Commands Used:

docker build -t observability-demo:1.0 .
docker run -d --name observability-demo   -p 8080:8080   observability-1:demo
http://localhost:8080/metrics
docker pull prom/prometheus
docker images | grep prometheus
docker run -d --name prometheus -p 9090:9090 prom/prometheus
http://localhost:9090
