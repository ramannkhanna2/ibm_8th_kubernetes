# ibm_8th_kubernetes

-- Check for new pvt key in etherpad at the top  :
https://etherpad.opendev.org/p/r.00b50a4c11cfd0898e411eebe6c329a8

master node

ssh -i "raman.pem" ubuntu@100.24.37.66

-------------
w1

ssh -i "raman.pem" ubuntu@44.223.33.89

--------------
w2 

ssh -i "raman.pem" ubuntu@54.211.111.104


================================

#############3
1 time initial setup :

```
ubuntu@ip-172-31-3-25:~$ sudo -i
root@ip-172-31-3-25:~# hostnamectl set-hostname w2
root@ip-172-31-3-25:~# bash
```
###############
