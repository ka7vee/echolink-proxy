# echolink-proxy
echolink-proxy docker container

Full docker container: https://hub.docker.com/r/rlucier/echolink-proxy

light weight: https://hub.docker.com/r/rlucier/echolink-proxy-tiny

Ralph KA7VEE

setup ==

docker run -d -p 8100:8100/tcp -v /data/:/home/echolink / docker://docker.io/rlucier/echolink-proxy:latest<br>
ELProxy.conf file is missing...
Creating basic ELProxy.conf file to home directory
EchoLink Proxy version 1.2.3
Listening for connections on port 8100
Ready for new client connection.
[ctrl] + [c]
cd ./data
vi ELProxy.conf
update:
Password=P@ssw0rd <<-- update

CallsignsAllowed= <<-- update if wanted
like CallsignsAllowed=callsign1|calsign2 ....
