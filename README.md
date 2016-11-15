   
Development
-----------

 # Clone linkfloyd repository to ~/htdocs/linkfloyd-php
 
    git clone git@github.com:linkfloyd/linkfloyd-php.git ~/htdocs/linkfloyd-php

 # Set IP addresses
 
    192.168.56.102 lf.dev

 # Install vagrant >= 1.8 on your local
 
    wget https://releases.hashicorp.com/vagrant/1.8.5/vagrant_1.8.5_x86_64.deb -O vagrant.deb && sudo dpkg -i vagrant.deb && rm vagrant.deb

 # Install Vagrant plugin 
 
    vagrant plugin install vagrant-vbguest
 
 # Install ansible >= 2.0 on your local
 
    sudo pip install ansible
    
 # Run vagrant   
 
    cd vagrant
    
    vagrant up
