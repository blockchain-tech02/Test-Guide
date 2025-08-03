# Aplication Setup & Testing Guide

This guide provides step-by-step instructions for setting up and running the project hosted at:

📁 **Repository:** [https://github.com/blockchain-tech02/testPrj725](https://github.com/blockchain-tech02/testPrj725)

---

## 📦 Prerequisites

Before starting, make sure the following tools are installed on your machine:

### ✅ Node.js

- Download and install Node.js from the official website:  
  👉 https://nodejs.org/en/download

### ✅ Python

- Install Python, which is required by some native Node modules during build:  
  👉 https://www.python.org/downloads/

> ⚠️ **Important:** During installation, select the option to **Add Python to PATH**.

---

## 🚀 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/blockchain-tech02/testPrj725.git
```

### 2. Navigate to the Project Directory

```bash
cd testPrj0721
```

### 3. Install Dependencies

Use the following command to install project dependencies. The --legacy-peer-deps flag ensures compatibility with older peer dependency definitions:

```bash
npm install --legacy-peer-deps
```

---

## 🚀 Running the Application

Run the development server with:

```bash
npm run start
```
