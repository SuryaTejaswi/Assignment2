# Assignment2
Aim:
Deploy Ngnix on web servers and haproxy to loadbalance the client requests successfully and 
serve a simple web page deployed on web servers through load-balancer depending upon the balance 
Procedure:
1.Deploy ngnix servers on the trageted hosts and required php pakages too and haproxy on the host as load balancer.
2.Configure the Haproxy and ngnix and restart servers.
3.Configure a bastion server with assh_config file.
4.Restart servers and run the command
  ansible-playbook -i hosts site.yaml
