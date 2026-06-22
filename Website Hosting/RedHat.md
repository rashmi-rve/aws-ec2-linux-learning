_#RedHat_

_#launch EC2 instance through Red Hat_
_#Key pair is must - .pem for mobaxterm and .ppk for putty_

_#connection required through remote desktop_ _#session_
_#download mobaxterm_
_#Public IP is required_
_#user is required_ 
_#private key is to upload in advance setting_

sudo yum update 
sudo yum install ngnix
sudo systemctl start nginx
sudo systemctl status nginx

sudo yum install wget

_#copy any free CSS template for practice_
wget link

ls

#rename the list name

mv name name.zip

sudo yum install unzip 

unzip name.zip

_#find the location of server where web content can be hosted_

cd/etc/nginx

ls

cat nginx.conf

_#location in **root** as -/usr/share/nginx/html_

cd web content folder

ls

sudo mv * /usr/share/nginx/html

_#run as root and set the SE Linux type of usr/share/ngnix/html to httpd_sys_content_t, so the web sever can read the files_

sudo chcon -r -t httpd_sys_content_t/usr/share/nginx/html

_#chcon - change context_
_#SE Linux -Security Enhanced Linux_
_#it is a command on linux system that use SELinux_




