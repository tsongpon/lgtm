# Docker Compose for LGMT stack

LGMT Stack with Opentelemetry collector

## Inside The Stack

 - otel-collector to collect Opentelemetry data
 - prometheus to store the application metric
 - tempo to store application tracing
 - loki to store application log

## Run

    git clone https://github.com/tsongpon/lgtm.git
    cd lgtm
    docker-compose -f monitoring.yml up

Opentelemetry collector listen on port `4317` and `4318`

Grafana dashboard available on `localhost:3000`

Grafana default username: `admin` password: `admin`