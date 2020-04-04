# Web Proxy using Docker, NGINX and Let's Encrypt for raspberry pi

the repo forks the great work of evertramos https://github.com/evertramos/docker-compose-letsencrypt-nginx-proxy-companion
my modifications shall enable it running on raspbian for raspberry pi

![Web Proxy environment](https://raw.githubusercontent.com/evertramos/images/master/webproxy.jpg)


# preparations
-you need docker, docker compose
-edit .env file for adapting it to your urls, credentials, ...

# running it
./start.sh
or docker-compose up -d

# useful hints
- foo bar
