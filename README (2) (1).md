# Connecting EC2 to Active Directory

## Prerequisites
- Ensure your EC2 instance is in a **running state** and has passed all three marks in the **status check**.  

## Steps

1. Select **Windows** on the instance.  
2. Click on the **Connect** option.  
3. In the **RDP Client** tab, scroll down and select **Download Remote Desktop File**.  
   - After it downloads, a window will pop up prompting you for a password.  
4. On the **RDP Client** tab, select **Get Password**.  
5. Choose the option to **Upload Private Key File**.  
   - Use the private key created in the previous lab.  
   - Navigate to the **files folder** from the earlier lab, select the Windows test key, and click **Open**.  
6. **Decrypt** the private key file to get the password.  
7. Scroll down and **copy the password**.  
8. Go back to the password prompt window and **paste** the password.  
9. Press **Continue** and then **Connect**.  
10. The system will configure and continue working in the background.  

## Result
You will now have a **working Windows virtual machine** connected through Remote Desktop.
