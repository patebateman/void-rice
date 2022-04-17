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
