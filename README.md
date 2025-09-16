# Azure Terraform AI Agent 🚀

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18.x-blue.svg)](https://reactjs.org/)
[![Azure](https://img.shields.io/badge/Azure-Cloud-0078d4.svg)](https://azure.microsoft.com/)
[![Terraform](https://img.shields.io/badge/Terraform-1.x-623ce4.svg)](https://terraform.io/)

An intelligent AI-powered agent for automating Azure infrastructure provisioning using Terraform. This tool provides a comprehensive solution for generating, validating, and deploying Azure resources with advanced error handling and best practices built-in.

## 🌟 Features

### 🎯 **Template Generation**
- **20+ Azure Services** supported including Cosmos DB, Azure OpenAI, App Services, HDInsight Kafka, and more
- **Intelligent Default Values** based on service types and best practices
- **Custom Templates** for complex services with proper configurations
- **Download Functionality** for generated Terraform files

### ⚡ **Auto-Validation Engine**
- **Real-time Validation** - no manual button clicks required
- **Service-specific Rules** for complex Azure resources
- **Security Best Practices** enforcement
- **Indentation and Syntax** checking

### 🚀 **Deployment Pipeline**
- **Complete Terraform Workflow**: `init` → `plan` → `apply`
- **Manual Plan Approval** for security and review
- **Real-time Logging** with color-coded status updates
- **Intelligent Error Recovery** with auto-fix suggestions

### 🛡️ **Security & Best Practices**
- SSH key recommendations for Linux VMs
- Key Vault integration suggestions
- Network security considerations
- Production-ready configurations

## 📋 Supported Azure Services

| Category | Services |
|----------|----------|
| **Compute** | Virtual Machines (Linux/Windows), App Services, Container Instances |
| **Storage** | Storage Accounts, Blob Containers, File Shares |
| **Database** | Cosmos DB, SQL Server, SQL Database |
| **AI/ML** | Azure OpenAI, Cognitive Services, Document Intelligence |
| **Networking** | Virtual Networks, Subnets, Application Gateway, Load Balancer |
| **Monitoring** | Application Insights, Log Analytics |
| **Security** | Key Vault, Managed Identity |
| **Configuration** | App Configuration |
| **Analytics** | HDInsight Kafka Clusters |

## 🚀 Quick Start

### Prerequisites
- Node.js 16.x or higher
- npm or yarn
- Azure CLI (for actual deployments)
- Terraform 1.x (for actual deployments)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/DC0603/terraform.git
cd terraform

2. **Install Dependencies**
npm install

3. **Start the development server**
npm start

4. Open your browser
Navigate to http://localhost:3000
