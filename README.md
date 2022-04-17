# void-rice

mad-ara's void rice (https://github.com/mad-ara/void-rice) edited to my liking.
`git clone https://github.com/0x0f0f0f/void-rice`
`cd void-rice`
```sh
cd void-rice # CD into this repository
sudo ./install-dependencies.sh # Install void packages
./build.sh  # Build
sudo ./install.sh # Install rice
mv ~/.xinitrc ~/.xinitrc.old # Backup old .xinitrc
cp .xinitrc ~/.xinitrc # Apply .xinitrc
```
recoompiling:
```
./build.sh && sudo ./install.sh
```

## Forked Software included in this repo
* [dwm](https://dwm.suckless.org/)
* [st](https://st.suckless.org/)
* [slstatus](https://tools.suckless.org/slstatus/)
* [vpm](https://github.com/bahamas10/vpm)
* [vsv](https://github.com/bahamas10/vsv)
* [dmenu](https://tools.suckless.org/dmenu/)
