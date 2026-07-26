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

## Step 4: Upload a Blob

A sample file was uploaded to verify that Azure Blob Storage was working correctly.

### Uploaded File

- **File Name:** activity.jpg
- **Upload Method:** Azure Portal

### Result

The file was successfully uploaded and is now stored as a blob within the 'public -container'container.

### Screenshot
<img width="960" height="428" alt="Screenshot 2026-07-21 015941" src="https://github.com/user-attachments/assets/7cd568ac-92c4-40b6-8f34-79a54ae784c0" />
<img width="960" height="528" alt="Screenshot 2026-07-21 020112" src="https://github.com/user-attachments/assets/468c3645-c2c8-4fd4-bde1-bc2a2ecc599e" />

| Azure Term          | Meaning                                                               |
| ------------------- | --------------------------------------------------------------------- |
| **Storage Account** | The top-level Azure storage resource.                                 |
| **Container**       | Like a folder that organizes blobs.                                   |
| **Blob**            | The actual file stored in Azure (image, PDF, text file, video, etc.). |

## What I Learned

Through this exercise I learned how Azure Blob Storage is structured and how data is organized.

Key concepts:
- A Storage Account is the top-level Azure resource.
- A Blob Container organizes related blobs.
- A Blob is an individual file stored in Azure.
- Private containers prevent anonymous access and improve security.
- Azure Portal provides an easy way to manage storage resources.



