# Go-Repository 
RUN ON LOCALHOST
go run main.go

INITIALISE GO MODULE
go mod init hellogohttp/m/v2

DOCKER BUILD
docker build -t hello_go_http .

DOCKER RUN
docker run -p 8080:8080 -t hello_go_http

Your application will be running on localhost:8080/helloworld