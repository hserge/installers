# installers
Generic shell scripts to install apps on linux

Scripts can be run remotly one of these ways:
```sh
bash <(curl -s http://mywebsite.com/myscript.txt)
bash <(wget -qO- http://mywebsite.com/myscript.txt)
curl -s http://server/path/script.sh | bash /dev/stdin arg1 arg2
```
