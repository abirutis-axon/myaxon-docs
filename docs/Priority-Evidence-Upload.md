---
title: Axon Body 3 Priority Evidence Upload
---

This feature lets you wirelessly upload the most recently recorded piece of evidence on your camera to Axon Evidence using its LTE connectivity.

Several factors can affect the performance, speed, and battery impact of uploading evidence by LTE. With strong LTE coverage, a 15-minute recording at 720H will take five minutes to upload and use about 2%, or 12 minutes, of battery capacity. With poor LTE coverage, this same recording may take 15 minutes to upload and use about 4%, or 24 minutes, of battery capacity.

Axon Body 3 cameras can continue to buffer and record new evidence normally while evidence is uploading by LTE.

This feature is only available for Axon Respond for Devices+ agencies. Agency Axon Evidence administrators can enable it and its workflow by turning on the Priority Evidence Upload setting in the Evidence Upload section on the Axon Body 3 Settings page:

![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021znn)

### Initiating a Priority Evidence Upload from the camera

1.  Press the **Program** and **Power** buttons simultaneously to open the camera's diagnostic menu.  
      
    ![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021znx)
2.  Use the **Volume Up** or **Volume Down** button to highlight **Upload Last**, then press **Select**.  
      
    ![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zo2)
3.  If there is evidence on the device, the Upload Last submenu displays with two options, **BACK** and **UPLOAD**. The top of the Upload Last submenu shows the start time of the recording followed by the recording duration in parenthesis.  
      
    ![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zo7)  
    If there is no evidence on the device, the display shows NO EVIDENCE.  
      
    ![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zoC)  
    Use the **Volume Up** or **Volume Down** buttons to select an option, then press **Select**.
    
    *   Choosing **BACK** will not upload any evidence and the display will return to the diagnostic menu.
    *   Choosing **UPLOAD** uploads the last evidence saved on the camera and displays UPLOAD STARTED.  
          
        ![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zoH)
    
      
    Once an upload has started, the upload icon displays at the bottom right when the camera is READY or RECORDING.  
      
    ![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zol)  
    Additionally, the diagnostic menu confirms the upload is in progress by displaying **Uploading**.  
      
    ![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zoq)  
    Once the evidence has uploaded successfully, **UPLOAD COMPLETE** flashes on the display and the evidence is deleted from the camera.  
      
    ![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021znZ)

### Cancel an upload

1.  Press **Program** and **Power** buttons simultaneously to open the diagnostic menu. 
2.  Use the **Volume Up** or **Volume Down** button to highlight **Uploading**, then press **Select**.  
      
    ![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zpA)
3.  Use the **Volume Up** or **Volume Down** buttons to highlight **CANCEL**, then press **Select**.  
      
    ![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zp1)  
    A confirmation message displays for three seconds and the upload is canceled. The evidence will remain on the device until it is uploaded by LTE, dock, or View XL standalone mode.  
      
    ![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zpF)

### Error states and edge cases

Priority Evidence Upload may display the following error messages. This section also describes certain LTE upload conditions.

**Evidence exceeds upload limit**

Recordings longer than 60 minutes cannot be completed using LTE due to the size of the file. Dock the camera or use View XL standalone mode to offload this evidence.

![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zpK)

**Upload paused: poor signal**

If the camera loses LTE coverage during an upload, it pauses and the camera displays this message along with a Pause icon. If LTE coverage returns within 10 minutes, the upload will resume, otherwise the upload is canceled and the evidence remains on the camera. 

![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zpP)

![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zpU)

**Upload paused: USB-C connected**

An LTE upload will pause when you connect a USB-C cable. The upload will resume when you disconnect the cable.

![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zpZ)

**Camera shut-down due to low battery**

If the camera shuts down due to a low battery during an LTE upload, the upload pauses and the evidence remains on the device. The upload will resume when the camera is charged and turned back on.

**Docked camera**

If you dock your camera during an LTE upload, the upload will continue using the dock’s ethernet connection, with the Priority Evidence Upload taking priority.

**Upload timed out**

If the upload takes longer than two hours (which may occur if LTE coverage is poor and/or the file size is large), the upload pauses and the camera displays this message. Select to either Resume or Cancel the upload.

![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zpj)

**Upload paused: livestream**

If you livestream into a camera that is actively uploading evidence via LTE, the upload pauses to allow the livestream. The upload resumes when the livestream ends.

![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zpo)

The Pause icon displays on the READY and RECORDING screens whenever an upload is paused.

![](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZN4t&feoid=00Nf3000003DI8R&refid=0EM4y0000021zqD)