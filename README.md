# Protection
# AUTHOR of this Project
$[K]Y~#Rocks & ss1234

# You Must be root to enter below commands
# For Ubuntu

apt-get update && apt-get upgrade

#For centos 
yum -y install update

# For gcloud install

gcloud init

# For Digital Ocean

cd ~
wget https://github.com/digitalocean/doctl/releases/download/v1.8.0/doctl-1.8.0-linux-amd64.tar.gz
tar xf ~/doctl-1.8.0-linux-amd64.tar.gz
sudo mv ~/doctl /usr/local/bin
doctl auth init

#It will now ask for token just create api token in your digital ocean account and paste here and press enter
#Now you re ready to run script
