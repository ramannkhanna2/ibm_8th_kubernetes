# ibm_8th_kubernetes

master node

pubIP : 54.232.241.122

ssh -i "raman-ibm-8th.pem" ubuntu@54.232.241.122

-------------
w1

pubIP : 52.67.128.193

ssh -i "raman-ibm-8th.pem" ubuntu@52.67.128.193

--------------
w2 

pubIP : 56.124.111.237

ssh -i "raman-ibm-8th.pem" ubuntu@56.124.111.237


================================

#############3
1 time initial setup :

ubuntu@ip-172-31-3-25:~$ sudo -i
root@ip-172-31-3-25:~# hostnamectl set-hostname w2
root@ip-172-31-3-25:~# bash

###############
