   
Development
-----------

 # Clone linkfloyd repository to `~/htdocs/linkfloyd-php`
 
    git clone https://github.com/linkfloyd/linkfloyd-php.git ~/htdocs/linkfloyd-php
    
    OR
    
    git clone git@github.com:linkfloyd/linkfloyd-php.git ~/htdocs/linkfloyd-php

 # Set IP address for `lf.dev` on your hosts file. (/etc/hosts)
 
    192.168.56.102 lf.dev

 # Install vagrant >= 1.8 on your local
 
    wget https://releases.hashicorp.com/vagrant/1.8.5/vagrant_1.8.5_x86_64.deb -O vagrant.deb && sudo dpkg -i vagrant.deb && rm vagrant.deb

 # Install Vagrant plugin 
 
    vagrant plugin install vagrant-vbguest
 
 # Install ansible >= 2.0 on your local
 
    sudo pip install ansible
    
 # Clone this repository. (clone path doesnt matter)
 
    git clone https://github.com/linkfloyd/linkfloyd-ansible-provisioner.git
    
 # Run vagrant   
 
    cd linkfloyd-ansible-provisioner
    
    cd vagrant
    
    vagrant up
