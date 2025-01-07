List of commands after creating EC2 instance :

**Install git :**
sudo su -
git --version
yum install git -y
git --version

**Get the code files from git:**
git clone https://github.com/Renu987/AWSDemo.git
ls
cd AWSDemo/

**Install Httpd apache server :**
yum install httpd -y
systemctl start httpd
systemctl enable httpd
systemctl status httpd

**Copy the files /var/www/html as apache can host the file which are in that folders:**
cp index.html /var/www/html
cp -r assets/ /var/www/html
cp -r error/ /var/www/html
cp -r images/ /var/www/html

**Go to /var/www/html :**                     
cd /var/www/html
ls
You can see the copied files

****Now Enter the public ip address of your ec2 instance  in browser and you can see the app page: ****
