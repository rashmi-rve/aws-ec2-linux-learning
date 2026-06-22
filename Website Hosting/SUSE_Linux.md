#SUSE_Linux

#launch EC2 instance through SUSE Linux

#Key pair is must - .pem for mobaxterm and .ppk for putty

#connection required through remote desktop #session

#download mobaxterm

#Public IP is required

#user is required

#private key is to upload in advance setting

#package manager is zypper

sudo zypper update

sudo zypper install ngnix

sudo systemctl start nginx

sudo systemctl status nginx

cd/etc/ngnix

ls

cat nginx.conf     -copy the root value for server location and paste in notepad

#copy free CSS template for practice

wget link

ls 

mv name name.zip

sudo zypper install unzip

unzip name.zip

ls

sudo mv * location as in /srv/www/htdocs

sudo chmod 777 /srv/www/htdocs

#chmod- change mode
#it is a command in unix/linux system used to change file and directory permission
