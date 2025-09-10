# ibm_8th_kubernetes

-- Check for new pvt key in etherpad at the top  :
https://etherpad.opendev.org/p/r.00b50a4c11cfd0898e411eebe6c329a8

master node

pubIP : 3.91.187.196

ssh -i "raman.pem" ubuntu@3.91.187.196

-------------
w1

pubIP : 54.225.33.161

ssh -i "raman.pem" ubuntu@54.225.33.161

--------------
w2 

pubIP : 13.217.200.242

ssh -i "raman.pem" ubuntu@13.217.200.242


================================

#############3
1 time initial setup :

```
ubuntu@ip-172-31-3-25:~$ sudo -i
root@ip-172-31-3-25:~# hostnamectl set-hostname w2
root@ip-172-31-3-25:~# bash
```
###############
