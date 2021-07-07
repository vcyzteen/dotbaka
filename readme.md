<b><h2><p align="center">**D O T B A K A**</p></h2></b>

<p align="center"><img src="https://img.shields.io/github/downloads/vcyzteen/dotbaka/total?color=FFFFFF&style=for-the-badge">
<p align="center"><img src="https://badges.pufler.dev/visits/vcyzteen/dotbaka?style=for-the-badge&label=&color=ffffff&label=visiting" /> <img src="https://img.shields.io/github/repo-size/vcyzteen/dotbaka?style=for-the-badge&label=files&color=ffffff"/> <img src="https://img.shields.io/github/license/vcyzteen/dotbaka?style=for-the-badge&label=licenci&color=ffffff" />
<img src="https://img.shields.io/badge/MAINTAINED-YES-white?style=for-the-badge">
<h3><b><p align="center"> H O M E S C R E E N </p></b></h3>

| H O M E |
|-|
|![img](https://github.com/vcyzteen/dotbaka/blob/baka/preview/n1.png)|
|![img](https://github.com/vcyzteen/dotbaka/blob/baka/preview/home.png)|
     
<b><p align="center">You are welcome if you want to take the part you want or change it on your own device</p></b>

* **Installasion for latest menthod**

```sh
$ git clone https://github.com/vcyzteen/dotbaka && cd dotbaka
```
```sh
$ chmod +x preinstalled && ./preinstalled
```
```sh
$ rsync -avxHAXP --exclude '.git*' .* ~/
```
```sh
$ pushd ~/.icons/ &&
     sudo ln -vs ~/.icons/Tela-grey /usr/share/icons/Tela-grey &&
     sudo ln -vs ~/.icons/Tela-red /usr/share/icons/Tela-red &&
  popd
```
```sh
$ fc-cache -rv
```

- **Compositor <kbd>suggested</kbd>**
  <details>
  <summary><strong>See</strong></summary>

  * Instructions for building `picom-ibhagwan` on void linux using `xbps-src`:
    1. Setup the `void-packages` repo:

    ```sh
    $ git clone --depth=1 https://github.com/void-linux/void-packages
    $ cd void-packages
    $ ./xbps-src binary-bootstrap
    $ echo XBPS_ALLOW_RESTRICTED=yes >> etc/conf
    ```
    2. Download the template repo and copy into `srcpkgs`:

    ```sh
    $ git clone https://github.com/ibhagwan/picom-ibhagwan-template
    $ mv picom-ibhagwan-template ./srcpkgs/picom-ibhagwan
    ```
    3. Build & install the package:

    ```sh
    $ ./xbps-src pkg picom-ibhagwan
    $ sudo xbps-install --repository=hostdir/binpkgs picom-ibhagwan 
    ```
    **Note #1:** if you have `xtools` installed you can install the package by running `xi -f picom-ibhagwan` (instead of using `xbps-install`).

    **Note #2:** before installing the package make sure to remove all other `compton|picom` packages with `sudo xbps-remove picom && sudo xbps-remove compton`.
  
  * Picom For Artix [ Aur ] | ```yay -S picom-ibhagwan-git```

- **VSCode Themes & Icons <kbd>optional</kbd>**
  <details>
  <summary><strong>See</strong></summary>
    
    <p align="center"><img src="preview/vscode.png" alt="Atom&Material" align="center"/>
    </p>
    <p align="center"><img src="preview/vscode-light.png" alt="Atom&Material" align="center"/>
    </p>
    
    <p align="center"><a href="https://github.com/PKief/vscode-material-icon-theme" />I C O N - T H E M E </a> | <a href="https://github.com/akamud/vscode-theme-onedark" /> T H E M E - V S C O D E - D A R K </a> | <a href="https://github.com/akamud/vscode-theme-onelight" /> T H E M E - V S C O D E - L I G H T </a></p>

- **Telegram Theme <kbd>optional</kbd>**
  <details>
  <summary><strong>See</strong></summary>

  <p align="center"><img src="preview/telegram.png" alt="Telegram-Theme" align="center"/>

  <p align="center"><a href="https://github.com/vcyzteen/Telegram-theme" /> T E L E G R A M - T H E M E </a>

- **SLIM Theme <kbd>optional</kbd>**
  <details>
  <summary><strong>See</strong></summary>

  <p align="center"><img src="preview/slim.png" alt="SLIM-Theme" align="center"/>

  <p align="center"><a href="https://drive.google.com/drive/folders/1_Ktq9kGqDi0TNC8Q49AWpLo2HvWkPhnQ" /> S L I M - T H E M E </a>
  
  	* *<b>Installasion See <a href="https://wiki.archlinux.org/title/SLiM">Archwiki<a/></b>*

- **Neofetch Image <kbd>by defaults</kbd>**
  <details>
  <summary><strong>See</strong></summary>

  | Artix | Void | Devuan |
  |-|-|-|
  |![img](https://github.com/vcyzteen/dotbaka/blob/baka/preview/artix.png)|![img](https://github.com/vcyzteen/dotbaka/blob/baka/preview/void.png)|![img](https://github.com/vcyzteen/dotbaka/blob/baka/preview/devuan.png)|

  **All Image Neofetch © @vcyzteen**

```
|-------------------------|------------------------|
|         Keybind         | Typed Key              |
|-------------------------|------------------------|
|    Open Rofi - Menu     | Super + Space          |
|-------------------------|------------------------|
|     Open - Terminal     | Super + Enter	   |
|-------------------------|------------------------|
|    Screenshot - Now     | Print [ PrtSc ]        |
|-------------------------|------------------------|
|   Screenshots - Half    | Alt + Print [ PrtSc ]  |
|-------------------------|------------------------|
|      Reload sxhkd       | Super + Escape         |
|-------------------------|------------------------|
|     Get all Menu XD     | Super + Z	           |
|-------------------------|------------------------|
|      Mpd With Rofi      | Super + M              |
|-------------------------|------------------------|
|    Youtube With Rofi    | Super + V              |
|--------------------------------------------------|
```
<h3><b><p align="center">T H A N K S - F O R</p></b></h3>

* **Inspiration Resources**
  * [اَدِّيْ](https://github.com/addy-dclxvi)
  * [Harry](https://github.com/owl4ce)
  * [elenpan](https://github.com/elenapan)
  * [Ibhagwan](https://github.com/ibhagwan)
  * [Aditya Shakya](https://github.com/adi1090x)
  * [Risky Nur Assyaufi](https://github.com/bandithijo)

* **© All artist who make icons, illustrations, and wallpapers.**

  * [Tela-Icons](https://github.com/vinceliuice/Tela-icon-theme)
  * [マネージャー](https://github.com/vcyzteen)
  * [Void 0 世界の鎮魂歌 - 雪](https://www.pixiv.net/member_illust.php?mode=medium&illust_id=89927268)

* **Our local linux art community**
  * [@dotfiles_id](https://t.me/dotfiles_id)
  * [R/unixporn](https://www.reddit.com/r/unixporn)

* **Message**
  * Nothing Important You Can Use/Copy/Give Issue/Feedback or whatever you want. This open source so... Up to you all. because some of the codes I got from people who are already proficient

<h3><b><p align="center">- - - T H A N K S - F O R - V I S I T I N G - - -</p></b></h3>
