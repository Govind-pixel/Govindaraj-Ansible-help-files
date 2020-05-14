#### Install ansible for linux (working checked 14.5.2020)
  * sudo yum update -y
  * sudo yum install -y python-boto python-boto3
  * sudo rpm -Uvh https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
  * sudo amazon-linux-extras install ansible2 -y  # for amazon-linux2
  * sudo yum install ansible -y
  
#### Install ansible on a Mac
  * Check if pip is already installed in your mac (which pip). In case you don't have it, try sudo easy_install pip
  * For installing Ansible, use : sudo pip install ansible
  * Another alternative to install ansible is using brew, you can simply do --> brew install ansible.
 
#### Install ansible on Windows
  * The easiest solution for installing ansible on windows is to use a linux virtual machine. for instance- virtualbox, vmware 

#### For RHEL/CentOS systems
  * python-pip and ansible are available via the EPEL repository.
  * In order to see if EPEL repo is already available, use command--> yum repolist | grep epel
  * use this command for RHEL/CentOS 6--> rpm -ivh http://d1.fedoraproject.org/pub/epel/6/x86_64/\     epel-release-6.8.noarch.rpm
  * For RHEL/Centos7 use--> yum install epel-release

#### New method for AWS RHEL8/Cent OS system (working checked 14.5.2020)
  * sudo yum update
  * us this command for RHEL/Cent OS8: sudo  yum install https://dl.fedoraproject.org/pub/epel/epel-release-latest-8.noarch.rpm
  * sudo yum install epel-release
  * sudo yum install ansible
  
#### For Debian/Ubuntu
  * sudo apt-get install python-software-properties
  * sudo apt-add-repository -y ppa:ansible/ansible
  * sudo apt-get update
  * sudo apt-get install -y ansible
  
#### Once installed, use ansible --version (to verify)
