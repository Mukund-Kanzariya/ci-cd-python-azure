# 🚀 CI/CD Python Azure

A complete CI/CD pipeline for deploying a Python web application to **Microsoft Azure App Service** using **GitHub Actions**.

This project demonstrates how to automate the build, testing, and deployment process whenever changes are pushed to the GitHub repository.

---

## 📌 Features

- Automated CI/CD using GitHub Actions
- Continuous Deployment to Azure App Service
- Python web application
- Version-controlled source code
- Easy to extend for Flask or Django projects
- Secure deployment using GitHub Secrets

---

## 🛠️ Tech Stack

- Python
- GitHub Actions
- Azure App Service
- Git
- YAML
- GitHub

---

## 📂 Project Structure

```
ci-cd-python-azure/
│
├── .github/
│   └── workflows/
│       └── azure-webapp.yml
│
├── app.py
│
└── README.md
```

---

## ⚙️ CI/CD Workflow

The GitHub Actions workflow performs the following steps:

1. Trigger on every push to the `main` branch.
2. Checkout the repository.
3. Set up the Python environment.
4. Install project dependencies.
5. Build the application.
6. Authenticate with Azure.
7. Deploy the application to Azure App Service.

---

## 🔄 Workflow Diagram

```
Developer
     │
     ▼
Push Code to GitHub
     │
     ▼
GitHub Actions Triggered
     │
     ▼
Checkout Repository
     │
     ▼
Setup Python
     │
     ▼
Install Dependencies
     │
     ▼
Build Application
     │
     ▼
Deploy to Azure App Service
     │
     ▼
Application Live
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/Mukund-Kanzariya/ci-cd-python-azure.git
```

Move into the project directory

```bash
cd ci-cd-python-azure
```

Run the application

```bash
python app.py
```

---

## 🔑 GitHub Secrets Required

To deploy successfully, configure the following secrets in your GitHub repository:

| Secret Name | Description |
|-------------|-------------|
| AZURE_WEBAPP_NAME | Azure App Service Name |
| AZURE_WEBAPP_PUBLISH_PROFILE | Publish Profile downloaded from Azure |

---

## 🌐 Azure Deployment

The application is deployed automatically to **Azure App Service** whenever code is pushed to the `main` branch.

Deployment includes:

- Automated build
- Continuous deployment
- Zero manual deployment steps

---

## 📈 Benefits of CI/CD

- Faster software delivery
- Automatic deployment
- Reduced manual errors
- Consistent deployment process
- Easy rollback using GitHub history
- Improved developer productivity

---

## 📸 GitHub Actions

After each push, GitHub Actions automatically executes the workflow and displays the deployment status under the **Actions** tab.

You can monitor:

- Build Status
- Deployment Status
- Logs
- Errors

---

## 📚 Learning Outcomes

This project helped in understanding:

- Continuous Integration (CI)
- Continuous Deployment (CD)
- GitHub Actions
- Azure App Service Deployment
- YAML Workflow Configuration
- GitHub Secrets
- Cloud Deployment

---

## 👨‍💻 Author

**Mukund Kanzariya**

GitHub: https://github.com/Mukund-Kanzariya

LinkedIn: *(Add your LinkedIn profile here)*

---

## ⭐ If you found this project useful

Give this repository a ⭐ on GitHub!
