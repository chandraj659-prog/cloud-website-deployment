# cloud-website-deployment
Deployed a static website using Nginx on Ubuntu VM
# Cloud Website Deployment

## 📌 Project Overview
This project demonstrates how to deploy a static website using **Nginx on Ubuntu Linux** inside a virtual machine environment.

The goal of this project is to understand basic cloud/server concepts such as web servers, Linux administration, and website hosting — without using paid cloud services.

---

## 🛠 Tools & Technologies Used
- Ubuntu Linux (Virtual Machine)
- Nginx Web Server
- VirtualBox
- HTML & CSS
- Linux Terminal

---

## 🚀 Steps Performed
1. Installed Ubuntu on VirtualBox
2. Installed and configured Nginx web server
3. Created a custom HTML webpage
4. Deployed the webpage in `/var/www/html`
5. Verified deployment using browser and service status

---

## ✅ Key Commands Used
```bash
sudo apt update
sudo apt install nginx
sudo systemctl status nginx
cd /var/www/html
sudo nano index.html
