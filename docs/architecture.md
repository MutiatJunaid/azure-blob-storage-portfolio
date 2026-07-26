# Azure Blob Storage Architecture

## Solution Overview

This project demonstrates the deployment of Azure Blob Storage to securely store unstructured data.

## Architecture Diagram

```text
                    Azure Subscription
                           │
                           ▼
                 Resource Group
                 (stoageaccount-rg)
                           │
                           ▼
                 Storage Account
                  (myfirststorage1)
                           │
                           ▼
                  Blob Container
                 (public container)
                           │
                           ▼
                  Uploaded Blob/File
