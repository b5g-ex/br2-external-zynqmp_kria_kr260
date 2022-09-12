# br2-external-zynqmp_kria_kr260

This is a br2-external for [KR260](https://japan.xilinx.com/products/som/kria/kr260-robotics-starter-kit.html).

## How to make

```
$ cd your/working/dir
$ git clone https://github.com/buildroot/buildroot.git
$ cd buildroot
$ git checkout 2022.05.2
$ make BR2_EXTERNAL=/path/to/this-repo zynqmp_kria_kr260_defconfig
$ ...
```

