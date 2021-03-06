# Amazon WorkSpaces Chromebook Client Application<a name="amazon-workspaces-chromebook-client"></a>

The following information will help you get started with the Amazon WorkSpaces Chromebook client application\.

**Topics**
+ [Requirements](#chromebook-requirements)
+ [Setup and Installation](#chromebook_setup)
+ [Connecting to Your WorkSpace](#chromebook_connecting)
+ [Gestures](#chromebook_gestures)
+ [Release Notes](#chromebook-release-notes)

## Requirements<a name="chromebook-requirements"></a>

The Amazon WorkSpaces Chromebook client application requires a Chromebook with Chrome OS version 45 or later\.

The client application works on most Chromebooks with version 45 or later, but some devices might not be compatible\. If you have problems with a device, you can report the problem on the [Amazon WorkSpaces forum](https://forums.aws.amazon.com/forum.jspa?forumID=164)\.

To check the version of Chrome OS, click the status area, where your account picture appears\. Click **Settings**, **About Chrome OS**\.

## Setup and Installation<a name="chromebook_setup"></a>

To download and install the client application, complete the following procedure\.

**To download and install the client application**

1. On your Chromebook, open [http://clients\.amazonworkspaces\.com/](http://clients.amazonworkspaces.com/) and choose the link for your Chromebook\.

1. Download and install the application\.

1. Verify that the Amazon WorkSpaces client application icon appears in your Chromebook search\.

## Connecting to Your WorkSpace<a name="chromebook_connecting"></a>

To connect to your WorkSpace, complete the following procedure\.

**To connect to your WorkSpace**

1. On your Chromebook, open the Amazon WorkSpaces client application\.

1. The first time that you run the client application, you are prompted for your registration code, which is contained in your welcome email\. The Amazon WorkSpaces client application uses the registration code and user name to identify which WorkSpace to connect to\. When you launch the client application later, the same registration code is used\. You can enter a different registration code by launching the client application and choosing **Enter new registration code** on the login screen\.

1. Type your user name and password and choose **Sign In**\. If your Amazon WorkSpaces administrator has enabled multi\-factor authentication for your organization's WorkSpaces, you are prompted for a passcode to complete your login\. Your Amazon WorkSpaces administrator will provide more information about how to obtain your passcode\.

1. If your Amazon WorkSpaces administrator has not disabled the "Remember Me" feature, you are prompted to save your credentials securely so that you can connect to your WorkSpace easily in the future\. Your credentials are securely cached while the application is running\.

   After the client application connects to your WorkSpace, your WorkSpace desktop is displayed\.

   \(Optional\) If your WorkSpace uses an AD Connector directory, you can update the maximum lifetime of the Kerberos ticket by following the steps in [Configuring Kerberos Policies](http://technet.microsoft.com/en-us/library/dd277401.aspx) in the Microsoft TechNet Library\. If you need to disable the "Remember Me" feature, search for help in the [Amazon WorkSpaces forum](https://forums.aws.amazon.com/forum.jspa?forumID=164)\.

## Gestures<a name="chromebook_gestures"></a>

The following are the gestures that are supported for the Amazon WorkSpaces Chromebook client application\.

Single tap  
Equivalent to a single click in Windows\.

Double tap  
Equivalent to a double click in Windows\.

Two finger single tap  
Equivalent to a right\-click in Windows\.

Two finger scroll  
Scrolls vertically\.

## Release Notes<a name="chromebook-release-notes"></a>

The following table describes the changes to each release of the Chromebook client application\.


| Release | Changes | 
| --- | --- | 
|  2\.4\.2  |  Fixed a bug with Caps Lock  | 
|  2\.4\.0  |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/workspaces/latest/userguide/amazon-workspaces-chromebook-client.html)  | 
|  2\.2\.7  |  Fixed minor issues  | 
|  2\.2\.4  |  Localization enhancements  | 
|  2\.2\.1  |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/workspaces/latest/userguide/amazon-workspaces-chromebook-client.html)  | 
|  2\.1\.3  |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/workspaces/latest/userguide/amazon-workspaces-chromebook-client.html)  | 
|  2\.0\.0  |  [\[See the AWS documentation website for more details\]](http://docs.aws.amazon.com/workspaces/latest/userguide/amazon-workspaces-chromebook-client.html)  | 
|  1\.0  |  Initial release  | 