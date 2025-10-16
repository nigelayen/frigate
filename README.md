# Frigate NVR (Network Video Recorder)

[Frigate NVR](https://github.com/blakeblackshear/frigate)  is an open source NVR built around real-time AI object detection. All processing is performed locally on your own hardware, and your camera feeds never leave your home.

I use a mix of cameras including Reolink, TP-Link, Ring video doorbell, and Ring indoor cameras. All cameras, except the Ring products, feed into Frigate NVR. There's probably a way to send an RTSP stream from the Ring cameras to Frigate but I have not had the time to figure that out yet.

### Installation
Follow the [installation documentation](https://github.com/blakeblackshear/frigate/discussions/16650) for installation in a Docker container.

### Hardware
[Coral USB Accelerator](https://www.amazon.ca/Google-Coral-Accelerator-coprocessor-Raspberry/dp/B07R53D12W) coprocessor used for object detection.