# void-rice
![screenshot](https://github.com/patebateman/void-rice/blob/master/screenshot.png?raw=true)
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
