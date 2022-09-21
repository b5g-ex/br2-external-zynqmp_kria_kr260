# br2-external-zynqmp_kria_kr260

This is a br2-external for [KR260](https://japan.xilinx.com/products/som/kria/kr260-robotics-starter-kit.html).

## How to use

### create buildroot linux

```
$ cd your/working/dir
$ git clone https://github.com/buildroot/buildroot.git
$ cd buildroot
$ git checkout 2022.05.2
$ make BR2_EXTERNAL=/path/to/this-repo zynqmp_kria_kr260_defconfig
$ make
# after build, you can find fw image, output/images/kr260.fw

# if you want to configure zynqmp_kria_kr260_defconfig, invoke below command
$ make menuconfig
```

### burn fw to SD

```
$ sudo fwup output/images/kr260.fw
```

