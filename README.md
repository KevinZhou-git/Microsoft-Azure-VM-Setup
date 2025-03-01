![image](https://github.com/user-attachments/assets/f499f67e-3444-442d-8d54-77b157aba2eb)
# What is Microsoft Azure?
Microsoft Azure is a comprehensive cloud computing platform and service created by Microsoft. It provides a wide range of cloud services, including computing, analytics, storage, and networking. Users can choose and configure these services to develop and scale new applications or run existing applications in the public cloud.
In this tutorial, you will learn how to set up a Microsoft Azure account and how to configure a virtual machine.

# Requirements
- Computer
- Reliable internet connection
- Credit Card (no payments needed)

# Setting Up Azure and a Virtual Machine
### Step 1: Create a free Microsoft Azure account

Click this [link](https://azure.microsoft.com/en-us) to create a free account

- Select "Try Azure for Free". You will need to sign into or create a Microsoft Account if you do not currently have one.
- Fill out the all the information required to create your account.
- Click "Go to the Azure Portal" and you are finished setting up your Azure account.
 ![image](https://github.com/user-attachments/assets/73d375a0-f9a2-4f5c-8040-ec353433e29b)
 ![image](https://github.com/user-attachments/assets/9bb5bec0-1695-4064-b28a-132d8f2c89f3)

### Step 2: Create a Resource Group

- At the top of the home page, type "resource group" into the search bar.
- Select "Create"
- Now you will need to give the resource group a name and region. This tutorial will be using "Azure1" as the name and "(US) East US" for the region.
- Click "Review + create" at the bottom left and "Create" when finished.
  
![image](https://github.com/user-attachments/assets/c237c181-3429-4b17-abaa-60ff6bd53c9f)
![image](https://github.com/user-attachments/assets/b65e7bf4-5e0c-45b0-a593-3e6ca1dcd59e)

![image](https://github.com/user-attachments/assets/140d4eea-c7f1-40db-a3e4-eb7bbb5b8a3d)

### Step 3: Create a Storage Account

- Search "storage account" in the search bar similar to Step 2.
- Select "Create storage account"
- You will need to use the same resource group and region as in Step 2. Assign a name for the storage account.
- Click "Review + create" at the bottom left and "Create" when finished.
![image](https://github.com/user-attachments/assets/f0694be5-b1d3-4139-a118-04b030358624)
![image](https://github.com/user-attachments/assets/c2da34f3-7a2c-4d1e-a4bc-db18d0639892)

### Step 4: Create a Virtual Machine

- Search "virtual machine" in the search bar.
- Select "Create" and "Azure virtual machine"
- You will need to select the same resource group and region as previous steps. Assign a name for the virtual machine.
![image](https://github.com/user-attachments/assets/fd947ca7-7bc6-4b5c-9172-620e82130ff9)
![image](https://github.com/user-attachments/assets/4c209714-15b4-4d7b-aadc-b7f5e47a6f84)

- Select "Windows 10 Pro" for the Image.
- Select "D2s_v3" for the Size.
- Assign a name and password for your virtual machine, and click "Review + Create" once finished.
![image](https://github.com/user-attachments/assets/c82a9149-c2a9-4fd9-b9a3-42069e12b65a)
![image](https://github.com/user-attachments/assets/2e43f059-e268-4093-a6c7-94e7b5bb7751)

### Step 5: Connect to your Virtual Machine

- We first need to find the public IP address of your virtual machine. Select the virtual machine you created and copy the IP address.
![image](https://github.com/user-attachments/assets/ad70e2a2-9790-46d4-833a-2006480662f9)

- Now, we will use Remote Desktop to connect to our virtual machine.
- Mac Users
  - Google "Microsoft Remote Desktop" and install it.
  - Open the application and click "Add PC".
  - Paste the IP address we copied and select "Add".
  - Double click the virtual machine and put in the username and password you created in Step 4.
  - Select continue.
- Windows Users
  - Press the Windows key and search "Remote desktop", and open the application.
  - Put in the IP address we copied.
  - Put in the username and password we created in Step 4, and click Ok.
    
![image](https://github.com/user-attachments/assets/fe05a32d-a0a2-4507-9d93-b2aa0419aba1)
![image](https://github.com/user-attachments/assets/683675e5-a5fe-4e9f-bbe0-19e6ec1043dc)
![image](https://github.com/user-attachments/assets/84abfbaf-e979-44e3-8d2e-8006fc72a8a3)

- Congratulations, you have created a virtual machine using Azure!
