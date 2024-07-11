# check-configuaraions-of-jetson-nano-

# old version - check for existing file

`cat /etc/nv_tegra_release`

# later versions (check L4T verions)

`dpkg-query --show nvidia-l4t-core`

`dpkg -l | grep 'nvidia-l4t-core'`

`sudo apt-cache show nvidia-jetpack`

`dpkg -l | grep -i 'jetpack'`

# CUDA version

`nvcc --version`


# install jtop

https://jetsonhacks.com/2023/02/07/jtop-the-ultimate-tool-for-monitoring-nvidia-jetson-devices/
