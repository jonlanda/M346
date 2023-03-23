# M346

## Inhaltsverzeichnis
- [KN01](#kn01)
- [KN02](#kn02)
- [KN03](#kn03)

## KN01

### B

UI
![UI](/KN01/multipass-ui.png)
`multipass list`
![multipass list](/KN01/multipasslist.png)

### C

`multipass start`
![multipass start](/KN01/startedinstanz.png)
`multipass stop`
![multipass stop](/KN01/stoppedinstanz.png)
`multipass cpu change`
![multipass cpu change](/KN01/setcpuinstanz.png)
`multipass delete`
![multipass delete](/KN01/deletedinstanz.png)

### D

index.html
![index.html](/KN01/indexhtml.png)
info.php
![info.php](/KN01/infophp.png)
db.php
![db.php](/KN01/dbphp.png)

## KN02

### A

![cloud-init-web.yaml](/KN02/cloud-init-web.yaml)

### B

`sudo systemctl status apache2.service`
![apache status](/KN02/apache_running.png)

index.html
![index.html](/KN02/cloud-init-web-working.png)

### C

#### a)

mysql shell
![mysql](/KN02/mysql.png)

`telnet <ip> 3306`
![telnet](/KN02/mysql_telnet_connection.png)

#### b)

cloud-init-web index.html
![index.html](/KN02/cloudinitweb_index.png)

cloud-init-web info.php
![info.php](/KN02/cloudinitweb_infophp.png)

cloud-init-web db.php
![db.php](/KN02/cloudinitweb_dbphp.png)

cloud-init-web adminer
![adminer](/KN02/cloudinitweb_adminer.png)

## KN03

### a)

#### Lab 4.1 EC2

Website & URL
![website](/KN03/htmlandurl.png)

EC2 Instanzen
![instances](/KN03/instances.png)

Instanz details
![instance_details](/KN03/instancedetails.png)

Security Group & Inbound Rules
![security_group&inbound_rules](/KN03/securitygroup.png)

#### Lab 4.2 S3

Liste der Buckets
![buckets](/KN03/bucketlist.png)

HTML Seite
![website](/KN03/htmlandurlbucket.png)

Dateien im Bucket
![files](/KN03/dateienbucket.png)

Static hosting
![hosting](/KN03/statichosting.png)

### b)

Connect with ssh
![ssh](/KN03/connectwithssh.png)

### C)

cloud-init
![cloud-init](/KN03/cloud-init-ssh.yaml)

ssh connection
![ssh-command](/KN03/sshconnectC.png)
