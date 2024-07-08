---
title: Camera registration - Axon Body 4
---

Before an Axon Body 4 camera can be used, it must be registered to your agency. This guide provides information about the out-of-the-box registration process for Axon Body 4 cameras. Additionally, Axon recommends fully charging and assigning an Axon Body 4 camera before using the camera.

Cameras can be registered using View XL in Standalone mode or using Axon Device Manager. The camera’s display will show **DOCK DEVICE OR CONNECT VIEWXL** if you can use View XL Standalone mode or Axon Device Manager to register the camera. Cameras that show **DOCK DEVICE** must be registered with Axon Device Manager.

*   [Axon Body 4 Camera Registration with Axon View XL Standalone Mode](#h_01EQ9QJSSEMECW7GV072GSZ3VT)
*   [Axon Body 4 Camera Registration with Axon Device Manager](#h_01EQ9QK1C6AVC0X4FS2C12E3YS)

![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZNLL&feoid=00Nf3000003DI8R&refid=0EMDo000001fbVP)

Axon Body 4 Camera Registration with Axon View XL Standalone Mode
-----------------------------------------------------------------

**Prerequisites:**

*   View XL v1.14 or greater
*   Axon Body 4

**Process**

1.  Power on the camera by pressing the **Power** button on the top of the camera. Verify the camera display shows **DOCK DEVICE OR CONNECT VIEWXL**.
2.  On your computer, sign in to View XL and launch Standalone mode.
3.  Plug the USB-A to USB-C cable into a USB port on the laptop/computer and then plug the cable into an Axon Body 4 camera that is powered on.
4.  If the camera is unregistered, you will be prompted to Register the camera. Click **Register** to continue. The registration process can take up to 20 seconds.
5.  Once successful, click **OK** and the camera will automatically connect to View XL where it can be assigned as needed.
6.  Following registration, agency camera settings from Axon Evidence are checked and applied to the camera. Power the camera off and then on again to allow any resolution configuration changes to apply.

Axon Body 4 Camera registration with Axon Device Manager
--------------------------------------------------------

**Prerequisites:** In addition to an Axon Body 4 camera, registration requires:

*   [Installing Axon Device Manager](https://my.axon.com/s/article/Installing-Axon-Device-Manager) (ADM) installed on an appropriate device - If you already have ADM installed, ensure you have v3.0.3 (Android) or v2.0.3 (iOS) or higher.  
      
    You must have [Axon Device Manager Permissions](https://my.axon.com/s/article/Axon-Device-Manager-Permissions) to use ADM. If you aren’t sure if you have permissions to use ADM, contact an Axon Evidence administrator for your agency to check on your permissions.

*   An Axon Body 4 Dock connected to power and the Internet (a green LED is visible on the WAN port). Your dock does not need to be registered. See the _Axon Body 4 Dock Installation Manual_ for information on installing a dock.

Before starting, Axon recommends that you familiarize yourself with the camera buttons by reviewing the information in the _Axon Body 4 User Guide_.

You can register multiple cameras, up to 100, at one if you have an Axon Dock bay for each camera. You must keep your mobile device with ADM within 30 feet of all the cameras you are registering.

1.  Un-box the Axon Body 4 camera. Power on the camera by pressing the **Power** button, on top of the camera, until you feel short vibration.   
    ![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZNLL&feoid=00Nf3000003DI8R&refid=0EMDo000001fbVZ)  
    The camera starts and the camera display, on top of the camera, shows **DOCK DEVICE**.
2.  Place the camera in the Axon Body 4 Dock. The camera display shows **REGISTER DEVICE**. 
3.  Open ADM and tap **Settings** ![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZNLL&feoid=00Nf3000003DI8R&refid=0EMDo000001fbVj) in the upper left.
4.  Under the Registration heading, tap **Devices** and then tap **Axon Body 4**.  
    ![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZNLL&feoid=00Nf3000003DI8R&refid=0EMDo000001fbVo)
5.  Review the device registration setup and tap **Next** twice to move to the next screen. Tap **Start Scan** when you are ready to start the registration process.
6.  ADM detects and prepares unregistered cameras. The number of detected and prepared cameras appears at the top of the ADM screen. 
    
    *   When a camera is prepared, camera display will show your agency name and the Operation and Triad LEDs blink green. 
    *   Go to the camera and press the **Select** button (located between the volume buttons). You must confirm the registration by pressing the **Select** button.  
         ![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZNLL&feoid=00Nf3000003DI8R&refid=0EMDo000001fbVy)
    *   If successful, the display will change to show **NOT ASSIGNED** to indicate the camera is ready to be assigned to a user.   
        ![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZNLL&feoid=00Nf3000003DI8R&refid=0EMDo000001fbWD)
    
      
    Keep cameras docked for at least 30 seconds after registering the device to allow for post-registration communication with Axon Evidence.
7.  When you have registered all the detected cameras, tap **Finish**. ADM shows a list of camera serial numbers that have been registered at your agency during this session.  
    Cameras that are successfully registered can be charged and assigned to users.

### Troubleshooting

If there is a problem with preparing the camera, ADM will show an error. Tap **Errors** to review the error information on ADM. If you are unable to register ANY cameras, this may be potentially a connectivity issue. Please reference the [Managing Network Whitelisting with Axon Cloud Services](https://my.axon.com/s/article/Managing-Network-Allowed-Lists-with-Axon-Cloud-Services) to ensure that the appropriate networks ports are open.

If SOME cameras are registering but others are not, this may be a transient error. Android devices tend to experience more transient errors than iOS devices. A suggested general troubleshooting approach is to:

1.  Start with only one camera docked at a time.
2.  Attempt to register. If registration error occurs, tap **Dismiss All** allow ADM to retry registration.
3.  If registration fails again, power off the camera and then power it on and repeat the registration process.

The following table provides information about the error codes and suggested actions.

**Error Code**

**Description**

**Troubleshooting Action**

\-1

Communication to Axon Body 4 has failed

Power the camera off, then power the camera back on and retry registration.  
  
If attempting to register large number of cameras in close proximity and you see this error, retry registration with individual camera.  
  
If error occurs again, tap **Dismiss All** and allow ADM to retry registration.

33, -7249973, 43 or 49

Camera time is inaccurate

Sign out and back into ADM.   
  
Power the camera off, then power the camera back on and allow the camera to remain docked for 2 minutes to allow sufficient time to synchronize the camera time.   
  
Confirm your agency network settings allow network communication from dock to Axon Evidence through port 80 and port 443. For more information, see [Managing Network Whitelisting with Axon Cloud Services](https://my.axon.com/s/article/Managing-Network-Allowed-Lists-with-Axon-Cloud-Services)

45 or 47

Camera is unable to reach the internet

Power the camera off, then power the camera back on and allow camera to remain docked for 1 minute prior to retrying. It will take about 30 seconds to establish an internet connection. Tap **Dismiss All** and allow ADM to retry the registration.  
  
If the error persists after retrying to register several times, check the internet connection and troubleshoot the dock internet connection. Common connection issues include agency firewall settings.

46

Camera is unable to reach your agency's Axon Evidence account

Sign out and back in to ADM. If you can sign in, retry registration. Otherwise, contact Axon Technical Support to see if there are any issues with Axon Evidence.

34, 48, or 50

Camera provisioning issue

Power the camera off, then power the camera back on and retry registration.  
  
If the error persists, contact your Axon Evidence administrator to confirm that Device Management permission is enabled.   
  
If Device Management permission is enabled, please contact your Axon representative or Axon Technical Support for assistance.