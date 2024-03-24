# Provided Identity-based Access to Storage Account File Share

## Introduction

Welcome to my professional portfolio, where I showcase expertise in cloud security infrastructure setup. Today, I'll walk you through the process of leveraging Azure Storage Accounts for secure data storage and implementing identity-based access controls across our environment using Microsoft Enterprise Kerberos.

![image](https://github.com/rasheedjimoh/iba-storageacct/assets/157264080/22d64704-42fe-432d-b3ed-baae08636fc8)



## Using Azure Storage Accounts

1. **Creating a Storage Account:**
   - Signed in to the Azure portal and navigated to "Storage accounts" to create a new storage account.
   - Specified essential details like subscription, resource group, name, location, and performance options.

![image](https://github.com/rasheedjimoh/iba-storageacct/assets/157264080/43b00325-29fd-4af6-9230-5aa258d1c2cb)


2. **Managing Storage Account:**
   - After creation, managed the storage account from the portal's "Storage accounts" section.
   - Tasks included creating file shares, setting access controls, uploading files, and monitoring usage and performance.

## Implementing Identity-Based Access

1. **Utilizing Microsoft Enterprise Kerberos:**
   - Provisioned identity-based access using Microsoft Enterprise Kerberos for seamless authentication and access control.
   - Input the domain name and utilized the command below to locate the Global Unique Identifier (GUID) for configuration:

```bash
repadmin /showreps ServerName
```

   - Replace "ServerName" with your domain controller (DC) name.

![image](https://github.com/rasheedjimoh/iba-storageacct/assets/157264080/ead759e8-a283-4413-b451-a5ae2170d579)


2. **Configuring File Share and Backup:**
   - Created file shares within Azure Storage Accounts to organize and manage data efficiently.
   - Implemented backup configurations to ensure data resilience and business continuity.

![image](https://github.com/rasheedjimoh/iba-storageacct/assets/157264080/9173e91b-59f2-46cb-ae05-633f20a829f9)

---

![image](https://github.com/rasheedjimoh/iba-storageacct/assets/157264080/14c7e185-8c25-4cd0-b274-d26352153c2a)

By following these steps, we establish a robust cloud storage solution with Azure Storage Accounts, enhancing security with identity-based access controls powered by Microsoft Enterprise Kerberos.

Stay secure, stay resilient!












