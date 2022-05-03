Purge Boost 1.65 at your own risk.
```
sudo apt purge libboost-dev
sudo apt purge libboost-all-dev

```

Install Boost 1.74.
```
sudo add-apt-repository ppa:mhier/libboost-latest
sudo apt-get update
sudo apt-get install libboost1.74-dev
```

Install readline8 (assume you already have readline7)
```
sudo ln -s /lib/x86_64-linux-gnu/libreadline.so.7 /lib/x86_64-linux-gnu/libreadline.so.8
```

Install zlib
```
sudo apt install zlib1g-dev
```

Install armadillo
```
sudo apt install libarmadillo-dev
```
