docker build -t war-sample .

docker run -it -p 7070:8080 --name war-sample war-sample

http://localhost:7070/hello-world/
