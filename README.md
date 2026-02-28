> [!CAUTION]
> Only available for Ubuntu or Debian Based distro. Since driver is built on install, you may unpack the file manually and try build on other distro base.<br>**PROVIDED AS IS WITH NO WARRANTY!!! I'M NOT RESPONSIBLE IF YOU INSTALL IT NOT IN THE INTENDED WAY!!!**

### 1. If you are on the linux machine with no internet, temporarily connect via ethernet and download the driver linked below:
https://www.tendacn.com/us/product/help/U11Pro

(Alternatively, I upload the zip file in this repo if somehow Tenda decides to discontinue and remove this download link from their website, u never know ;)

### 2. Before unpack and installing, install the dependency first. This driver is built on install time.
```shell
sudo apt update && sudo apt install make gcc-13 g++-13 build-essential linux-headers-$(uname -r) dkms
```

### 3. Now can unpack and install via apt
```shell
sudo apt install ./driver-file.deb
```
