# Deployment
## Step 1: Create Resource Group

A Resource Group was created in Azure to organize and manage all resources used in this Blob Storage portfolio project.

### Resource Group Details

- **Resource Group Name:** storage-rg
- **Region:** west us3
- **Purpose:** Container for Azure Storage resources

### Status

✅ Completed

### Screenshot
<img width="960" height="430" alt="Screenshot 2026-07-21 002008" src="https://github.com/user-attachments/assets/358ad0e2-8b6f-4755-bff4-3ba1db10da59" />
<img width="960" height="433" alt="resourcegroup2" src="https://github.com/user-attachments/assets/60a78153-27c7-42ec-9925-4853bb0245be" />

## Step 2: Create Storage Account

A Storage Account was created to host Azure Blob Storage for this project.

### Storage Account Details

- **Storage Account Name:** myfirststorage1
- **Performance:** Standard
- **Redundancy:** Locally Redundant Storage (LRS)
- **Region:** west us3

### Why these settings?

- **Standard** provides cost-effective storage suitable for most applications.
- **LRS** keeps three copies of the data within a single Azure region, providing durability while keeping costs low for a portfolio project.

### Status
### Screenshot

<img width="960" height="429" alt="storage accout" src="https://github.com/user-attachments/assets/e38fa951-abba-4e12-8f9c-c284683d1b8e" />
<img width="960" height="428" alt="storageaccount" src="https://github.com/user-attachments/assets/92094e47-9384-4975-9017-a95375d96e33" />


## Step 3: Create Blob Container

A private Blob Container was created to store files securely within the Storage Account.

### Container Details

- **Container Name:** public-container
- **Access Level:** Private (No anonymous access)

### Why Private?

I selected private access to ensure that only authenticated users or applications with the appropriate permissions can access the files. This follows Azure security best practices.

### Status

✅ Completed

### Screenshot

<img width="960" height="432" alt="container1" src="https://github.com/user-attachments/assets/f4e72410-6b6a-4dac-928f-b4fc4b422cc0" />
<img width="960" height="426" alt="container2" src="https://github.com/user-attachments/assets/422ef798-de7f-49b0-83ec-879432be3abe" />


✅ Completed

### Screenshot



