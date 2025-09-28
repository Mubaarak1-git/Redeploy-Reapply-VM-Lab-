# 🔄 Azure VM Redeploy & Reapply Lab – My Experience
In this lab, I explored how to recover a Windows-based Azure virtual machine (VM) that was experiencing connectivity and provisioning issues. I used two key recovery operations available in the Azure portal:

- **Redeploy VM**: When Remote Desktop (RDP) access failed and the VM became unreachable, I used the redeploy option to move the VM to a new physical node within Azure’s infrastructure. This process retained all configurations, disks, and network settings—allowing to restore access without losing data.

- **Reapply VM** State: In a separate scenario, the VM entered a failed provisioning state. I resolved this by reapplying the VM’s state, which triggered a fresh provisioning cycle while preserving the original setup. This helped recover the VM without needing to rebuild it from scratch.

🧪 **What I Practiced** <br> I deployed a Windows Server VM for testing Active Directory and internal applications. When connectivity broke down, I applied these recovery techniques to restore functionality within minutes. This lab strengthened my understanding of Azure’s troubleshooting tools and taught me how to maintain uptime in both sandbox and production environments.

## 🎯 Lab Objectives Achieved: Redeploy & Reapply Azure VM

As part of this lab, I successfully:

- ✅ Identified the difference between **redeploying** and **reapplying** a virtual machine in Azure.
- ✅ Used the Azure portal to **redeploy a Windows-based VM**, resolving Remote Desktop (RDP) connectivity issues without losing configuration or data.
- ✅ Executed the **Reapply VM State** operation to recover a VM stuck in a failed provisioning state.
- ✅ Verified that all VM settings, disks, and networking remained intact after both recovery actions.
- ✅ Demonstrated practical troubleshooting skills for restoring VM health in real-world scenarios.
- ✅ Strengthened my confidence in maintaining uptime and reliability across Azure infrastructure.

This lab reinforced my ability to handle VM recovery operations with precision and clarity — a key skill for any cloud engineer working in production or sandbox environments.

## 📸 Screenshots

### Step 1: Click search box  
_Selected the Azure portal search box to locate services, resources, or troubleshooting tools for managing virtual machines and infrastructure. This step kicks off your navigation flow — perfect for launching into redeploy, reapply, or tagging actions._

![Click search box](Screenshots/Begin%20VM.png)

### Step 2: Type virtual machines and press Enter  
_Used the Azure portal search bar to find the target virtual machine, then navigated to its **Redeploy + reapply** blade to initiate host migration and provisioning recovery actions._

![Type virtual machines and press Enter ](Screenshots/Type%20Virtual%20Machine%20.png)
### Step 3: Click Virtual machines  
_Selected “Virtual machines” from the Azure portal search results to access the VM inventory and begin redeploy or reapply recovery actions. This step launches your troubleshooting workflow — ideal for restoring access._

![ ](Screenshots/From%20Serach%20result%20press%20VM.png)

### Step 4: Click on Server01  
_Selected `Server01` from the virtual machine inventory to open its overview page and access recovery actions like Redeploy and Reapply.This step initiates targeted troubleshooting — perfect for resolving RDP or provisioning issues._

![lick on Server01](Screenshots/Select%20Redploying%20VM.png)

### Step 5: Click Redeploy + reapply  
_Navigated to the “Redeploy + reapply” blade from the Server01 VM overview to initiate host migration or rerun provisioning for recovery and troubleshooting. This step is key for resolving RDP failures or failed provisioning states without altering your VM configuration._

![Click Redeploy + reapply](Screenshots/Click%20Redploy%20and%20Reapply.png)

### Step 6: Click Redeploy  
_Selected the “Redeploy” button to migrate Server01 to a new Azure host, resolving potential connectivity or infrastructure issues while preserving all VM settings. This step is a powerful recovery action — ideal for restoring access without rebuilding._

![Click Redeploy ](Screenshots/Click%20Redploy.png)

### Step 7: Click Overview  
_Returned to the “Overview” tab of Server01 to confirm the redeployment status and review updated VM health and connectivity details. This step wraps up the recovery flow — perfect for validating that your VM is back online and stable._

![Click Overview ](Screenshots/Click%20Overview.png)

 ### Step 8: Click the notification bell 
_in the top-right corner to view alerts or provisioning messages for this VM._

![Click the notification bell](Screenshots/Click%20Notification%20Bell.png)

### Step 9: Redeploying virtual machine  
_Confirmed that Server01 was successfully redeployed to a new Azure host. The operation resolved infrastructure-level issues while preserving all VM settings and resources._

![Redeploying virtual machine ](Screenshots/Click%20Redploy%20VM.png)

### Step 10: Click Refresh  
_Manually refreshed the Server01 overview page to confirm successful redeployment and ensure the VM status reflects its latest operational state._

![Click Refresh ](Screenshots/Click%20Refresh.png)

### ✅ Step 11: Click Refresh again  
_Refreshed the Server01 overview page to verify that the VM restarted successfully and retained its “Running” status post-operation._

![Click Refresh again](Screenshots/Click%20Refresh%20Again.png)

### Step 12: Click Redeploy + reapply  
_Accessed the “Redeploy + reapply” blade from the Server01 overview to initiate host migration or reapply provisioning for troubleshooting VM connectivity or failed state._

![Click Redeploy + reapply](Screenshots/To%20Replay%20Click%20Redploy%20&%20Reapply.png)

### Step 13: Click Reapply  
_Selected the “Reapply” button to rerun platform provisioning for Server01, resolving potential VM configuration or connectivity issues without changing infrastructure settings._

![Click Reapply](Screenshots/Click%20Reapply.png)

### Step 14: Click Notification bell  
_Opened the Azure portal notifications icon to track Replay or Replay+ progress and monitor VM telemetry attachment status._

![Click Notification bell](Screenshots/Click%20Notification%20Bell2.png)



### Step 15: Click Reapplying virtual machine  
_Executed the “Reapply” operation for Server01 to rerun platform provisioning and restore VM health. Verified success via notification panel showing “Succeeded” status. This step confirms a clean recovery — ideal for resolving failed states without changing infrastructure._

![Click Reapplying virtual machine](Screenshots/Click%20Reapply%20VM.png)

### Step 16: Click Refresh  
_Selected the “Refresh” button on the Server01 overview page to update the VM status and confirm that recent operations completed successfully._

![Click Refresh](Screenshots/To%20know%20the%20Status%20REFRESH.png)

> **Tip** This step is my final checkpoint — ideal for validating redeploy or reapply actions.