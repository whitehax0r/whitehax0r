 👋 Hi, I’m @whitehax0r a.k.a (razr2312) on Twitter
- 👀 I’m interested to share my little knowledge to this greatest community, my native language is Spanish but also speak English as well.
- 🌱 I’m currently learning cybersecurity as part of the Red Team those are more focused to attack and break the matrix xD.
- 💞️ I’m looking to collaborate on PS4 linux community and other interest stuff.
- 📫 How to reach me at the end of this file.
<!---
whitehax0r/whitehax0r is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

First Github project, proudly made by a Latino catracho 🤠

# ArchLinux-PS4

This is a compiled and updated Arch linux with some minor personal changes more related to GUI to look better and included emulators.

![neofetch](https://github.com/whitehax0r/ArchLinux-PS4/blob/4c8010140ee8e5f8d68b1d623464d555706d2f8d/neofetch.png)

![lscpi](https://github.com/whitehax0r/ArchLinux-PS4/blob/883347d1f54bdcb4b2fc1828fcb714c84158b72d/lspci.png)

![glxinfo](https://github.com/whitehax0r/ArchLinux-PS4/blob/883347d1f54bdcb4b2fc1828fcb714c84158b72d/glxinfo.png)

![desktop2](https://github.com/whitehax0r/ArchLinux-PS4/blob/883347d1f54bdcb4b2fc1828fcb714c84158b72d/Desktop2.png)

# Features

- Parallel Downloads enabled.
- PS4 repository enabled.
- LightDM with autologin enabled window manager.
- Neofetch - Show general information about this system.
- Latest PS4 Drivers from oficial repo.
- XFCE - Desktop Environment.
- Steam - The ultimate destination for playing, discussing, and creating games.
- ExFat file system support.
- Bluez - For bluetooth pairing PS4 controller.
- Blueberry - GUI compatible with XFCE/GTK.
- Duckstation - Best PSX emulator.
- Dolphin emulator - Nintengo Wii and Gamecube emulator.
- Nano - Text editor.
- Chromium - Web browser.
- Powerlevel10k - ZSH terminal.
- PCSX2 - Playstation 2 emulator with vulkan support.
- Yabaouze - Sega Dreamcast emulator.
- Hacknerdfonts - For icons inside ZSH and customized fonts for terminal.
- RetroArch - Multiplatform emulator.
- Minecraft Java - Because is fun. :pick:
- LSD - Powered LS bassically.
- BAT - Powered CAT bassically.
- VLC - Video player.
- Spotify - Music player.
- Yay - Yet another yogurt. Pacman wrapper and AUR helper written in go.
- Zip - Compress files to zip files.
- Unzip - Uncompress zip files.
- P7zip - Commandline 7zip support for Linux.
- Htop - See process and other stuff.

# Mandatory requirements
A brain xD and a lot of patience.

# My PS4 Hardware

- PS4 Slim
- Firmware 9.00
- Model CUH-2115B.
- SouthBridge Baikal.

## If you have same PS4 hardware as me you can use these files from below:

- [bootargs.txt](https://github.com/whitehax0r/ArchLinux-PS4/blob/4add3a72d25dcfabff433283606b9ce30762d4d9/bootargs.txt) MD5 >__C84AD779CE76762C04CBF80E420E324D__
- [initramfs.cpio.gz](https://github.com/whitehax0r/ArchLinux-PS4/blob/4add3a72d25dcfabff433283606b9ce30762d4d9/initramfs.cpio.gz) MD5 >__951549B1DEB59DAE3ADA8038461BADD2__
- [bzImage](https://github.com/whitehax0r/ArchLinux-PS4/blob/4add3a72d25dcfabff433283606b9ce30762d4d9/bzImage) MD5 >__B8BDDA64FDED673D1FD8017C2A4B4122__
- [arch.tar.xz](https://mega.nz/file/6ro0mZqb#uzVI3PjhxZ7m5hk4EC2AxCIg5B8h87mqEuvUEzo20Oo) MD5 >__7A997C14B2FAD0C839107A07C69FC312__

# Preparing your PS4 system.

- Make sure you are on firmware 9.00.
- Go to Settings>Sound and Screen>Video output Settings>
- Resolution set to >__1080p__
- RGB range se to >__Full__
- HDR set to >__Off__
- Deep color output set to >__Off__
- Then go to Setting>System>
- Uncheck the box "Enable HDMI Device Link"
- Uncheck the box "Enable HDCP"

# Preparing your USB 3.0 Device for ArchLinux-PS4

:warning: Highly recommeded to use a USE A >=16GB USB 3.0 Device :warning:

- Format the USB 3.0 Device to Fat32 filesystem. You can use this [software.](http://ridgecrop.co.uk/index.htm?guiformat.html)
- Copy and paste the bzImage, the initramfs.cpio.gz, bootargs.txt and arch.tar.xz files to the root of the USB 3.0 Device.
- :warning: If you use the same initramfs.cpio.gz from my Github, this one is created by Nazky, the name of this OS should be arch.tar.xz :warning:
- :warning: __If you use the initramfs.cpio.gz from psxita team, you should rename this file arch.tar.xz to psxitarch.tar.xz__ :warning:
- The total of 4 files should be on the root of your USB 3.0 Device bzImage, the initramfs.cpio.gz, bootargs.txt and arch.tar.xz or psxitarch.tar.xz.
- Open the PS4 web browser and first jailbreak your PS4 with Al-Azif [host](https://cthugha.exploit.menu/#PS4%20(9.00)) follow the instructions on the website.
- Then connect your USB 3.0 Device with all the needed files on your PS4, make sure to connect to the USB slot that is near from your PS4 Blue-ray Disc Drive.
- Launch the 1GB Linux payload using the one of your trust host but I recommend to you to use this [one](https://sleirsgoevy.github.io/900-host/) from [Sleirsgoevy](https://github.com/sleirsgoevy) because this one detects the bootargs.txt file to avoid black screen issues. __I tried with other host but did not detect the bootargs.txt file.__

+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
- When you are on the rescushell type the following commands:
>__exec install-psxitarch.sh__
- :warning: If you use the initramfs.cpio.gz from Nazky type the following commands: :warning:
>__exec install-arch.sh__
- When the installation is done ArchLinux-PS4 is going to boot automatically, if not type the following command:
>__exec start-psxitarch.sh__
-  :warning: __If you use the initramfs.cpio.gz from Nazky type the following commands:__ :warning:
>__exec start-arch.sh__

- ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

# TODO List

- RPCS3 emulator - PS3 emulator. (You can try with the AppImage in their [website.](https://rpcs3.net/download))
- ProtonDB play windows games on linux.
- Nothing more, you tell me.

# Know Issues

Not sure why but every time you boot in to Linux, you have to set your current time and date, just type the following commands on terminal as root: 

>__# timedatectl set-time "yyyy-MM-dd hh:mm:ss"__

For example:

>__# timedatectl set-time "2022-02-19 13:13:54"__

Not sure why but every time you boot in to linux, you have to unpair and pair again your PS4 controller.

# Some FAQs

## Got black screen
Make sure your display is compatible with the 1080p resolution, if you still have a black screen try a others monitor or TV.

## I want to uninstall this OS from my USB 3.0 Device
Just format your device.

## How to update ArchLinux-PS4?
Just type the following command:
>__sudo pacman -Syyu__
- and type "Yes" if there are packages with updates.

## Can I use my DS4 controller as mouse?
Yes!, you can use the touchpad of your DS4 controller.

## I have difficulties to connect my DS4 controller, what can I do?
I will upload a video later.

## I'm not sure about my PS4 Hardware?
You can search [here](https://www.psdevwiki.com/ps4/Southbridge#Southbridge_revisions) or [here.](https://www.psdevwiki.com/ps4/)

## Where I can find those PS4 kernels and initramfs.cpio.gz for other PS4's hardware.
Well you can download those files from Hakkuraifu [Github.](https://github.com/Hakkuraifu/PS4Linux-Documentation)

# Social Media

- You can follow me on [Twitter](https://twitter.com/razr2312)
- You can follow me on [YouTube](https://www.youtube.com/user/allank2312/videos)

![esta es una imagen](https://github.com/whitehax0r/ArchLinux-PS4/blob/353059a5bbb0a7f161ade53a56e374a6398d7c6a/Flag.png)

