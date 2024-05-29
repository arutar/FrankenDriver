![logo](logo/FrankenDriver.png)
# FrankenDriver
### Original nvidia driver for **frankenstein graphics cards** with a laptop chip. (**Win10 Win11 Linux**)  
How to enable [Easy Anti-Cheat support](https://github.com/arutar/FrankenDriver/issues/6)!

- RTX 20XX / RTX 2070m / RTX 2080m / RTX 2080m Super
- RTX 3050m Ti / RTX 3060m / RTX 3070m / RTX 3070m Ti / RTX 3080m / RTX 3080m Ti
- RTX 4080m / RTX 4090m (starting from version **551.86**)
- RTX A2000 / RTX A3000 (starting from version **555.85**)

This page is for those people who were lucky enough to buy a video card from aliexpress 

<img src="https://img.shields.io/badge/-RTX%204080m-FF3633" height="25"/> / <img src="https://img.shields.io/badge/-RTX%204090m-2E4053" height="25"/> 

<img src="https://img.shields.io/badge/-RTX%203050m%20Ti-CCFFCC" height="25"/> / <img src="https://img.shields.io/badge/-RTX%203060m-orange" height="25"/> / <img src="https://img.shields.io/badge/-RTX%203070m-green" height="25"/> / <img src="https://img.shields.io/badge/-RTX%203070m%20Ti-blueviolet" height="25"/> / <img src="https://img.shields.io/badge/-RTX%203080m-blue" height="25"/> / <img src="https://img.shields.io/badge/-RTX%203080m%20Ti-795548" height="25"/> 

<img src="https://img.shields.io/badge/-RTX%202070m-ff69b4" height="25"/> / <img src="https://img.shields.io/badge/-RTX%202080m-ff4400" height="25"/> / <img src="https://img.shields.io/badge/-RTX%202080m%20Super-16a085" height="25"/> / <img src="https://img.shields.io/badge/-RTX%2020XX-95a5a6" height="25"/> 

<img src="https://img.shields.io/badge/-RTX%20A2000-BC8F8F" height="25"/> / <img src="https://img.shields.io/badge/-RTX%20A3000-F0FF33" height="25"/> 

By default, manufacturers offer to download two drivers that need to be installed sequentially and which are simply of terrible quality, for example, it is impossible to render with such drivers using blender or arnold, and updating such a driver will most likely never happen. 
I decided to fix this situation and corrected the original drivers from nvidia, which now work fine with such video cards. Use it, enjoy life and don't forget to [support the project](https://boosty.to/frankendriver/purchase/1380135?ssource=DIRECT&share=subscription_link)!!  

<img align="right" width="120" height="120" src="logo/qr_b1b07814e495597a0792eb5ef7984907.png">

# Drivers download  
#### Studio and [LATEST drivers download with boosty](https://boosty.to/frankendriver/purchase/1380135?ssource=DIRECT&share=subscription_link) **subscription + TG channel**.  
[Latest news in the boosty feed](https://boosty.to/frankendriver)

##### Unfortunately, subscription through **buymeacoffee** is no longer possible and, for some reason unknown to me, the frankendriver page there is blocked.

- Windows [528.24](https://drive.google.com/uc?export=download&confirm=no_antivirus&acknowledgeAbuse=true&id=1o8mkToO0ssKjTdF-C90LjKbtLKFtfIuq) (with support for changing the Power Limit)
- Windows [546.33](https://drive.google.com/uc?export=download&confirm=no_antivirus&acknowledgeAbuse=true&id=1a71Idxp8uq2JooA7nImUTp5F7jCS6lqL)
- Windows [551.23](https://drive.google.com/uc?export=download&confirm=no_antivirus&acknowledgeAbuse=true&id=1N5y8kkQK7YZ4j5uPxZa2IFHX3a9hpB5m)
- Windows [551.86](https://drive.google.com/uc?export=download&confirm=no_antivirus&acknowledgeAbuse=true&id=174KUaWSLPhXnwj225pWyJZF1YKyzndyx)
  https://drive.google.com/file/d/1nSB-kHAAoEDyY6TfKaHtOLFsh-RRK7p7/view?usp=drive_link
- Linux [525.85.05](https://drive.google.com/uc?export=download&confirm=no_antivirus&acknowledgeAbuse=true&id=1Uk8Mw2TcGgqBxYsmBa8EOiKlTSSmn9SS) and [Installation instruction](https://github.com/arutar/FrankenDriver/issues/11)
- Linux [550.78](https://drive.google.com/uc?export=download&confirm=no_antivirus&acknowledgeAbuse=true&id=1nSB-kHAAoEDyY6TfKaHtOLFsh-RRK7p7)


<details><summary>Linux (HiveOS) Wget download link</summary>

```Batchfile
 wget --output-document=NVIDIA-Linux-x86_64-525.85.05.run '--post-data=confirm=no_antivirus' 'https://drive.google.com/uc?export=download&confirm=no_antivirus&acknowledgeAbuse=true&id=1Uk8Mw2TcGgqBxYsmBa8EOiKlTSSmn9SS'
```
```Batchfile
 wget --output-document=NVIDIA-Linux-x86_64-535.104.05.run '--post-data=confirm=no_antivirus' 'https://drive.google.com/uc?export=download&confirm=no_antivirus&acknowledgeAbuse=true&id=1ErN4_upq1C5KkJs2EnA9PMQGKQk62Csl'
```

</details>

<details><summary>Security and transparency</summary>

1) Only installer configs and inf files are modified.  
2) No driver binaries are modified!  
3) No additional executable files are installed or executed.
4) NVPCF removed from driver to avoid error 31
5) In order to view the contents of the installer, it is enough to unpack the contents using rar or 7zip.  

</details>

<details><summary>Supported devices</summary>
    
- ### RTX 3060m
  10DE.2520 10DE.0000  

- ### RTX 3070m
  10DE.249D 10DE.0000  
  10DE.249D 4D50.4449  

- ### RTX 3070m Ti
  10DE.24A0 10DE.0000  
 
- ### RTX 3080m   
  10DE.249C 10DE.0000  
  10DE.249C 4D50.4449  

</details>

<details><summary>Issues</summary>

- [Easy Anti-Cheat errors](https://github.com/arutar/FrankenDriver/issues/2)
- [How to remove Easy Anti-Cheat errors](https://github.com/arutar/FrankenDriver/issues/6)
- [Add a new Device ID](https://github.com/arutar/FrankenDriver/issues/5)

</details>

#### [Silver subscription & TG channel](https://boosty.to/frankendriver/purchase/1487157?ssource=DIRECT&share=subscription_link) for communities or organizations that would like to support the project!
#### Need a very customized driver? Interested in the long existence of the project? [Gold subscription & TG channel](https://boosty.to/frankendriver/purchase/1383232?ssource=DIRECT&share=subscription_link)

