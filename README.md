# JenkinsVagrant
Vagrantfile for quickly setting up CentOS with Jenkins

#Requirements:
- Virtualbox (tested on 6.1.28)
- Vagrant

#Modify these (if needed):
vb.name = "agent"
 -Virtualbox VM Name
config.vm.network "forwarded_port", guest: 8080, host: 8889, host_ip: "127.0.0.1"
 - Port Forwarding
