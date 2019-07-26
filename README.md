
How to get an ‘A+’ in SSL Labs Server Test with NginX configuration

server {
	listen 443 ssl;
	server_name domain;
	# SSL
	ssl_certificate /patch/fullchain.crt;
	ssl_certificate_key /patch/privkey.pem;
  include /etc/nginx/ssl.conf;

}
