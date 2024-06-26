# Integrirovon dasturlash muhitni o'rnatish

<!--toc:start-->

- [Integrirovon dasturlash muhitni o'rnatish](#integrirovon-dasturlash-muhitni-ornatish)
  - [Python uchun IDE-lar](#python-uchun-ide-lar)
  - [IDE-ni tortish](#ide-ni-tortish)
    - [VSCodium/Code](#vscodiumcode)
      - [Windows va MacOS (VSCode)](#windows-va-macos-vscode)
      - [Windows (VSCodium)](#windows-vscodium)
      - [MacOS (VSCodium)](#macos-vscodium)
      - [Linux](#linux)
        - [:simple-materialformkdocs: Linux-ga hali ishlar olib-borilmoqda :material-alert:](#simple-materialformkdocs-linux-ga-hali-ishlar-olib-borilmoqda-material-alert)
  - [IDE-ni ornatish](#ide-ni-ornatish)
    - [VSCode](#vscode)
      - [Windows](#windows)
      - [MacOS](#macos)
      - [Linux](#linux)
    - [VSCodium](#vscodium)
      - [Windows](#windows)
      - [MacOS](#macos)
      - [Linux](#linux)
        - [:simple-materialformkdocs: Linux-ga hali ishlar olib-borilmoqda :material-alert:](#simple-materialformkdocs-linux-ga-hali-ishlar-olib-borilmoqda-material-alert)
        - [Arch Linux](#arch-linux)
        - [Debian](#debian)
  - [Post-Install](#post-install)
  <!--toc:end-->

IDE (ingiliz tilidan) yoki IDM bu Integrirovon dasturlash muhiti bolib

Bu sizga dasturlashda yordam beradigan maxsus programma boladi

## Python uchun IDE-lar

- Visual Studio Codium/Code
  Ingiliz tilini biladiganlar uchun:
- PyCharm Community Edition\*
- Thonny\*
- Spyder\*

\* - bu kursga hali qoshilmagan

## IDE-ni tortish

### VSCodium/Code

???+ info "Windows foydanalovchilar:"
Bu huddi oddiy programmani ornatish dek

#### Windows va MacOS (VSCode)

!!! note "Tortib olish"
![VSCode downloading](../assets/images/vscode-download.png)
O'rnatovchini tortib olish uchun: [Visual Studio Code](https://code.visualstudio.com)

#### Windows (VSCodium)

!!! note "Windows"

<h3> 1. ![VSCodium Downloading](../assets/images/vscodium-download.png)

    2. ![VSCodium Github Releases Show all](../assets/images/vscodium-github-download.png)

    3. ++ctrl+f++ va "msi" deb yozing

    4. ![VSCodium Github Releases FINAL Download](../assets/images/vscodium-github-download-2.png)
    </h3>

#### MacOS (VSCodium)

!!! note "MacOS"

<h3> 1. ![VSCodium Downloading](../assets/images/vscodium-download.png)

    2. ![VSCodium Github Releases Show all](../assets/images/vscodium-github-download.png)

    3. ++control+f++ va "dmg" deb yozing

    4. ![VSCodium Github Releases FINAL Download](../assets/images/vscodium-github-download-macos.png)
    </h3>

#### Linux

##### :simple-materialformkdocs: Linux-ga hali ishlar olib-borilmoqda :material-alert:

## IDE-ni ornatish

### VSCode

#### Windows

!!! warning ""
O'rnatishda to'liq rasmlar yoq
!!! info ""

<h3> 1. ![VSCode License Agreement - Agree](../assets/images/vscode-license-agree.png)

    2. ++enter++-ni 2 matta bosing

    3. ![VSCode installation](../assets/images/vscode-installation-preview.png)

    4. ![VSCode END](../assets/images/vscode-install-complete.png)
    </h3>

#### MacOS

!!! warning "Rasmlar yoq chunki kurs faqat Windows noutbukida yaratilgan."
!!! info ""

<h3> 1. DMG-ni oching<br> 2. Visual Studio Code-ni Applications papkasiga otkazing
</h3>

#### Linux

!!! info "Debian"
Debian Distributivi uchun
`bash
    sudo apt install code
    `
!!! info "Arch Linux"
Arch-Linux Distributivi uchun
`bash
    sudo pacman -S code
    `
!!! info "Fedora Linux"
Fedora Distributivi uchun
`bash
    sudo dnf install code
    ` > Needs confirmation

### VSCodium

#### Windows

!!! info "" 1. ![VSCodium License Agreement and install](../assets/images/vscodium-license-agreement-and-install.png)

    2. **O'rnatilish tugagandan so'ng o'rnatuvchini yopsangiz boladi.**

#### MacOS

!!! info ""
MacOS-da esa huddi manashu [paragrafdagideg](#macos) o'rnatsangiz boladi lekin bu yerda rasimlar yoq!

#### Linux

##### :simple-materialformkdocs: Linux-ga hali ishlar olib-borilmoqda :material-alert:

VSCodium-ni o'rnatish uchun siz linux Distributivingizni bilishingiz kerak
buni `#!bash neofetch` kommanda bilan boladi lekin bunga siz ingiliz tilini bilishingiz kerak boladi!

```bash
neofetch
```

Terminal-ni ochib bu kommandani yo'zing

##### Arch Linux

```bash
sudo pacman -S vscodium
```

##### Debian

!!! info "WIP"

## Post-Install

!!! info ""

<h3> 1. ![Post Install](../assets/images/vscode-post-install-1.png)

    2. ![Post Install step 2](../assets/images/python-extenstion-install.png)
    </h3>

Va siz muvaffaqiyatli IDE-ni o'rnattingiz va sozladingiz!

