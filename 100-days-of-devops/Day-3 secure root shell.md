# Day 3 Challenge
Following security audits, the xFusionCorp Industries security team has rolled out new protocols, including the restriction of direct root SSH login.


Your task is to disable direct SSH root login on all app servers within the Stratos Datacenter.

1. Login to the app server via ssh
2. Edit the ssh config file
`sudo nano /etc/ssh/sshd_config`

3. Find the directive PermitRootLogin. It may be commented out with a #. Remove the # and change its value to no

4. Do this for all app-servers