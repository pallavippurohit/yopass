# yopass
Deploy yopass application as docker compose
Install docker & docker compose 
Go to respective path (eg. /opt/services ''create services folder in /opt)
Create docker-compose.yaml file in it
Create 2 folders certs & conf in /opt/services
Create SSL certificate for the domain you want and put it's domain_name.crt & domain_name.key file in certs folder
Create nginx.conf file in conf folder
In nginx.conf replace domain_name with domain name you want
Then run docker-compose up -d
