# Firewall
Directory contains files associated with the **ALX Software Engineering program** project "0x13. Firewall". This project looks at the concept of Web stack debugging and what firewall is.

## Task 1 add 'sudo' where necessary
- apt-get install ufw
- sed -i 's/IPV6=.*/IPV6=yes/' /etc/default/ufw
- ufw disable
- ufw enable
- ufw default deny incoming
- ufw default allow outgoing
- ufw allow 22/tcp
- ufw allow 443/tcp
- ufw allow 80/tcp

### How to manage and forward ports with UFW
https://www.arubacloud.com/tutorial/how-to-manage-and-forward-ports-with-ufw-on-ubuntu-18-04.aspx

## Task 2

### modify your /etc/ufw/before.rules and paste the file as your answer


![](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-sysadmin_devops/284/V1HjQ1Y.png)