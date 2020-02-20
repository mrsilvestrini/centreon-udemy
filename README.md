# PROJECT COURSE CENTREON ENTERPRISE 3.4

Project for class Udemy Course Centreon 3.4

Getting Started

- Fork the project and enjoy.
- Atention for pre requisites and License!!!

Prerequisites

- Course

  - <https://www.udemy.com/course/centreon/>

- Hypervisor (VMWare or Virtualbox)

- Centos 7 minimal iso
  - <http://ftp.unicamp.br/pub/centos/7.7.1908/isos/x86_64/>

Authors

- Marcos Silvestrini

License

- This project is licensed under the MIT License - see the LICENSE.md file for details

Setup Environment

- Install Centos minimal

  Disable selinux  
  /etc/selinux/config

- Disable firewald
  systemctl stop firewalld  
  systemctl disable firewalld

- Install tools

  vim  
  wget  
  net-tools  
  git  
  cifs-utils

- Install Centreon with script fame script
  <https://github.com/mrsilvestrini/centreon>

- Create Monitoring
  1 - Create a command  
  Example: check_host_alive  
  $USER1$/check_icmp -H $HOSTADDRESS$ -w 5000,50% -c 7000,100%
