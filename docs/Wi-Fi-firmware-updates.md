---
title: Axon Body 3 Wi-Fi firmware updates
---

The Wi-Fi Firmware Updates feature enables cameras to download and install new operating system and firmware updates when in proximity to a preconfigured network. This functionality is available for all Axon Body 3 customers and is not dependent on any unique licenses.

This article provides information on the [in-field workflows](#In-Field Use) that occur on the camera when new firmware is available and installed via Wi-Fi. It also has information on some [errors and edge cases](#Error States and Edge Cases), and [Frequently Asked Questions (FAQs)](#Frequently Asked Questions).

Agency Axon Evidence administrators can enable the Wi-Fi Firmware Updates feature and workflow by setting up authorized Wi-Fi access points and then enabling the Axon Body 3 Wi-Fi Evidence Upload and Firmware Updates setting. For more information on how to enable and configure this feature, see the [Axon Body 3 Automatic Wi-Fi Upload](https://my.axon.com/s/article/AB3-Automatic-Wi-Fi-Upload?language=en_US#:~:text=Setting%20Up%20Body%20Camera%20Networks%20and%20Enabling%20the%20Setting) article.

**Note:** The Wi-Fi Firmware Updates feature requires Axon Body 3 camera Operating System v1.23 or later.

### In-field use

In the field, all Axon Body 3 cameras will utilize that preconfigured list of Body Camera Wi-Fi Networks to download new firmware updates when they are available. When Axon publishes a new firmware version to your agency, cameras will become aware of that update and attempt to download it when the following conditions are met:

1.  The camera already has Operating System v1.23 or later running.
2.  The camera is within range of a trusted Wi-Fi network previously configured in the Body Camera Wi-Fi Networks page of Axon Evidence.
3.  The camera is charging via a USB-C cable and already above 20% battery.
4.  The camera is not actively recording.

If all of these conditions are met, the camera will first download that new firmware within your agency’s Firmware Download Timeframe setting. This timeframe ranges from 2 to 8 hours, with a default of 6 hours, and is configurable on the Axon Body 3 Settings page in Axon Evidence. The camera will display a Wi-Fi symbol when it is successfully connected and a download symbol as it is downloading the firmware:  
  
![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN6Q&feoid=00Nf3000003DI8R&refid=0EMDo000000HkbM)

Once the firmware has successfully downloaded, the user will be prompted for 60 seconds with an opt-in message to install the firmware:  
  
![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN6Q&feoid=00Nf3000003DI8R&refid=0EMDo000000HkbR)

If the user presses the Select button on the camera at this time, the firmware will install on the camera. This will be displayed via flashing white LEDs and a sideways download icon followed by a camera reboot. At the time of boot up, the camera will be updated with the latest firmware version.  
**Note:** Because this reboots the camera, we recommend not pressing select to install the firmware if the camera is in active use.  
  
![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN6Q&feoid=00Nf3000003DI8R&refid=0EMDo000000Hkbb)

If the user ignores the opt-in prompt, it will disappear after 60 seconds and the camera will return to the READY state:  
  
![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN6Q&feoid=00Nf3000003DI8R&refid=0EMDo000000Hkbl)

If after four hours the prior conditions are still met (camera charging, above 20% battery, not recording), the camera will prompt the user with an opt-out message:  
  
![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN6Q&feoid=00Nf3000003DI8R&refid=0EMDo000000Hkbq)

The intention of waiting four hours is an attempt to apply the firmware when the camera is not in active use. However, if the user does see this message and is actively using the device, they can press the Select button to cancel the installation of the firmware. If this message is ignored for 60 seconds, then the firmware will install. This will be displayed via flashing white LEDs and a sideways download icon followed by a camera reboot. At the time of boot up, the camera will be updated with the latest firmware version.  
  
![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN6Q&feoid=00Nf3000003DI8R&refid=0EMDo000000Hkbv)

Other camera functionality is introduced with the Wi-Fi Evidence Upload and Firmware Updates setting enabled. When successfully connected to preconfigured Wi-Fi connections, cameras will also: sync time once per day, sync setting changes made on the Axon Body 3 Camera Settings page of Axon Evidence, sync changes to the Body Camera Wi-Fi Networks page of Axon Evidence, and upload evidence. To learn more about the workflow for evidence upload over Wi-Fi, see the [Axon Body 3 Automatic Wi-Fi Upload](https://my.axon.com/s/article/AB3-Automatic-Wi-Fi-Upload) article.

### Error states and edge cases

If a Wi-Fi network connection is lost or interrupted mid-download, the download will be paused. The download will resume when the previous conditions are met again.

Wi-Fi connectivity to applications, such as Axon View, Fleet 2 View XL, or Fleet 3 Dashboard will always be prioritized over the Wi-Fi Firmware Updates workflow. This means that if a download is occurring on the camera and then a user attempts to playback evidence in an application, then the download will be paused and the connectivity to support playback will be prioritized.

As a general rule, all active actions take precedence over a firmware download. As another example, if firmware is downloading over Wi-Fi on the camera and then a user begins recording a new piece of evidence, then the download will be paused and the camera will begin recording immediately. Anytime one of the previously mentioned conditions are broken or interrupted, the camera will pause its Wi-Fi download to support that active action.

### Frequently Asked Questions

We have added the following frequently asked questions and answers to clarify the expected behavior and aid with the use of the Wi-Fi Firmware Updates feature. If you have additional questions, contact Technical Support or your Axon representative for more information.

**Can cameras still be docked to receive firmware updates if this setting is enabled?**

Yes. If your agency uses camera docks, cameras can use that ethernet connection to download firmware, upload evidence, sync settings, and more. This Wi-Fi Firmware Updates workflow supports in-field updates, but there is no issue with utilizing docks as another source of connection.

**What happens if one of the conditions is broken when firmware is downloading?**

If your camera either 1) loses connection to Wi-Fi, 2) stops charging via USB-C, 3) drops below 20% battery, or 4) begins recording, the firmware download will pause. It will resume again once all required conditions are met again.

**Can my camera support firmware updates via Wi-Fi while in Sleep Mode?**

Yes. It is common that users will have their camera in Sleep Mode during off-shift periods for privacy purposes. Because of that, we support Wi-Fi Firmware Updates while the camera is in Sleep Mode as long as it meets the previously mentioned conditions.

**What happens if the opt-in or opt-out messages are interrupted by a different button press or action?**

If the opt-in or opt-out message is displayed as another camera action takes place, such as the Event Button being pressed or a Signal Event occurring, the message will disappear and the other action will take precedence. The camera will then follow the logic of attempting to install again four hours later if the conditions are met.

**How will the camera handle evidence upload and firmware downloads over Wi-Fi?**

If the camera has evidence on the device when it’s connected to Wi-Fi, that evidence will attempt to upload. The camera can concurrently download firmware via that same Wi-Fi connection if the prior conditions are met. To learn more about Automatic Wi-Fi Upload, see the [Axon Body 3 Automatic Wi-Fi Upload](https://my.axon.com/s/article/AB3-Automatic-Wi-Fi-Upload) article.

**What functions can occur over the preconfigured Body Camera Wi-Fi Networks?**

With the Axon Body 3 Wi-Fi Evidence Upload and Firmware Updates setting enabled and at least one network configured on the Body Camera Wi-Fi Networks page, the Axon Body 3 can do the following functions over Wi-Fi when in proximity:

*   Upload evidence
*   Download and install firmware
*   Sync time
*   Sync agency-wide settings, including new, edited, or deleted Body Camera Wi-Fi Networks

**What functions are not supported over Wi-Fi?**

Currently, the main function that still requires the ViewXL Standalone application or an ethernet-connected dock is camera registration. After registration, all in-field operations are now supported via Wi-Fi.