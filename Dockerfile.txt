docker build -t syed-devops-app .
docker run -d -p 8080:80 --name syed-app syed-devops-app