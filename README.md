## Project Overview

This repository contains my personal CV website, built and deployed using Azure services, follwing [ACG project video.](https://www.youtube.com/watch?v=ieYrBWmkfno&t=470s) It demonstrates my skills in **cloud technologies**, **CI/CD pipelines**, **backend integration**, and **static web hosting**. This project serves as a showcase of my proficiency in Azure and web development.

## Features

- **Static Web Hosting**: The website is hosted on **Azure Static Web Apps**, offering a fast and reliable user experience.
- **Visitor Counter**: A backend feature using **Azure Functions** and **CosmosDB** tracks real-time visitor data and stores it securely.
- **CI/CD Pipeline**: The project employs **GitHub Actions** for automated deployments, ensuring that any code changes are reflected live through continuous integration and deployment.
- **Professional Design**: The design uses a deep blue color scheme (#0A3D62) for the homepage and a lighter variant for the about section, presenting a clean and modern look.
- **Key Management**: Secure handling of sensitive information (like CosmosDB keys) using **GitHub Secrets**.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Azure Functions, CosmosDB
- **Cloud**: Azure Static Web Apps, GitHub Actions (CI/CD)
- **Security**: GitHub Secrets for managing sensitive data
- **Python**: Backend logic for Azure Functions

## Challenges & Solutions

### Azure CLI and Subscription Access Issues
While setting up the project, I ran into multiple issues with the **Azure CLI** during the `az account show` command. The problems were related to authentication and subscription access. These issues took a long time to resolve, involving multiple steps like refreshing the authentication, troubleshooting permissions, and verifying the correct subscription settings. This was a complex process that significantly delayed the project but ultimately enhanced my understanding of Azure's subscription and access controls.

### Key Management
Another challenge was managing sensitive data such as the CosmosDB keys. Initially, these keys were exposed in the codebase, which posed a security risk. I resolved this by using **GitHub Secrets** to store and manage the keys securely, ensuring they were not exposed in the repository.

### CI/CD Pipeline
Setting up the CI/CD pipeline with **GitHub Actions** was challenging due to issues in configuring the YAML file for deployment. After debugging, I was able to set up the pipeline to automatically deploy the website every time a change is pushed to the repository.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AishaS992/azurecv.git
