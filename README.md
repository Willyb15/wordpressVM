# wordpressVM


###Go to wordpress .org and dowlonad wordpress


## save to files on your local machine

##open up your project and initialize git

make a .gitignore file so some db inforation and ideas file are not tracked
make an initial commit to git of the recently downloaded WP files
git init
git add . 
git status
git commit -m "first commit"
gir remote add origin https:s://github.com/yourname/project.git
git push -u remotre origin master
git sttus
nothing to commit working tree clean
Your files should now be on github and updated

###On AWS Launch EC2 Instance running Ubuntu

#save your pem keys ND CHMOD00 KEYS and SSH into your servr

run sudo apt get update

Install Apache Web Server 
sudo apt-get install apache2
Install Git
sudo apt-get install git
Install Myswl Server 
sudo apt-get install mysql-server
mysqladmin -p -u root version
sudo systemctl restart apache2
Install Php
sudo apt-get install php libapache2-mod-php php-mcrypt php-mysql

sudo nano /etc/apache2/mods-enabled/dir.conf

Now we have everything we need on our web server to get WP up and running


Push your WP files out to the web server =
git push 

Now you should receive the WP page Copy and pase this text and create new file in WP
Send this out
