# vagrant-docker-ucp

 ansible-playbook /vagrant/ansible/swarm.yml -i /vagrant/ansible/hosts/swarm
 
 
 swarm-master:
 
 docker run --rm -it -v /var/run/docker.sock:/var/run/docker.sock --name ucp docker/ucp install -i --swarm-port 3376 --host-address  192.168.57.90
