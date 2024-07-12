# 0x10-https_ss
### Description of what each file shows:
Files that start with:
1. After updating A records for www (to point to load balancer), lb-01, web-01, and web-02 on [Gandi](https://www.gandi.net/en), running this script shows our subdomain and A records
2. After following the Step-by-Step Guide on Digital Ocean to install a certificate, this shows the most updated HAproxy config file. HAproxy is listening to port TCP 443 and accepts SSL traffic.
3. Shows updated HAproxy config file. Redirects HTTP traffic to HTTPS. HAproxy returns a 301 permanent redirect.

### Environment
* Language: Bash script
* OS: Ubuntu 14.04 LTS
* Web Servers: web-01, web-02 Nginx
* Load Balancer: lb-01, (www) HAproxy; Important folders /etc/letsencrypt/live/www.melissax.online/*
* Domain Name: from [Gandi](https://www.gandi.net/en)
* Style guidelines: [Shellscript for Bash](https://github.com/koalaman/shellcheck)
