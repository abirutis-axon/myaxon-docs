---
title: Location services - Axon Body 4
---

The Axon Body 4 camera uses two technologies for determining camera location: Global Navigation Satellite System (GNSS) and Wi-Fi Positioning System. This article provides an overview of the Axon Body 4 camera location services, how this information is used in Axon Evidence and Axon Respond, and includes some [Frequently Asked Questions](#h_4212b612-0ef6-4fcb-bb72-e922607700ee).

### Global Navigation Satellite System (GNSS)

Global Navigation Satellite System (GNSS) refers to a constellation of satellites that continuously transmit signals. Devices on the ground use these signals to determine their own location based on signal strength and time from the satellites. The United States' Global Positioning System (GPS) is the most popular and as a result GNSS is often just referred to as GPS.

![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000QNQ9&feoid=00Nf3000003DI8R&refid=0EMDo000001fbss)

When an Axon Body 4 camera is recording, its GNSS receiver will process signals from orbiting satellites to determine approximate location in a similar manner to your smart phone or in-car navigation. The determined location information is known as a “fix,” and the time starting when a device begins receiving satellite signals after powering on until it determines its own location is known as the “time to first fix.”

GNSS works well when there is clear line-of-sight to the sky. However, because satellite signals can be blocked and scattered by buildings and trees, GNSS does not work indoors and may have errors when a device is near tall buildings.

### Wi-Fi positioning system

The Axon Body 4 camera also has the ability to use Wi-Fi positioning to determine its location, by using signal strength from nearby Wi-Fi access points. This technology is also similar to location services in a smart phone.

Wi-Fi positioning has several benefits, including:

*   Indoor location – Wi-Fi positioning enables the camera to get a position fix in most indoor locations as it does not require satellite signals.
*   Reduced time-to-first fix – under most circumstances Wi-Fi positioning should provide a position fix in less than 3 seconds. However, this may be longer in very rural locations or if the Axon Body 4 is traveling at a high speed. Wi-Fi positioning assists the device’s GNSS by giving the device an initial starting location for faster satellite acquisition.

In collaboration with [Skyhook,](https://www.skyhook.com/) Axon provides Wi-Fi positioning as an optional setting for your Axon Body 4 cameras. This is enabled or disabled on the Axon Body 4 Settings page in Axon Evidence.

**Data processing and service providers** – When Wi-Fi positioning is enabled on the Axon Body 4, certain data related to the use of the Axon Body 4 will be sent to our Wi-Fi positioning service provider to allow them to provide, maintain, and improve the services. Without this provider, the Axon Body 4 is unable to use Wi-Fi Positioning. Please see [Axon’s Cloud Services Privacy Policy](https://www.axon.com/axon-cloud-services-privacy-policy) for information related to all of our service providers, also referred to as sub-processors.

### Location information usage

The location information from Axon Body 4 cameras can be displayed in Axon Evidence or Axon Respond.

*   Axon Evidence – Location information from Axon Body 4 cameras is embedded in the video evidence. The location information is shown in the location map on right side of the Evidence Detail page.

*   [Axon Respond](https://my.axon.com/s/article/Axon-Aware-and-Aware-Overview) – While recording, an Axon Body 4 camera can be enabled to send location updates to Axon Respond. Location updates are sent every few seconds and stop once the camera stops recording. The [Respond map](https://my.axon.com/s/article/Axon-Aware-and-Aware-Features#gps) shows location markers based on when an Axon Body 4 camera last sent a location update.

### Enable and disable Axon Body 4 location services

The Axon Body 4 location services are controlled on an agency-wide basis on the [Axon Body 4 Camera Settings page](https://my.axon.com/s/article/Body-Camera-Settings) in Axon Evidence.

![User-added image](https://axon.file.force.com/servlet/rtaImage?eid=ka0Do000000QNQ9&feoid=00Nf3000003DI8R&refid=0EMDo000001fbsx) 

Frequently Asked Questions
--------------------------

### Does Axon Body 4 continuously record camera location?

*   No, an Axon Body 4 will only attach location to video when a camera is recording. This is why there is not any location data in the pre-event buffer.

### Does Axon Body 4 use cell tower or network-based positioning?

*   No. The Axon Body 4 camera uses satellite and Wi-Fi based positioning only.

### Are GNSS and Wi-Fi Positioning new technologies?

*   No, GNSS and Wi-Fi Positioning are used by virtually every smart phone as they dramatically improve location services. Normally the are just both bundled under the generic term, “GPS”.

### What is Skyhook?

*   [Skyhook](https://www.skyhook.com/about-skyhook) is a location technology company, founded in 2003, that pioneered the use of Wi-Fi to determine device positioning for mobile

### Does the Axon Body 4 camera connect to Skyhook?

*   All data that is exchanged is proxied through Axon Evidence; the camera does not connect directly to any outside service.

### How is my data used and protected?

*   Location information is used to operate, maintain and deliver the Skyhook Services and to develop new products, services or datasets, per Skyhook’s [Services Privacy Policy](https://www.skyhook.com/privacy-services)