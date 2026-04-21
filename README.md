# Okta Terraform Lab

## 🎯 Overview
This repository uses Terraform to automate the creation and management of Okta Groups within a Sandbox environment.

## 🛠️ Prerequisites
* **Terraform CLI:** (v1.0+)
* **Okta Sandbox Account:** [Developer Console](https://developer.okta.com/)
* **Okta API Token:** Created with read/write permissions for Groups.

## 📂 Project Structure
* `main.tf`: Defines Okta resources (Groups).
* `providers.tf`: Configures the Okta connection.
* `variables.tf`: Defines required inputs.
* `.gitignore`: Prevents sensitive `.tfvars` and state files from being uploaded.

## 🚀 How to Run
1. Initialize the project:
   ```bash
   terraform init