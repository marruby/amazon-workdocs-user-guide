# Troubleshooting Amazon WorkDocs Drive<a name="drive_troubleshoot"></a>

This section provides troubleshooting tips for common Amazon WorkDocs Drive errors\.

**Recovered Files**  
If you change a file that you don't have permissions to edit, you can't upload that file to your Amazon WorkDocs site\. Instead, the site saves the changes to your local `Recovered Files` folder\. You can open this folder from the Amazon WorkDocs Drive menu by choosing the question mark icon, then **Go to recovery folder**\. From there, you can upload the file to Amazon WorkDocs as a new file\.

**Recovery Folder Full**  
Delete unnecessary files from your local `Recovered Files` folder\.

**Drive Repair Required**  
**Windows** – Restart by opening the Amazon WorkDocs Drive settings and choosing **Log out \(change site\)**\. Repeat those steps to sign in again, and tnen check the `Recovered Files` folder for any files you might need to save\. If you don't remember how to open the settings, see [Opening the Amazon WorkDocs Drive settings in Microsoft Windows](open-wdd-settings.md)\.  
**macOS** – Restart Amazon WorkDocs Drive by choosing the **Amazon WorkDocs Drive** icon on the menu bar, choosing the gear icon, then choosing **Log out**\. Repeat those steps to sign in again, and then check the `Recovered Files` folder for any files you might need to save\.

**Local Disk Full**  
Delete unnecessary files from your local disk and `Recovered Files` folder\.

**Storage Limit Exceeded**  
Delete unused files to free up storage space\. If you need more space after deleting unused files, contact your Amazon WorkDocs administrator\.

**Critical Dependency Unavailable**  
Restart the **Message Queuing** service on your computer by opening the **Services** app\. For **Message Queuing**, choose **Restart** or **Start**\.  
If the error persists, open **Computer Management**, **Services and Applications**\. If **Message Queuing** does not appear in the navigation pane, [uninstall **Message Queuing**](https://docs.particular.net/transports/msmq/uninstalling-msmq) and Amazon WorkDocs Drive\. When you reinstall Amazon WorkDocs Drive, it reinstalls **Message Queuing** for you\. For more help, contact your administrator\.

You can also report an issue from the Amazon WorkDocs Drive menu\.

**Report an Issue**  
You use the Amazon WorkDocs Drive task pane to report issues\. 

**To report an issue**

1. Open the Amazon WorkDocs Drive task pane\. If you don't remember how, see steps 1 and 2 in [Opening the Amazon WorkDocs Drive settings in Microsoft Windows](open-wdd-settings.md)\. 

1. Choose the question mark icon, and then choose **Report an issue** to send us a description of the problem\. Note the tracking number\. It serves as a reference for support cases or correspondence with us\.

**Known Limitations**  
Amazon WorkDocs Drive doesn't support Symlinks\.