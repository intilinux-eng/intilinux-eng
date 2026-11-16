# Antonio Rosario Intilisano - Intilinux - Maker Ing 

**Automotive software engineer in Turin, Italy.** I currently work on **[Eclipse S-CORE](https://eclipse.dev/score/)** at **ETAS GmbH**. S-CORE is the open-source core software stack for software-defined vehicles, hosted by the Eclipse Foundation ([eclipse-score](https://github.com/eclipse-score) on GitHub). My S-CORE work happens under my company account; this profile is for my personal projects.

[LinkedIn](https://www.linkedin.com/in/antonio-rosario-intilisano/)

## About

I've spent more than ten years on vehicle software:
- **ETAS** (2018 – today): first Product Owner of **RTA-VRTE**, ETAS's AUTOSAR Adaptive framework, and of the VSPS Experience Package; now working on Eclipse S-CORE.
- **Teoresi**, for CNH Industrial / IVECO (2015 – 2018): testing and validation of embedded Linux telematics units: Yocto BSPs on i.MX6, CAN/J1939 and UDS diagnostics, Wi-Fi, Bluetooth and cellular connectivity, OTA updates.
- **University of Catania** (2012 – 2015): PhD research on speech recognition and spoken dialog systems. Best paper award at CONTENT 2014 for a grammar generator for spoken language understanding. Along the way I built Android apps, including an augmented-reality tourism guide for Epson Moverio smart glasses.

Linux has been part of my work for years, from embedded targets to the kernel: in 2018 I had a patch merged upstream. Now it's my desktop too, and I contribute to KDE. I like tools that solve a real, everyday problem and explain themselves in plain language.

Away from the keyboard I restored and drive a 1990s **Fiat Coupé 2.0 16v** with the Lampredi twin-cam engine, which is why I maintain an ECU diagnostics tool for Marelli IAW systems. I'm into **valve (tube) hi-fi**, I ride my bike, and I run my own local-first home automation (Shelly, MQTT, no cloud).

## Open source contributions

| Project | Contribution | Status |
|---|---|---|
| **Linux kernel** | [platform/x86: acer-wmi: add another KEY_POWER keycode](https://git.kernel.org/torvalds/c/c7a437fdd6e794290082cd19808627c661e15c5d): power button support for the Acer Swift 3 | merged, Linux 4.18 |
| **KDE Frameworks** (KIO) | [DesktopExecParser: add acceptsFiles()](https://invent.kde.org/frameworks/kio/-/merge_requests/2559) | under review |
| **KDE Plasma** | [Task manager: open recent folders with the app that recorded them](https://invent.kde.org/plasma/plasma-desktop/-/merge_requests/4231) | under review |
| **Visual Studio Code** | [Linux: publish recent workspaces to the desktop](https://github.com/microsoft/vscode/issues/348335) | proposal |

## Projects

**Automotive**
- **[scrample-pingpong-bench](https://github.com/intilinux-eng/scrample-pingpong-bench)**: zero-copy IPC latency benchmark for Eclipse S-CORE `score::mw::com`, with notes on the middleware, benchmark design and Linux real-time tuning. C++, Bazel.
- **[iaw-scan-3](https://github.com/intilinux-eng/iaw-scan-3)**: diagnostics and data logging for 1990s Fiat, Lancia and Alfa Romeo engines (Marelli IAW ECUs, FIAT CODE immobiliser) over a K-line cable. C#, fork of IAW Scan 2.

**Linux desktop**
- **[vscode-recent-workspaces-linux](https://github.com/intilinux-eng/vscode-recent-workspaces-linux)**: recent VS Code workspaces in the KDE Plasma taskbar, like the Windows Jump List. It led to the KDE and VS Code changes above. Python, GLib, systemd.
- **[icloud-sync](https://github.com/intilinux-eng/icloud-sync)**: two-way automatic iCloud Drive sync on Linux, built on rclone bisync. Python.

**Home automation**
- **[LocalHome](https://github.com/intilinux-eng/LocalHome)**: local-first home automation for a real two-zone apartment with a radiant ceiling and a VMC, on an Arduino UNO Q. Shelly Gen3 over local MQTT, no cloud; a page for the residents, an admin panel for the installer, desktop apps for Windows and Linux, and a Debian package for the board. Python, Flask, JavaScript, Qt.

**Networking**
- **[netlog](https://github.com/intilinux-eng/netlog)**: your network traffic explained in plain sentences: which program talks to whom, what is new, what is exposed. Python, Scapy.

## Tech

C, C++, C#, Python, Java, Bash · embedded Linux, Yocto · AUTOSAR Adaptive, CAN, UDS · Qt and KDE Frameworks · Bazel, CMake, Docker, systemd, Jenkins · Scrum
