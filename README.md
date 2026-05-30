# Linux Web Server Deployment Lab

## Overview

Configured and deployed a local NGINX web server using Linux/macOS terminal commands.

This project demonstrates web server configuration, service management, local deployment, HTTP validation, and infrastructure troubleshooting.

---

## Architecture

```text
Browser
   ↓
NGINX Web Server
   ↓
Custom HTML Page
```

---

## Technologies Used

- Linux/macOS Terminal
- NGINX
- Bash
- VS Code
- Networking
- HTTP

---

## Tasks Completed

- Installed and managed NGINX
- Created a custom HTML web page
- Configured an NGINX server block
- Validated NGINX configuration syntax
- Restarted the NGINX service
- Tested HTTP connectivity using curl
- Documented the deployment with screenshots

---

## Commands Used

```bash
brew install nginx
brew services restart nginx
brew services info nginx
nginx -t
sudo mkdir -p /var/www/html
sudo nano /var/www/html/index.html
sudo cp nginx-lab.conf /usr/local/etc/nginx/servers/nginx-lab.conf
curl -I http://localhost:8080
```

---

## Screenshots

### NGINX Service Restart

![NGINX Restart](screenshots/nginx-restart.png)

---

### NGINX Service Status

![NGINX Status](screenshots/nginx-status.png)

---

### NGINX Configuration Test

![NGINX Test](screenshots/nginx-test.png)

---

### Custom HTML File

![HTML File](screenshots/index-html.png)

---

### NGINX Server Configuration

![NGINX Config](screenshots/nginx-config.png)

---

### HTTP Validation

![HTTP Validation](screenshots/http-validation.png)

---

### Browser Validation

![Browser Validation](screenshots/browser-validation.png)

---

## What I Learned

- How to configure an NGINX web server
- How to manage services from the terminal
- How to validate web server configuration
- How to troubleshoot HTTP connectivity
- How to document infrastructure projects professionally