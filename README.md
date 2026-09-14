# Ansible Automated Nginx Deployment

## 📌 Overview

This project demonstrates automated deployment of an Nginx web server on an AWS EC2 Ubuntu instance using Ansible.

The project uses an Ansible controller to connect to an AWS EC2 target server through SSH and automatically install Nginx and deploy a custom HTML website.

## 🏗️ Architecture

Ansible Controller (Ubuntu)
        |
        | SSH
        ↓
AWS EC2 Ubuntu Server
        |
        ↓
Nginx Web Server
        |
        ↓
Custom HTML Website

## 🛠️ Technologies Used

- AWS EC2
- Ansible
- Linux / Ubuntu
- Nginx
- HTML
- Git & GitHub
- SSH

## 🚀 What I Did

- Installed Ansible on Ubuntu
- Created an AWS EC2 Ubuntu server
- Configured SSH access
- Created an Ansible inventory
- Tested connectivity using Ansible Ping
- Created an Ansible playbook
- Installed Nginx automatically
- Deployed a custom HTML webpage using Ansible
- Verified the website through the EC2 public IP
- Uploaded the project to GitHub

## 📁 Project Structure

```text
ansible-nginx-deployment/
├── .gitignore
├── index.html
├── nginx.yml
└── README.md
