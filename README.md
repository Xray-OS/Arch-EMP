# Arch Linux Empowered

![OS Logo](https://images2.imgbox.com/cb/60/hskBSEv0_o.png)

## What is Arch-EMP (Arch Linux Empowered)

Arch Linux EMP or Arch Linux Empowred is an Arch Linux version highly improved with fixes for performance better functionality absolute compatibility with gaming and at the same time remaining its vanilla look and logos related to Arch Linux.

Remember Arch Linux doesn't have a default appaerance or defaults settings, so anything you do with your distro could be considered Arch Linux or Linux in general, so my Arch Linux version would be a super monster with steroids ready for gaming, content creation and programming.

## About "BLOAT"
What you probably call bloat, i probably call it "programs that everyone should have", there is nothing wrong with a system that has ready to go settings and programs for things that should be out of the box available by default when it comes to functionality and great performance on your Linux system. 

## Where do this come from?
This comes from the Xray_OS project, Xray_OS is an Arch Linux distribution focused on gaming and performance, Arch-EMP is the same but just with minor changes to make it more-like vanilla Arch experience, without theming or ay specific resemblance to the Xray_OS project when it comes to branding.

## What are the performance improvements Arch-EMP brings to the table?

There is a long list of changes that have being made to this distribution for the improvement of the performance, most of them comes from the Xray_OS project and the CachyOS project. Improvements for the Kernel, indeed a better KerneL (Xanmod-RealTime). 

Improvements to lots of NVIDIA settings for maximum performance on NVIDIA cards, improvements for the limit resources, CPU usage, Audio performance, NVME and SSD performance has being made, and a couple other things, this is a non-complete list of the optimizations for performance that has being made for this distro, mos of them coming from the Xray_OS project:

- raytracing support enabled for NVIDIA and INTEL

- trim support enabled for SSDs

- NVIDIA PRIME Render Offload enviroment variables already set in shell, so applications will render using the NVIDIA GPU enabling PRIME render offload functionality, everytime you run them through the terminal 

- NVIDIA persistenced service enabled, to avoid the kernel tearing down the device state whenever the NVIDIA device resources are no longer in use

- NVIDIA PCI-Express Runtime D3 (RTD3) Power Management enabled, for fully power down the GPU when not in use

- support for Sourthern Islands generation AMD GPUs

- support for Sea Islands generation AMD GPUs

- support for Southern Islands GPUs in the radeon driver. Essentially

- use of the page attribute table for memory management in NVIDIA cards enabled

- kernel modesetting for the NVIDIA DRM (Direct Rendering Manager) module enabled

- use of the framebuffer device for NVIDIA DRM enabled
 
- essential real-time priority for audio processes settings for maintaining low latency and smooth audio playback.
 
- audio processes locked to an unlimited amount of memory in RAM, preventing it from being swapped out to disk
 
- hard limit for maximum number of open files increased to allow processes to handle more open files simultaneously
 
- real-time priority adjusted to ensure processes receive preferential treatment in terms of cpu scheduling
 
- processes in @realtime group locked to an unlimited amount of memory in RAM, preventing it from being swapped out to disk, crucial for rt-performance
 
- smaller journal files for less storage overhead, reducing the need of unnecessary disk space
 
- normal user applications such as audio software are allowed to request real-time priority which is crucial for tasks like audio processing, multimedia, and other time-sensitive operations
 
- logging level adjusted,reducing unnecessary log entries providing essential information without overwhelming the logs
 
- lower verbosity for fewer log entries, saving disk space and reducing I/O overhead
 
- Resource delegation applied to ensure fair resource distribution among user services
 
- adjusted timeouts that ensures services do not hang indefinitely during startup or shutdown
 
- adjusted limits that helps preventing resource exhaustion and ensure fair resource allocation

- resource delegation for efficient resource management to ensure resource limits are enforced and that child units inherit relevant controllers
 
- adjusted default soft and hard limits for the number of open files for efficient management of file desciptors, preventing resource exhaustion and enhancing overall system stability and responsiveness, also preventing performance degradation due to contention or exhaustion

- still documenting the rest of the performance optimizations W.I.P

## Cool features
- Chaotic-AUR, even on discover and the rest of the package managers
- Beatiful terminal with ZSH
- Out of the box ready for gaming content creation and programming
- Plasma desktop enviroment already configured properly
- Xanmod Real Time Kernel
- Floorp browser as your default browser + Vivaldi browser (yes i have a bias for these browsers)
- All essential services like bluetooth enabled
- All wine dependencies
- Supergxctl to switch between hybrid mode or only integraded GPU
- Timeshift-auto-snaps
- Optional version with snapd support integrated
- Raytracing support (supported hardware needed)
- Custom repo, with some PKGs that you would normally get only through the AUR (xray-repos basically)
- yay - AUR helper
- A Special Fix for the missing title bar in Davinci Resolve on KDE Plasma (probably already fixed in plasma 6)
- Support for software development
- And many more..

## Visuals
What does it look like?

![Desktop1](https://images2.imgbox.com/da/c2/DbH8ijhH_o.png)

**Download(NVIDIA)1.01:** [![Download Arch-EMP](https://a.fsdn.com/con/app/sf-download-button)](https://sourceforge.net/projects/arch-linux-empowered-arch-emp/files/latest/download)

## AMD version it's been worked please wait, Thank You. 

## Support
If you like to support my work you can send DM, and ask for platforms to use for donations.

## Contributing
You can always help and contribute to this project, send DM and present your ideas.

## Authors and acknowledgment
Angel Gustavo Lopez

## License
At the moment Arch-EMP is free and open source under the MIT license

![OS Logo](https://images2.imgbox.com/cb/60/hskBSEv0_o.png)
