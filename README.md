<h3 align="center">
	<img src="https://github.com/JaKooLit/Telegram-Animated-Emojis/blob/main/Activity/Sparkles.webp" alt="Sparkles" width="38" height="38" />
	 Сборка KLV-Hyprland-Sway-CE
	<img src="https://github.com/JaKooLit/Telegram-Animated-Emojis/blob/main/Activity/Sparkles.webp" alt="Sparkles" width="38" height="38" />
</h3>

# *Sway*

![1719838135_grim](https://github.com/sofijacom/KLV-Hyprland-Sway-CE/assets/107557749/96da6941-5f7e-4273-888a-bed56cfd966d)

![2024-07-03_17-42](https://github.com/user-attachments/assets/be6c22e0-4ec3-42d8-a0ad-d156314a31c4)


# *Hyprland*

![screenshot-20240701-153718](https://github.com/sofijacom/KLV-Hyprland-Sway-CE/assets/107557749/d8b3796f-c417-45af-a2d0-8f4123dc3513)


1) Create a folder `KLV-Hyprland-Sway-CE` typing in the terminal `mkdir -p KLV-Hyprland-Sway-CE`

2) Open a terminal in the created folder `KLV-Hyprland-Sway-CE` or go to the folder by typing in the terminal

   - `cd KLV-Hyprland-Sway-CE`

3) Place the build script  `KLbuild_Void_hyprland_sway_0.39_BASE.sh` in the created folder.
   
4) Make it executable.`chmod +x KLbuild_Void_hyprland_sway_0.39_BASE.sh`

5) Enter in terminal `./KLbuild_Void_hyprland_sway_0.39_BASE.sh`

6) Wait for the build to finish.

7) After the build is complete to package `07firstrib_rootfs` into `07KLV-Hyprland-Sway-CE-x.x.sfs` where x.x is your build number.

8) Type in terminal.

```
mksquashfs 07firstrib_rootfs 07KLV-Hyprland-Sway-CE-x.x.sfs -noappend -comp xz -b 512k
```
  - where x.x is your build number.

9) Delete the `07firstrib_rootfs` folder.

##

FirstRib-KLV build script. 

```
./KLbuild_Void_hyprland_sway_0.39_BASE.sh
```
FirstRib-KLV build script PLUG file.

Example of using a .plug file:

```
./build_firstrib_rootfs.sh void default amd64 f_00_Void_wayland_hyprland_sway_0.39_no-kernelBASE.plug
```

***f_00_Void_wayland_hyprland_sway_0.39_no-kernelBASE.plug***  builds a  ***(root filesystem)***  for the Arch Linux-based Hyprland desktop operating system, similar to **KLV-Hyprland-Sway**.

To create a complete distribution, all other utilities, tools and configurations are downloaded from a centralized repository and installed as a .tar.gz file.

<p align="center">	
  <img src="https://github.com/sofijacom/sofijacom/blob/49e18fe1d7c2223884efd95af9370dcb84697427/icons_line/gray0_ctp_on_line.svg?sanitize=true" />
</p>
