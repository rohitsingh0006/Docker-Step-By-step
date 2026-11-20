# Day 0 : To create the practice environment and meet the prerequisites.

We will be using docker on ubuntu linux. If you are using windows/mac system you may use VMware to create a VM of Ubuntu linux or Use Azure VM or any other cloud providers' VM.


## Install docker & setup

### 🚀Here are steps to install docker on ubuntu:

<mark>install docker</mark>
```bash
    # apt update
    # sudo apt install apt-transport-https ca-certificates curl software-properties-common
    # curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
    # sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu focal stable"
    # sudo apt install docker-ce
    # usermod -aG docker <normal_user> 
```
