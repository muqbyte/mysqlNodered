# mysqlNodered

Please follow the command below

1. sudo apt-get remove docker docker-engine docker.io
2. sudo apt-get update
3. sudo apt install docker.io
4. sudo snap install docker
5. sudo curl -L "https://github.com/docker/compose/releases/download/v2.27.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose #please change the version
6. mkdir mysqlNodered
7. cd mysqlNodered
8. touch docker-compose.yml
9. vi docker-compose.yml
10. press i to edit
11. press enter then type ":wq!" and press enter
12. docker-compose config
13. if everything is good, then the content in the file will print out
14. docker compose up -d
15. docker ps
