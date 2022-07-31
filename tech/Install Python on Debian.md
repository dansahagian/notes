# Install Python on Debian

```shell
sudo apt update
sudo apt install wget
sudo apt install build-essential zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev libssl-dev libreadline-dev libffi-dev libsqlite3-dev libbz2-dev

wget https://www.python.org/ftp/python/3.9.3/Python-3.9.3.tgz
tar -xf Python-3.9.3.tgz
cd Python-3.9.3

./configure

make -j 4
sudo make altinstall
```
