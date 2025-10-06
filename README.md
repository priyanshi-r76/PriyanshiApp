# PriyanshiApp — AWS Elastic Beanstalk Deployment

This project showcases the deployment of a custom Node.js application using AWS Elastic Beanstalk. It includes environment configuration, tagging, monitoring via CloudWatch, and a clean deployment pipeline.

## 🌐 Live App
[Click here to view PriyanshiApp](http://PriyanshiApp-env.eba-2kd2qqqx.us-east-1.elasticbeanstalk.com)

## 📚 Table of Contents
- [Tech Stack](#tech-stack)
- [App Structure](#app-structure)
- [Environment Variables](#environment-variables)
- [Monitoring Dashboard](#monitoring-dashboard)
- [Resource Tags](#resource-tags)
- [Screenshots](#screenshots)
- [Reflection](#reflection)

## 🛠️ Tech Stack
- Node.js
- Express
- AWS Elastic Beanstalk
- EC2 (t3.micro)
- CloudWatch
- IAM, VPC, Security Groups

## 📦 App Structure

Your app includes:
## 📦 App Structure

- [index.html](https://github.com/priyanshi-r76/PriyanshiApp/blob/main/index.html)
- [app.js](https://github.com/priyanshi-r76/PriyanshiApp/blob/main/app.js)
- [package.json](https://github.com/priyanshi-r76/PriyanshiApp/blob/main/package.json)

## ⚙️ Environment Variables
- `PROJECT_OWNER`: Priyanshi Rawat
- `VERSION`: 1.0
- `DEPLOYMENT_DATE`: 2025-10-06
- `APP_STAGE`: Production

## 🧠 Monitoring Dashboard
CloudWatch dashboard includes:
- CPUUtilization
- NetworkIn / NetworkOut
- EnvironmentHealth

## 🏷️ Resource Tags
- `Owner`: Priyanshi Rawat
- `Project`: AWS Major Project
- `Purpose`: Final Submission
- `ReviewedBy`: AWS Faculty Panel

## 📸 Screenshots

### App Homepage
![App Homepage](screenshots/app-homepage.png)

### App Running
![App Screenshot](screenshots/app-running.png)

### EC2 Tags
![EC2 Tags](screenshots/ec2-tags.png)

### CloudWatch Dashboard
![CloudWatch](screenshots/cloudwatch.png)

## 📝 Reflection
This project taught me how to deploy, monitor, and manage cloud-native apps using AWS. I learned to troubleshoot health issues, configure environments, and visualize performance metrics. Next steps: explore multi-instance scaling and CI/CD integration.

## 🔗 GitHub Repository
[Click here to view the full project on GitHub](https://github.com/priyanshi-r76/PriyanshiApp)

---

Made with 💙 by Priyanshi Rawat
