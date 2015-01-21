Vagrant Box with Jekyll - Ansible provisioner
===========================================

How to produce box named ``jekyll-ansible-v0.1.0``:

    vagrant up
    vagrant package --output jekyll-ansible-v0.1.0.box
    vagrant box add jekyll-ansible-v0.1.0 jekyll-ansible-v0.1.0.box
