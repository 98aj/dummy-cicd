# Hello this is dummy project to set up dummy ci cd workflow

# 🚀 Dummy CI/CD Project

This is a simple project to demonstrate how to set up a **CI/CD pipeline** using **GitHub Actions**.

---

## 🧱 What is CI/CD?

- **CI (Continuous Integration)**: Automatically test and integrate new code into the codebase.
- **CD (Continuous Deployment/Delivery)**: Automatically deploy the application to staging or production after passing CI.

---

## 🪜 Steps to Set Up CI/CD Pipeline

### ✅ Step 1: Create Workflow Directory

Create a folder named `.github/workflows/` at the root of your project.

```bash
mkdir -p .github/workflows
bash```

### ✅ Step 2: Create a Workflow YAML File
Create a file like dummy-ci.yml inside .github/workflows/.

### ✅ Step 3: Define Workflow Structure
Each GitHub Actions YAML file consists of:

name – Workflow name

on – Event that triggers the workflow (push, pull_request, schedule, etc.)

jobs – A set of actions to run on the specified trigger

### ✅ Step 4: Add Conditions Using GitHub Events
GitHub provides predefined events to control when your workflow runs.
You can define these under the on: section in your YAML file.
