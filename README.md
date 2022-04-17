# void-rice

mad-ara's void rice (https://github.com/mad-ara/void-rice) edited to my liking.
```sh
cd void-rice
sudo ./install-dependencies.sh
./build.sh
sudo ./install.sh
mv ~/.xinitrc ~/.xinitrc.old
cp .xinitrc ~/.xinitrc
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
