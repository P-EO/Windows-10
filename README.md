# Windows 8 Transformation Theme for RaspiOSMake Raspberry Pi OS look as close to Windows 8 as possible.[Download Windows 10 for free](https://dw.uptodown.com/dwn/QUdv6naN6XSz-BTNBv1U7PjToknerMmh-l4mc1WdG564SioD6mMWJOZ30K0o4zvzyQz6PmkZ431LrCGMw8hXy4DXgwP-5Mgz4R0Guy_9C6r7RhLyc7T7wcXCDFdKQw7C/wWnYZ_ooIbQ5Uq-bB3jMyNVjP98Ert8eF9c3Eb6k0pUPUJA4txPQehTTXh87AfD5zT38jEIDqOCpstMeW3KFzAkck_NZPK1lzeWFlH-L8DnE71u8tL1z_Q-F2dobG_Z6/NB5WiSrgkZFEWMiaK029uCaqG5-_IHtQNFPJP-_NyLaKCwuLE0V7VVjWt6vXB2a438p-utg6yzxQGVHBGyM_o6XG-Rq943fxBK6Q9JjKJSo=/)
Installs an icon theme, GTK theme, mouse cursor, openbox theme, xcompmgr, and custom panel.
/home/pi/Windows-8/install
![images (1)](https://user-images.githubusercontent.com/87420016/127193723-2d390e0c-0864-4d7d-bc3a-dd91ffa404a2.jpeg)
](https://github.com/P-EO/pi-store)

To download:

    git clone https://github.com/P-EO/Windows-8
    
To install:
    
    /home/pi/Windows-8/install

To uninstall:

    /home/pi/Windows-8/uninstall
    sudo apt purge xcompmgr gtk2-engines-murrine tint2 -y
**Thanks to François for featuring this Windows 8 theme in [his blog](https://www.framboise314.fr/raspberry-pi-os-avec-un-look-de-windows-8/)!**
## Credit:
- The icon theme is originally from [the B00merang project](https://github.com/B00merang-Artwork/Windows-10). Customizations were added by [the TwisterOS team](https://twisteros.com/). Botspot further customized the icon theme to be compatible with Raspbian.
- The GTK theme is based on [the B00merang project](https://github.com/B00merang-Project/Windows-10). Botspot heavily modified it to work best with Raspbian.
- The mouse cursor theme is non-modified Windows 8.1 mouse cursor theme, gotten from [here](https://www.gnome-look.org/p/1084938/).
- The openbox theme was designed from scratch by Botspot.
- Xcompmgr adds transparency and shadows to windows. Non-modified.
- The 'custom panel' is actually two panels, one over the other. The lower one is `lxpanel`, and Botspot designed the entire theme from scratch. The upper one is `tint2`, and Botspot designed all the taskbar elements from scratch. This double-panel approach is necessary to  better mimic Windows 8. No other Windows 8 theme for any Linux OS is as realistic as this theme.
