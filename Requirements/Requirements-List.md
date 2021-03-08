# [ViridianKrypton](/main/readme.md#viridiankrypton "Return to README.md")
	
## Table of Contents  

### [1. Requirements List](#requirements-list)   
### [2. Test Table](#test-table)  
### [3. License](#license)  
	
## [Requirements List](#1-requirements-list)  
[Return to README.md](/main/readme.md#6-requirements--test-methods)  
>	The system shall...

| Requirement ID | Requirement Description | Test Method |
| ---- | ---- | ---- |
| R1 | Create user accounts upon request | Demonstration | |
| R1.1 | Populate user profile either from user input, linked accounts, or user's Electronic Health Record | Test |
| R1.2 | Get user privacy preferences and/or set defaults | Test |
| R1.2.1 | Be able to modify scans to adjust level of detail and anonymity | Test |
| R2 | Display selected scans to user | Demonstration |
| R2.1 | Allow user to manipulate displayed scan (rotate, zoom, etc.) | Demonstration |
| R2.1.1 | Display preview results of changes to privacy settings | Demonstration |
| R2.1.2 | Allow changing privacy settings from 3d render display screen | Test |
| R2.2 | Enable browsing for files and execution of common file operations | Test |
| R3 | Associate user data with scan files | Inspection |
| R3.2.1 | Add metadata from user profile to appropriate templates | Test |
| R4 | Transmit 3D renders of scans to authorized users upon request | Demonstration |
| R4.1 | Compress/decompress data for transit | Inspection |
| R4.2 | Authenticate users and requests | Inspection |
| R5 | Adhere to privacy laws and standards | Inspection |
| R5.1 | Encrypt data in transit and at rest | Inspection |

*This list is a living document. Requirements may be added or removed as the project progresses.*

## [Test Table](#2-test-table)
[Return to README.md](/main/readme.md#6-requirements--test-methods)
> Unit testing  
> Integration testing  
> System testing  
> Acceptance testing  

| Test ID | Requirement ID(s) | Test Procedure | Current Status | Time Stamp | Build Version |
| ---- | ---- | ---- | ---- | ---- | ---- |
| Number | Number | Detailed Instructions | Passed/Failed/Not Tested | If Tested | If Tested |
| T1 | R1 | Create a user account | Not Tested | | |
| T1.1 | R1.1 | Populate User Profile Data | Not Tested | | |
| T1.1.1 | R1.1 | Retrieve user data from User Input | Not Tested | | |
| T1.1.2 | R1.1 | Retrieve user data from Linked Accounts | Not Tested | | |
| T1.1.3 | R1.1 | Retrieve user data from Electronic Health Record | Not Tested | | |
| T1.2 | R1.2 | Populate User Privacy Preferences | Not Tested | | |
| T1.2.2 | R1.2 | Modify Scan Detail | Not Tested | | |
| T1.2.3 | R1.2 | Modify Scan Identity Metadata | Not Tested | | |
| T1.2.4 | R1.2 | Set Default Privacy Preferences | Not Tested | | |
| T1.2.5 | R1.2 | Set Privacy Preferences from User Input | Not Tested | | |
| T2 | R2 | Display a scan on the User Dashboard | Not Tested | | |
| T2.1.1 | R2.1 | Rotate a displayed scan | Not Tested | | |
| T2.1.2 | R2.1 | Zoom a displayed scan | Not Tested | | |
| T2.1.3 | R2.1.1 | Preview privacy settings on a displayed scan | Not Tested | | |
| T2.1.3 | R2.1.2 | Change privacy settings from User Dashboard | Not Tested | | |
| T2.2.1 | R2.2 | Browse for files on local machine | Not Tested | | |
| T2.2.2 | R2.2 | Save files to local machine | Not Tested | | |
| T3 | R3 | Add user metadata to a scan file | Not Tested | | |
| T3.1.1 | R3.2.1 | Retrieve user metadata from user profile | Not Tested | | |
| T4 | R4 | Transmit a render of a scan, processed according to user privacy preferences, as input to an API | Not Tested | | |
| T4.1 | R4.1 | Compress render for transmission, check filesize against original | Not Tested | | |
| T4.1.1 | R4.1 | Decompress receive render, check file hash against original | Not Tested | | |
| T4.2.1 | R4.2 | Authenticate Users | Not Tested | | |
| T4.2.2 | R4.2 | Authenticate Requess | Not Tested | | |
| T5 | R5 | Check app against legal privacy laws & standards using an appropriate checklist | Not Tested | | |
| T5.1 | R5 | Inspect whether appropriate encryption methods are in use | Not Tested | | |
| T5.1.1 | R5.1 | Check a sample of files in storage for encryption | Not Tested | | |
| T5.1.2 | R5.1 | Check a sample of files in transit for encryption | Not Tested | | |

##### License
Copyright: Kurt Woodward (2021)  
All rights reserved.  
[Back to top](#viridiankrypton)
