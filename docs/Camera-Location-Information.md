---
title: Camera Location Information
---

Axon Body 4 cameras can report location data to Axon Respond and Axon Evidence while recording and buffering.

Agency Axon Evidence administrators can set the camera location settings on the Axon Evidence Axon Body 4 settings page.

![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000ZNPX&feoid=00Nf3000003DI8R&refid=0EMDo000001dGNs)

The default setting is **Location available when camera recording**, which only makes camera location available to Axon Respond and Axon Evidence when the camera is recording.

When the **Location available when camera is recording and buffering** setting is selected, camera location will be reported to Axon Respond and Axon Evidence while the camera is recording and while the camera is buffering.  
  
In general, camera location is available in both the browser and mobile application of Axon Respond. Camera location while the camera is buffering is updated on the Respond platform every 15 minutes and will be denoted on the map with a device marker. Camera location while recording is updated every few seconds. The location map on the Axon Evidence Device Profile page is updated with the same frequency as the Respond platform.  
  
A camera will not provide location updates to the Respond map if it is docked or connected to a USB cable (cameras will update location when in [Sleep Mode](https://my.axon.com/s/article/Axon-Body-3-Sleep-Mode)). If a camera has been removed from the Respond map due to Respond Device Location Filter setting, then it will not appear on the Respond map until it begins recording.  
  
_Example:_ An agency has selected the Location available when camera is recording and buffering setting and has set the Respond Device Location Filter to Within 4 hours. If a camera is docked for more than 4 hours, it is removed from the Respond map and will not appear again until it begins recording.

**Important:** Choosing the **Location available when camera is recording and buffering** setting will affect battery charge levels. Users can expect to see a 5–10 minute reduction in camera runtime with this option.