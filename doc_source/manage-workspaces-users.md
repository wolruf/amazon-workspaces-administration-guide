# Manage WorkSpaces Users<a name="manage-workspaces-users"></a>

Each WorkSpace is assigned to a single user and cannot be shared by multiple users\. Whenever you launch a WorkSpace, you must assign it to a user that does not already have a WorkSpace\.

As an administrator for Amazon WorkSpaces, you can use the Amazon WorkSpaces console to perform the following tasks to manage WorkSpaces users\.

## Edit User Information<a name="edit-user"></a>

You can use the Amazon WorkSpaces console to edit the user information for a WorkSpace\.

**Note**  
This feature is available only if you use Microsoft AD or Simple AD\. If you use Microsoft Active Directory through AD Connector or a trust relationship, you can manage users and groups using [Active Directory Users and Computers](https://technet.microsoft.com/en-us/library/cc754217.aspx)\.

**To edit user information**

1. Open the Amazon WorkSpaces console at [https://console\.aws\.amazon\.com/workspaces/](https://console.aws.amazon.com/workspaces/)\.

1. In the navigation pane, choose **WorkSpaces**\.

1. Select a user and choose **Actions**, **Edit User**\.

1. Update **First Name**, **Last Name**, and **Email** as needed\.

1. Choose **Update**\.

## Send an Invitation Email<a name="send-invitation"></a>

You can send an invitation email to a user manually if needed\.

**To resend an invitation email**

1. Open the Amazon WorkSpaces console at [https://console\.aws\.amazon\.com/workspaces/](https://console.aws.amazon.com/workspaces/)\.

1. In the navigation pane, choose **WorkSpaces**\.

1. Select the user to send the invitation to and choose **Actions**, **Invite User**\.

1. Copy the email body text and paste it into an email to the user using your own email application\. You can modify the body text if desired\. When the invitation email is ready, send it to the user\.