# yopass
1. Deploy yopass application as docker compose
2. Install docker & docker compose 
3. Go to respective path (eg. /opt/services ''create services folder in /opt)
4. Create docker-compose.yaml file in it
5. Create 2 folders certs & conf in /opt/services
6. Create SSL certificate for the domain you want and put it's domain_name.crt & domain_name.key file in certs folder
7. Create nginx.conf file in conf folder
8. In nginx.conf replace domain_name with domain name you want
9. Then run docker-compose up -d
