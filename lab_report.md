Nikki Shakeraneh (shak0039)

# Lab 3

This screenshot shows the creation of an Ubuntu virtual machine in the Azure portal.
![image](https://github.com/user-attachments/assets/9a99f48f-16c5-4288-bf7d-52f5a0bcff6f)

This screenshot captures the Networking settings of the VM, where inbound port rule for TCP port 3000 is added. This allows external access to Grafana’s web interface, which runs on port 3000.
![image](https://github.com/user-attachments/assets/2b3ffc30-1e82-40a7-8344-3cee0f735dc3)

This is the step where I connect to the virtual machine using SSH. This connection allows access to the Ubuntu VM environment, which enables the installation and configuration of Grafana and Azure integration.
![image](https://github.com/user-attachments/assets/d789796b-8d0e-4cf8-9501-3769f437c145)

This terminal output confirms that the Grafana service was successfully started and enabled to launch on system boot. 
![image](https://github.com/user-attachments/assets/6e83f01e-871c-46c0-8931-e054583f63e9)

This Azure portal screenshot displays the Identity blade of the VM, where the System assigned managed identity has been turned on. This allows the VM to authenticate securely with Azure Monitor without the need for credentials.
![image](https://github.com/user-attachments/assets/963bf5dd-a6c2-424b-b7af-86bc9928d89a)

This image shows the initial login to the Grafana web UI. After entering the default credentials (admin/admin), the user is prompted to update the password.
![image](https://github.com/user-attachments/assets/34382734-8cf4-40f5-8fe6-c57aabcd3736)

This screenshot shows the "Add data source" section in Grafana. I selected Azure Monitor, chose Managed Identity as the authentication method.
![image](https://github.com/user-attachments/assets/dd01af13-b3a1-4285-ab60-4173de8b60b5)

This panel shows the user creating a new dashboard in Grafana and selecting metrics from Azure Monitor. The metrics visualized are Percentage CPU, Available Memory Percentage, Network In Total and Network Out Total.
![image](https://github.com/user-attachments/assets/d082884d-c40f-401f-95b7-7c66485e09f5)

This screenshot shows the dashboard being saved after making customizations.
![image](https://github.com/user-attachments/assets/242f28b1-ea54-4965-8137-dcd2663f54fe)

This final screenshot displays the completed Grafana dashboard with real-time visualizations of the selected Azure metrics. It displays the integration and it provides insight into the performance of the Ubuntu virtual machine.
![image](https://github.com/user-attachments/assets/e77188f9-29f1-4278-aa2d-f06c17a7e3a1)
