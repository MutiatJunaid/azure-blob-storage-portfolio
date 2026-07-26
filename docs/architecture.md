# Azure Blob Storage Architecture

## Solution Overview

This project demonstrates the deployment of Azure Blob Storage to securely store unstructured data.

## Architecture Diagram

                           Azure Subscription
                                   │
                    ┌──────────────┴──────────────┐
                    │                             │
                    ▼                             ▼
            Resource Group                Azure Storage Account
                                                   │
                         ┌─────────────────────────┼─────────────────────────┐
                         ▼                         ▼                         ▼
                  Blob Container          Storage Configuration      Data Protection
                  (Private Access)        HTTPS • TLS 1.2           Soft Delete
                         │
                         ▼
                   Uploaded Blob
