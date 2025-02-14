![Image](https://github.com/user-attachments/assets/c54326c7-0ce0-4405-86c4-b896b993aec3)

<p align="center">
    <a href="https://github.com/MrVivekRajan/Plymouth-Themes/stargazers"><img src="https://img.shields.io/github/stars/MrVivekRajan/Plymouth-Themes?colorA=1d2021&colorB=b16286&style=for-the-badge"></a>
     <a href="https://github.com/MrVivekRajan/Plymouth-Themes/contributors"><img src="https://img.shields.io/github/contributors/MrVivekRajan/Plymouth-Themes?colorA=1d2021&colorB=5e81ac&style=for-the-badge"></a>
     <a href="https://github.com/MrVivekRajan/Plymouth-Themes/blob/main/LICENSE">
        <img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=GNU&colorA=1d2021&colorB=eebd35&logo=unlicense&logoColor=b16286&"/></a>   
</p>

<p align="center">
    <a href="https://github.com/MrVivekRajan/Plymouth-Themes/issues"><img src="https://img.shields.io/github/issues/MrVivekRajan/Plymouth-Themes?colorA=1d2021&colorB=fb4934&style=for-the-badge"></a>
    <a href="https://github.com/MrVivekRajan/Plymouth-Themes/forks"><img src="https://img.shields.io/github/forks/MrVivekRajan/Plymouth-Themes?colorA=1d2021&colorB=458588&style=for-the-badge"></a>
</p>

## 🌠 About This Project
A warm welcome to all the people reading out this 🤗. Here at this repo you will find some cool, stylish and eye catchy boootanimations for [Plymouth.](https://www.freedesktop.org/wiki/Software/Plymouth/)
 
# Previews

<details><summary>Style-1</summary>
    
# Anonymous  
![Image](https://github.com/user-attachments/assets/274056c0-92f1-40b2-b850-eee5d78679bd)
# Angry-Eye
![Image](https://github.com/user-attachments/assets/4cb532f3-ef57-456b-879e-9089a9d5e3a1)
# Ironman
![Image](https://github.com/user-attachments/assets/e8549da1-bc02-4297-82d0-a5bd22e572c8)
# Error
![Image](https://github.com/user-attachments/assets/8a521ae0-27ee-4913-ac7c-4666206560b9)
# Dc-Marvel 
![Image](https://github.com/user-attachments/assets/02ac0d10-5818-4d80-9a85-126161ed6a22)
</details>

<details><summary>Style-2</summary>

# Goku   
![Image](https://github.com/MrVivekRajan/Plymouth-Themes/blob/main/Preview/goku.gif?raw=true)
# Starlord
![Image](https://github.com/user-attachments/assets/4c56f308-cba5-4ee7-ae9c-5f0d0724547e)
# Sasuke 
![Image](https://github.com/user-attachments/assets/5834b229-1dd2-481f-bf3e-3eaaaaab6b35)
# Steam
![Image](https://github.com/user-attachments/assets/c11e575b-e93e-4554-8c46-15b99f7c935f)
# Rockstar
![Image](https://github.com/user-attachments/assets/f339cc24-4a46-4832-bb4a-f1bb8ea176e8)
</details>

<details><summary>Style-3</summary>

# Cube
![Image](https://github.com/user-attachments/assets/9366c03b-bc80-4d51-9317-32ba4893c400)  
# Google
![Image](https://github.com/user-attachments/assets/ce1c1f7f-252a-44be-a4d2-f650d2cfb643)
# Ios
![Image](https://github.com/user-attachments/assets/ec910985-4139-48bf-bf75-e4a3ceccde0e)
# Google2
![Image](https://github.com/user-attachments/assets/cd6bcf6e-eeef-4853-861f-0f15a2e9eb8a)
# HyperOs
![Image](https://github.com/user-attachments/assets/1b38fb5c-7dd0-48d0-b7b6-7635aea0aaf4)
</details>

<details><summary>Style-4</summary>

# DeadLight
![Image](https://github.com/user-attachments/assets/52b14037-825b-43da-a2ef-175d1c71c16f)
# Windows
![Image](https://github.com/user-attachments/assets/7f34ff9f-f175-4247-af74-16a9e9ea2795)
# WindowsGr (Getting Ready)
![Image](https://github.com/user-attachments/assets/e4f097d4-a2ac-46d9-858d-8b82d90f0ee8)
# Bsol (Blue Screen Of Life)   
![plymouth ](https://github.com/user-attachments/assets/ea6b1579-eda4-435b-bb8f-47868fdfc21e)
</details>

# Installation
- Install plymouth on your distro by following guide written on your distro's wiki page or search on the internet. Do follow each and every steps properly ▼
  
  [Arch](https://wiki.archlinux.org/title/Plymouth)  [Debian](https://wiki.debian.org/plymouth)  [Ubuntu](https://wiki.ubuntu.com/Plymouth) [Linux-Mint](https://community.linuxmint.com/tutorial/view/646)  [Nix-OS](https://wiki.nixos.org/w/index.php?title=Plymouth&mobileaction=toggle_view_desktop)  [Gentoo](https://wiki.gentoo.org/wiki/Plymouth)  [EndeavourOS](https://forum.endeavouros.com/t/guide-how-to-install-and-use-plymouth/51363)  [Fedora](https://discussion.fedoraproject.org/t/enable-plymouth-startup/70079)  [MX-Linux](https://mxlinux.org/wiki/system/add-plymouth-to-mx-linux/)  [Manjaro](https://wiki.manjaro.org/index.php/Plymouth)  [oepnSUSE](https://en.opensuse.org/openSUSE:Plymouth)   

- After installation make sure that you have a themes folder inside /usr/share/plymouth/ if not then create one
by ▼ 
```bash
sudo mkdir /usr/share/plymouth/themes/
```

- Clone this repository if you want all the themes at once else if you want any individual theme then download it from release section
```bash 
git clone https://github.com/MrVivekRajan/Plymouth-Themes.git
```

- After cloning or downloading your desired theme simply copy and paste your desired Theme to
```bash
/usr/share/plymouth/themes/
```

- Now just set your desired theme as default Plymouth theme and make sure to rebuild `initrd` for that just use command given below ▼
```bash  
sudo plymouth-set-default-theme (theme-name) -R 
```
- Dont forget to replace `(theme-name)` with your desired theme's name in above command ▲

# Download
- If you want to download all the themes at once then simply clone/download this [repository.](https://github.com/MrVivekRajan/Plymouth-Themes)
- If you want to download individual or your desired theme then download it from [Release-Section.](https://github.com/MrVivekRajan/Plymouth-Themes/releases)
- `Also Available at` [Pling](https://www.pling.com/p/2216301/) and [Gnome-Look.](https://www.gnome-look.org/p/2216301)

# Credits
- [MagiBoot-D3bootanimations](https://t.me/MagiBoot) - For Bootanimations and ideas
- [K Harishnkr](https://github.com/harishnkr) - For Blue Screen of Life Idea
- [Mauro Meloni](https://gitlab.com/maurom) - For circular loading animation

# Thanks for Visiting !! ❤️❤️
I Hope You Like my project, if yes then don't forget to give it a star as it means a lot.
<h4> <span>· </span> <a href="https://github.com/MrVivekRajan/Plymouth-Themes/issues"> Report Bug </a> <span> · </span> <a href="https://github.com/MrVivekRajan/Plymouth-Themes/issues"> Request Feature </a> </h4>
