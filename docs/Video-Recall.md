---
title: Axon Body 3 Video Recall
---

The Video Recall feature lets Axon Body 3 cameras capture lower-resolution evidence when the camera is not actively recording, with optional audio. With the appropriate permissions, users can then retrieve/recall evidence from a period within the last 18 hours of active camera use in the event that a camera was not recording during a critical incident but evidence is needed.

This article provides information on how to [enable Video Recall](#Enabling) on devices in your agency, the required [Role permission setting](#Permission), the [Video Recall evidence specifications](#Specifications), and how to use [Axon View XL Standalone Mode to recall/retrieve evidence](#Retrieve) from the Video Recall storage.

The Video Recall feature is available for all Axon Body 3 agencies without any additional add-ons or licenses.

Enable Video Recall
-------------------

Agency Axon Evidence administrators can enable the Video Recall feature and workflow by turning on the Video Recall setting in the Video section on the Axon Body 3 Settings page. This setting is disabled by default upon the release of Video Recall and must be manually enabled by an agency administrator before use of the feature.

![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN5m&feoid=00Nf3000003DI8R&refid=0EM4y000001kXQg)

In addition to enabling the Video Recall setting, Axon Body 3 cameras must have OS version 1.15 or higher to capture Video Recall evidence.  
  
Administrators can also enable audio capture in Video Recall recordings by turning on the Audio in Video Recall setting in the Audio section. This setting is also disabled by default and must be manually enabled before audio is captured.  
  
![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN5m&feoid=00Nf3000003DI8R&refid=0EM4y000004cmy2)

Video Recall permission
-----------------------

Agency Axon Evidence administrators must enable the Access Video Recall Files permission for the Roles that will use Video Recall before users can access and use the feature.

![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN5m&feoid=00Nf3000003DI8R&refid=0EM4y000001kXQv)

### Enable Video Recall permission

Administrators can modify existing Roles, create new Roles, or copy and modify an existing Role to enable the Video Recall permission.

1.  On the menu bar, click **Admin** and then under Agency Settings, click **Roles & Permissions**. The Roles & Permissions page lists available roles in alphabetical order.
2.  The next action depends on if you are creating a new Role or editing an existing Role.
    *   To create a new Role - click **Create Role**, then enter the Role Name and select the license Tier.
    *   To edit a Role - click the edit icon on the same line as the role that you want to edit.
3.  Scroll down to the Evidence Management section and set the Access Video Recall Files permission for the Role to **Allowed**.
4.  When you have finished setting all the permissions for the Role, scroll to the bottom of the page and then click **Save**. Axon Evidence immediately begins enforcing the changes to permissions that you made.
5.  Once all your Roles have been created or edited, check that users are assigned to the appropriate roles.

AB3 Video Recall Evidence specifications
----------------------------------------

**How it works**

*   Video Recall files are captured in 30-minute increments while the camera is buffering.
*   Video Recall capture is stopped when the camera is in Sleep mode, Off, Docked, Recording, or actively plugged into View XL Standalone Mode.
*   Video recall files are recoverable from the last 18 hours of buffering, and there is a storage reserve specifically for Video Recall evidence.
*   The camera begins overwriting the oldest video recall files after the 18 hours of storage reserved for Video Recall becomes full.
*   Video Recall evidence is recorded in SD (Standard Definition - 480p) when the camera is on and buffering.
*   Recalled video is uploaded into Axon Evidence after selection.
*   Recalled video is uploaded with a unique watermark, title, and tag to help easily identify it.
*   Enabling this feature can impact Axon Body 3 camera battery capacity, reducing charge by approximately 30-minutes for 12 hours of buffering runtime.
*   The reserved storage for Video Recall is about 15%, or 8GB, of total recording storage. 

**Privacy functions**

*   Video Recall is designed with officer privacy in mind and captures audio only if separately enabled.
*   Recalling evidence requires specific, agency-configurable administrative rights using the View XL Standalone Mode.
*   Recalling evidence also requires physical access to the camera. So an officer will know their camera is being requisitioned.
*   The camera must be physically plugged into a computer running View XL Standalone Mode to recall evidence on the device.
*   The 18-hour buffer cannot be played back in View XL Standalone. Evidence must be recalled into Axon Evidence before playback and metadata editing is possible.
*   Device audit logs indicate who recalled evidence and when.

Retrieving Video Recall evidence
--------------------------------

The Axon Body 3 Video Recall feature adds a new Video Recall tab to View XL Standalone Mode. The Video Recall tab is only visible to users assigned to Roles with the Access Video Recall Files permission enabled.

The Video Recall tab shows files that have been captured in the past 18 hours while the camera was buffering that are available for upload. These files are captured in 30-minute increments and are noted by timestamp of the recording start time and duration of the file. If a Video Recall file duration is less than 30 minutes, this means the Video Recall recording was interrupted by a different camera state, such as being in placed in Sleep Mode, docked, powered off, plugged into View XL Standalone, or actively recording. When the camera returns to buffering Video Recall recording resumes with a new file.

Users can select Video Recall files for upload in the Video Recall tab. The selected files are placed in the upload queue and are uploaded to Axon Evidence. Users cannot view Video Recall evidence nor edit metadata prior to upload. User can view the status of the file uploads by going to the Upload tab. Once uploaded, the Video Recall evidence functions as normal evidence in Axon Evidence with the ability to playback and edit metadata.

![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN5m&feoid=00Nf3000003DI8R&refid=0EM4y000001kXR0)

### Uploading Video Recall evidence

1.  Sign into View XL and launch Standalone Mode. See the [Signing In and Connecting an Axon Body 3 Camera help article](https://my.axon.com/s/article/View-XL-Standalone-Mode---Signing-In-and-Connecting-an-Axon-Body-3-Camera) on My Axon for information about signing in to View XL.
2.  Click the Video Recall icon.
3.  Review the Video Recall file timestamps to find the files you want to upload. Files are captured in 30-minute increments and the timestamp shows the recording start time of the file.  
    ![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN5m&feoid=00Nf3000003DI8R&refid=0EM4y000001kXRe)
4.  Select Video Recall files you want to upload.  
      
    The Recall Video file is placed into the Uploads queue. While uploading, the file is still shown in the Video Recall tab with an uploading state until upload completes.  
    ![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN5m&feoid=00Nf3000003DI8R&refid=0EM4y000001kXRj)  
      
    You can monitor the status of the upload by going to the Upload tab. Then be removed from the Video Recall tab list.  
    ![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN5m&feoid=00Nf3000003DI8R&refid=0EM4y000001kXS8)  
      
    After the file is uploaded, it will appear in Axon Evidence with a unique title, a Video Recall tag, and watermark indicating that it was captured during the Video Recall recording and not as part of an active recording.  
    ![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN5m&feoid=00Nf3000003DI8R&refid=0EM4y000001kXSI)