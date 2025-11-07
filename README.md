# Hackintosh EFI for Acer-Aspire-A715-75G (Frankenstein Build)

This EFI was assembled by combining and adapting configurations from several similar laptop EFIs. It serves as a functional base configuration and may require minor adjustments depending on hardware revision.

![Desktop Screenshot](https://raw.githubusercontent.com/hauptkern/Acer-Aspire-A715-75G-SEQUIOA-EFI/refs/heads/main/screenshot.png)

## Working
- Bluetooth  
- NVRAM  
- Integrated GPU  
- Screen brightness control  
- Native display resolution @ 60Hz  
- All USB ports  
- Webcam  
- Battery percentage reporting  
- Sleep / Wake  
- Sensors  
- CPU turbo boost  
- Trackpad  
- Fn keys  
- Headphone jack  
- Onboard Wi-Fi (via **itlwm + HeliPort**)  
- Speakers  
- Power management  
- Internal microphone  

## Not Working
- Discrete NVIDIA GTX 1650 (disabled, unsupported on macOS)

## Wi-Fi Setup
1. itlwm is already included.
2. Install HeliPort to connect to Wi-Fi networks (macOS Wi-Fi menu will not work).
