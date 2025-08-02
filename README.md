# echolink-proxy
echolink-proxy docker container

Full docker container: https://hub.docker.com/r/rlucier/echolink-proxy

light weight: https://hub.docker.com/r/rlucier/echolink-proxy-tiny

Ralph KA7VEE

setup ==

docker run -d -p 8100:8100/tcp -v /data/:/home/echolink / docker://docker.io/rlucier/echolink-proxy:latest<br>
ELProxy.conf file is missing...<br>
Creating basic ELProxy.conf file to home directory<br>
EchoLink Proxy version 1.2.3<br>
Listening for connections on port 8100<br>
Ready for new client connection.<br>
[ctrl] + [c]<br>
cd ./data<br>
vi ELProxy.conf<br>
update:<br>
Password=P@ssw0rd <<-- update<br>

CallsignsAllowed= <<-- update if wanted<br>
like CallsignsAllowed=callsign1|calsign2 ....<br>
