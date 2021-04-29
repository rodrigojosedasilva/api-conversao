```sh
docker image build -t rjds/api-conversao:v1 .
docker image tag rjds/api-conversao:v1 rjds/api-conversao:latest
docker run -d -p 8081:8080 rjds/api-conversao:v1 
```