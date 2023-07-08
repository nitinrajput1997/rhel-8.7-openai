# rhel-8.7-openai

### DPDK(Data Plane Development Kit)
Download DPDK version 20.05.0
```
wget http://fast.dpdk.org/rel/dpdk-20.05.tar.xz
```

DPDK Compilation
```
tar -xvf dpdk-20.05.tar.xz
cd dpdk-20.05
```

Meson Install
```
sudo dnf update
sudo dnf install python3-devel python3-pip ninja-build
pip3 install meson
sudo dnf install python3-pip
meson --version
```
