#To deloy container use following command. Where "--ulimit" will be use to increase file limit on container
docker run -d --ulimit nofile=4124:4124 -p 80:80 -p 443:443   --name haproxy cadent-haproxy
