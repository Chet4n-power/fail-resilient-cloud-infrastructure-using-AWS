# the below is a shebang code for initiating bash codes
#!/bin/bash 

# the below commands are to download nginx server inside linux instance
apt update -y
apt install -y nginx

# the below commands are to start nginx server
systemctl start nginx
systemctl enable nginx

# the below command is used to show the output in the webpage opened 
echo "<h1>Deployed via AWS ASG</h1>" > /var/www/html/index.html
