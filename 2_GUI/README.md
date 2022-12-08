Ok.. So let's go:
If you don't have an ethernet connection, [use nmcli](https://wiki.archlinux.org/title/NetworkManager#nmcli_examples) -- (Yeah, I know this is from Arch Guide)
```bash
# List all available networks
nmcli device wifi list
# Connect to your network
nmcli device wifi connect YOUR_SSID password YOUR_PASSWORD
```

And install some required packages,
```bash
sudo apt-get install kitty i3 git build-essential feh fish bat exa xsel xclip maim firefox-esr rofi
```

I have some configs for VIM and Neovim in case you are interested, but if you do't like AppImage, flatpak, Snap, or install from sources, I would recommend you to use VIM with Debian, because Neovim package is outdated and my configs won't work.
```bash
sudo apt install vim
```
PS: If you choose Neovim, you will have to change config.fish in order to work correctly...

Now, clone my repo:
```bash
cd mkdir Documents
cd Documents
git clone https://github.com/pzeadrian/debian
cd debian
```

And copy my configs to your .config folder by running my script
```bash
<Insert Script :)>
```

Change shell to /usr/bin/fish
```bash
chsh
```

And, 
```bash
sudo reboot
```

That's all here..