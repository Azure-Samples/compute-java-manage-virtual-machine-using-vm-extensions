---
page_type: sample
languages:
- java
products:
- azure
description: "Azure Compute sample for managing virtual machine extensions."
urlFragment: compute-java-manage-virtual-machine-using-vm-extensions
---

# Manage Virtual Machine Extensions (Java)


  Azure Compute sample for managing virtual machine extensions. -
   - Create a Linux and Windows virtual machine
   - Add three users (user names and passwords for windows, SSH keys for Linux)
   - Resets user credentials
   - Remove a user
   - Install MySQL on Linux | Choco and MySQL on Windows
   - Remove extensions
 

## Running this sample

To run this sample:

Set the environment variable `AZURE_AUTH_LOCATION` with the full path for an auth file. See [how to create an auth file](https://github.com/Azure/azure-libraries-for-java/blob/master/AUTH.md).

```bash
git clone https://github.com/Azure-Samples/compute-java-manage-virtual-machine-using-vm-extensions.git
cd compute-java-manage-virtual-machine-using-vm-extensions
mvn clean compile exec:java
```

## More information

[http://azure.com/java](http://azure.com/java)

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
