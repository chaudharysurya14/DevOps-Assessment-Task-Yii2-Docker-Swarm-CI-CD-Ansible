# Yii2 App Deployment on Docker Swarm

## 📦 Stack
- PHP 8.1 + Yii2
- Docker Swarm
- NGINX (host reverse proxy)
- Ansible for automation
- GitHub Actions for CI/CD

## 🚀 Setup Instructions

1. Clone repo
2. Configure GitHub Secrets
3. Run Ansible Playbook
4. Push code to main branch
5. GitHub Actions will deploy automatically

## 🔥 Assumptions
- Single EC2 instance
- Public IP accessible
- DockerHub account available

## 🧪 Testing
- Open `http://172.69.182.133/` and verify the Yii2 application is accessible.
