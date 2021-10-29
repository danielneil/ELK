# ELK

Simple instance of an ELK running on Rocky Linux. Uses Metricbeat to display the metrics of the localhost in Kibana. 

# Setup

1. Prepare a vanilla Rocky Linux (or a RHEL) Server instance with VirtualBox ([help](https://kifarunix.com/install-rocky-linux-8-on-virtualbox/)).

2. Install ansible ([help](https://www.how2shout.com/linux/how-to-install-ansible-on-rocky-linux-8-or-almalinux/)).

3. Install Git ([help](https://tastethelinux.com/2021/08/06/how-to-install-git-on-rocky-linux-8-ec2-aws/)).

4. Open a terminal, and run:
```
git clone https://github.com/danielneil/ELK.git && cd ELK && ./build.sh
```
5. Navigate to http://kibana-server-ip:5601.
