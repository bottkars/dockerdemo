# dockerdemo
this is a basic demoifile for docker swarm demo on azurestack.

notes to myself:  

rdp to jumphost  
install-script install-gitscm  
ssh into swarmmaster (c`n`p pubkey)  

git clone https://github.com/bottkars/dockerdemo.git  
cd dockerdemo  
export DOCKER_HOST=10.0.0.5:2375  
docker compose up -d  
