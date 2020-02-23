This is a demo ansible playbook.
It doesn't require any special paramaters.
This playbook will install NGINX and then configure it with static website.
static-website will be downloaded from S3.

OS Requirements:
---------------
Ubuntu 18.04


How to run:
-----------
ansible-playbook nginx_url.yml -i hosts -u ubuntu --private-key ~/awskeys/baber_aws.pem -b


Above command will work if hosts file and nginx_url.yml are in same working direcroty.
