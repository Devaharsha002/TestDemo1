# TestDemo1

# PrimeOne Bank CRM System

A comprehensive enterprise CRM system built on Microsoft Power Platform for digital-first banking operations.

## 🏗️ Architecture

- **Platform**: Microsoft Dynamics 365 CE / Power Platform
- **Database**: Microsoft Dataverse
- **Backend**: C# Plugins (.NET Framework 4.6.2)
- **Frontend**: JavaScript Web Resources
- **CI/CD**: GitHub Actions with Power Platform Build Tools

## 📋 Features

### Core Modules
- **Customer Onboarding**: Digital KYC verification and account setup
- **Product Management**: Banking products with eligibility rules
- **Loan Processing**: Application lifecycle with approval workflows
- **Service Management**: Omnichannel customer service with SLA tracking
- **Compliance**: AML monitoring and regulatory reporting
- **Analytics**: Customer insights and risk profiling

### Business Entities (39 Tables)
- Person, Customer, Address, KYC Document
- Product, Account, Loan Application
- Service Request, Compliance Case, Risk Profile
- And 29 more supporting entities

## 🚀 Getting Started

### Prerequisites
- Visual Studio 2022 with Power Platform Tools extension
- Power Platform environment (Dev/Test/Prod)
- Power Platform CLI
- Git

### Development Setup
1. Clone the repository
2. Open `Plugins/PrimeOneBank.Plugins.sln` in Visual Studio 2022
3. Connect to your Power Platform environment via Tools → Connect to Dataverse
4. Import the unmanaged solution from `Solutions/Unmanaged/`

### Deployment
