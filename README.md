# openstack-devstack

    $ sudo apt update
    $ sudo apt upgrade -y
    $ sudo apt-get update
    $ sudo apt-get upgrade -y
    $ sudo apt update
    $ sudo apt upgrade -y
    $ sudo apt-get update
    $ sudo apt-get upgrade -y
    $ sudo useradd -s /bin/bash -d /opt/stack -m stack
    $ sudo chmod +x /opt/stack
    $ echo "stack ALL=(ALL) NOPASSWD: ALL" | sudo tee /etc/sudoers.d/stack
    $ sudo su - stack #
    $ sudo apt install git -y
    $ git clone https://opendev.org/openstack/devstack 
    $ cd devstack
    $ cp ./samples/local.conf local.conf
    $ sudo vim local.conf
    
    # HOST_IP=IPADDRESS
    # Modify Password
    $ ./stack.sh
    # IPADDRESS/dashboard
