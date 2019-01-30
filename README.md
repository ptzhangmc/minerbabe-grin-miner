![image](https://user-images.githubusercontent.com/7948466/51163162-c263d780-18d3-11e9-8d52-96003f7ce9df.png)

# A Grin GPU miner from Minerbabe

Minerbabe is an GPU mining OS base on Linux. Minerbabe supports many digital coins.

Today, Minerbabe releases a new miner to support Grin.

You can use AMD/NVIDIA GPUs with 4G/6G/8G/10G memory to mining Grin now!

The miner is optimized for GPUs with different memory.

The test results on some typical GPU are below:

* Cuckaroo 29

GPU| GPS
---|---
AMD 380 4G|0.21
AMD 550 4G|0.28
AMD 560 4G|0.31
AMD 390 4G|0.38
AMD 470 4G|0.67
AMD 570 4G|0.64
AMD 470D 4G|0.70
AMD 570 4G on ROCm|0.90
AMD 390 8G|1.18
AMD 570 8G|1.30
AMD 570 8G on ROCm|1.50
AMD 480 8G|1.26
AMD 580 8G|1.32
AMD 580 8G on ROCm|1.54
AMD Vega64 8G|2.85
NVIDIA 1050Ti 4G|0.855
NVIDIA 1060 6G|1.95
NVIDIA 1070 8G|2.88
NVIDIA 1080 8G|3.10
NVIDIA 1070Ti 8G|3.24
NVIDIA 1080Ti 11G|5.10

* Cuckatoo 31

GPU| GPS
---|---
AMD 390 8G|0.150
AMD 570 8G|0.161
AMD 570 8G on ROCm|0.174
AMD 480 8G|0.210
AMD 580 8G|0.178
AMD 580 8G on ROCm|0.197
AMD Vega64 8G|0.410
NVIDIA 1070 8G|0.316
NVIDIA 1080 8G|0.339
NVIDIA 1070TI 8G|0.380
NVIDIA 1080Ti 11G|0.551
NVIDIA 2080 8G|0.69
NVIDIA 2080Ti 11G|1.7

ROCm is a new computing driver from AMD. Unfortunately not all of the mining rigs support ROCm.

The miner is being continuously optimized. Install Minerbabe to automatically keep the miner being updated.

Minerbabe dev fee: 3% for Grin; 1% for the other coins.

Download minerbabe image: https://cdn3.minerbabe.com/disk/minerbabe_v4.12en.img.zip

Manage your rigs at: https://en.dashboard.minerbabe.com

Get tutorial and more information at: www.minerbabe.com

Telegram: https://t.me/joinchat/HkFS5xXBWHhA5QE-WfcxDg

Enjoy!

### Release Notes

#### pre release v0.0.6  2019-01-30

1. Based on v0.7.0
2. Add support for AMD Hawaii Arch GPU: RX290 RX390

#### v0.7.0  2019-01-28

1. Add "nocpu" feature for Nvidia gpu.
2. Verify share's difficulty before submit.

#### v0.6.4  2019-01-18

1. Add support for AMD 380 550 560;
2. Reduce the delay rate of shares;

### Minerbabe Screenshot

![image](https://user-images.githubusercontent.com/7948466/51162923-e541bc00-18d2-11e9-9076-2c9bb0305a99.png)




