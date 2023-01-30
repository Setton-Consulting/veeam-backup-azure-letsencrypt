# veeam-backup-azure-letsencrypt
 A simple method to get a valid SSL certificate for Veeam Backup for Azure Appliance

Script functioning is based on renewal via Certbot and Certbot-dns-cloudflare module

To Install on Ubuntu/Debian

sudo apt update
sudo apt install snapd
sudo snap install core
sudo snap refresh core
sudo snap install --classic certbot
sudo ln -s /snap/bin/certbot /usr/bin/certbot

sudo snap install certbot-dns-cloudflare
