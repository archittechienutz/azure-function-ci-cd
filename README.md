# Azure Function CI/CD with Azure DevOps

This project demonstrates how to build, test, and deploy an Azure Function App using Azure DevOps CI/CD pipelines directly from GitHub Codespaces.

## 🚀 Function App Description

A simple HTTP-triggered Azure Function written in JavaScript that responds with a custom greeting message.

### Example Request

```http
GET /api/HelloWorld?name=Archit

Example Response

{
  "message": "Hi Archit, your CI/CD Function is working from Codespaces!"
}

Technologies Used
Azure Function App (Node.js)

GitHub Codespaces (for development)

Azure DevOps (for CI/CD)

Azure Resource Manager (deployment target)

YAML-based Azure Pipelines

🔁 CI/CD Pipeline Stages
Stage	Description
Build	Installs Node dependencies
Test	Runs automated tests (or skips if none exist)
Deploy	Deploys to Azure Function App via ARM

🌐 URLs
GitHub Repository: https://github.com/archittechienutz/azure-function-ci-cd.git

Deployed Function App: https://fluffy-garbanzo-jwwq6jqxv7vh5wwr-7071.app.github.dev/api/HelloWorld?name=Archit