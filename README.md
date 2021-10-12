# VivintRTSP
This covers a detailed guide and sample configurations for deriving the RTSP streams of Vivint security cameras so that they can be used in other NVR solutions such as Frigate. This guide assumes a HomeAssistant supervised installation of Frigate, but it should also work for any third party NVR implementation that relies on RTSP streams like Frigate. It also requires some version HomeAssistant installed and the Vivint custom componets integration set up and configured appropriately (either manually or with HACS). To see how to do this, [refer to the YouTube guide here.](https://www.youtube.com/watch?v=s-7HyBGYfg4)

# The Basics
This assumes you have the following:

- A supervised installation of HomeAssistant 
- HACS installed ([here is a video walkthrough on how to do that](https://www.youtube.com/watch?v=D6ZlhE-Iv9E))

It is possible to manually install this custom integration [as shown in the author's github page](https://github.com/natekspencer/hacs-vivint), but it is beyond the scope of this guide and will not be covered. 

You will now need to authenticate to your Vivint account. If you are successfull, you will be presented with a screen asking you to choose the area for all of the devices.

