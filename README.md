
How to Nginx tuning tips TLS/SSL HTTPS – Improved TTFB/latency

server {
	listen 443 ssl;
	server_name domain;
	# SSL
	ssl_certificate /patch/fullchain.crt;
	ssl_certificate_key /patch/privkey.pem;
  include /etc/nginx/ssl.conf;

}
