# Credit Calculator

A simple credit / loan repayment calculator built as part of the **DevOps Ninja Contest**.

This project demonstrates how to build, containerize, and deploy a small application using modern DevOps practices while maintaining clean and minimal application logic.

---

## Overview

The Credit Calculator allows users to:

- Calculate loan installment amounts
- Estimate total repayment cost
- Adjust parameters such as loan amount, interest rate, and repayment period
- Quickly simulate financing scenarios

The main goal of the project was not only to implement financial calculation logic, but also to showcase:

- CI/CD pipeline configuration
- Containerization
- Deployment automation
- Clean project structure

## Features

- Loan repayment calculation
- Interest rate handling
- Installment breakdown in pdf file
- Simple and intuitive interface
- Container-ready setup

## DevOps Context

This project was created as part of the **DevOps Ninja Contest**, focusing on:

- Infrastructure as Code principles
- Docker-based environments
- Automated builds
- Continuous Integration workflows
- Deployment best practices

It serves as a practical example of combining application development with DevOps automation.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/arosicki/credit-calculator.git
cd credit-calculator
```

Follow the instructions in the repository to:

- Install dependencies
- Run locally
- Build Docker image (if applicable)
- Deploy using provided configuration

## Docker

If the project includes a Dockerfile:

```bash
docker build -t credit-calculator .
docker run -p 3000:3000 credit-calculator
```
