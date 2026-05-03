# 🚀 .NET CI/CD Pipeline using Azure DevOps

## 📌 Project Overview
This project demonstrates a complete CI/CD pipeline for a .NET web application using Azure DevOps.  
It automates build, test, and deployment across multiple environments.

---

## 🛠️ Technologies Used
- Azure DevOps
- .NET 8
- Azure App Service
- Git & GitHub
- YAML Pipelines

---

## ⚙️ CI/CD Pipeline Flow

### 🔹 CI (Continuous Integration)
- Restore dependencies
- Build application
- Run unit tests
- Publish artifact

### 🔹 CD (Continuous Deployment)
- Deploy to Dev
- Deploy to Staging
- Deploy to Production
- Manual approval before Production

---

## 🌍 Environments

| Environment | URL |
|------------|------|
| Dev | http://mywebapp-dev-sejal.azurewebsites.net |
| Staging | http://mywebapp-stg-sejal.azurewebsites.net |
| Production | http://mywebapp-prd-sejal.azurewebsites.net |

---

## 📈 Key Learnings
- Built multi-stage YAML pipeline
- Implemented environment-based deployments
- Configured Azure service connections
- Fixed .NET version compatibility issues
- Debugged real CI/CD pipeline errors

---

## ✅ Project Status
✔ Completed and deployed successfully  
✔ CI/CD fully working  
✔ Hosted on Azure App Service  

---

## 👩‍💻 Author
Sejal Sakhala
TODO: Explain how other users and developers can contribute to make your code better. 

If you want to learn more about creating good readme files then refer the following [guidelines](https://docs.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)
