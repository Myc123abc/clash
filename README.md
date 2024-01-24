```
mkdir ~/.config/
mkdir ~/.config/mihomo/
cd ~/.config/mihomo/
```
download clash.tar.gz
```
tar xvf clash.tar.gz
chmod +x clash

wget -U "Mozilla/6.0" -O ~/.config/mihomo/config.yaml  Your Clash subscription link URL

./clash
```
firefox proxy
```
127.0.0.1 7890
127.0.0.1 7890
127.0.0.1 7890
localhost, 127.0.0.0/8, ::1
```
terminal proxy
add to .bashrc
```
export http_proxy="http://127.0.0.1:7890"
export https_proxy="http://127.0.0.1:7890"
```
unset proxy
```
unset http_proxy
unset https_proxy
```
