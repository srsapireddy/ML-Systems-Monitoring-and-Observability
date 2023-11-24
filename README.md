# ML-Systems-Monitoring-and-Observability

## Monitoring metrics with Prometheus
We need monitoring of the model because:
1. Data Changes
2. Continuous model monitoring after deployment (changes in variables, distributions, and decrease in performance)
3. Model performance monitoring (model input and distribution monitoring)
4. Data checks in shadow mode (variable distribution in training and live data)

![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/f816adc6-d88d-44a0-ae4b-460fce13c905)

## Difference between testing and monitoring
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/da491290-424e-404a-bbd7-e2f26c3df0d9)
A system's observability is the degree to which it can be debugged. </br>
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/2cf3c6f2-9229-4bc8-8df1-4029f9cb1496)

## Components of monitoring systems:
Key aspects of Alerting: </br>
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/9f399d11-d830-4eb8-926e-8e753614b259)
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/ba2344a9-0286-4719-8b33-17fff2439f68)

## Key Monitoring Principles for ML: After Deployment
1. Monitor Model Predictions: check for skew, bias, staleness, and other quality indicators
2. Computational Performance: Monitor system training speed, serving latency

## Metrics for ML Systems
### Pros
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/a7cb9dcc-96be-4ffa-bc9a-57e5321f7066)
### Cons
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/b0a62254-1d59-4f53-891d-3db89cbdedf7)
### ML Metrics
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/6b716f6f-d58e-4b3d-b391-1690e05e97e6)

## Understanding Prometheus and Grafana
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/15c15a4a-f8a3-4069-b1fb-0e0cf7253bc1)
### Metrics in Prometheus
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/acb68d02-db2d-4e9e-bb01-c8c7dcd563dc)
### PromQL Query Language
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/2c3ed26b-6548-4413-869c-958fcdbe2af3)

### Lab Commands
```
docker-compose up -d --build
docker ps
```

### Docker Containers Running
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/764eac29-64a4-4931-8b3e-cbd12b129e4c)
### Flask Application
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/bb0c3f5a-6828-4eb7-bfb0-e783b9bc44cb)
### Metrics EndPoint
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/6d493388-4b69-4af6-8482-fc015d0d6f28)
### Prometheus Expression Browser
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/23c488e9-6637-429c-bb45-8c52aa0a0fae)

## Checking Prometheus Metrics
### Checking for counter metric
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/8c81d9ed-05bc-48f1-9f5d-50b10fac7eaa)
### Querying on labels (Filtering on just the endpoints)
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/bb641cfd-a2af-43ce-a683-a17cef862538)
### Aggregating request counts on HTTP requests
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/d45387a6-e9fa-4cca-968a-e1e22d19478e)
### Calculating time spent on endpoints
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/48d52864-e48d-4030-a8e0-c033bd48262b)
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/f8bb0c35-601c-40d7-8dc9-8cffd4408114)
This is the total amount of time spent on these different endpoints </br>
### Calculating the latency (Average latency over the last minute)'
![image](https://github.com/srsapireddy/ML-Systems-Monitoring-and-Observability/assets/32967087/16a8594c-fe70-4246-9f67-5b247bc81c86)



















