# OpenStack Env
Create HA openstack deploy environment for kolla-ansible
* 1 deploy
* 3 controller
* 2 compute node

# How to use
1. Create `keys` folder and generate ssh key
```
mkdir -p $PWD/keys
ssh-keygen ssh-keygen -b 2048 -t rsa -f $PWD/keys/key -q -N ""
```
2. Prepare files 
* kolla-ansible-docker.tar.gz : kolla-ansible tool written by kjelly
* ansible-kolla-os : deploy os with openstack service use ansible written by cameron.c
* kolla-runtime.tar.gz : quick install docker by kjelly
* kolla-ansible image: kolla-ansible used docker image by kjelly

[To do]
