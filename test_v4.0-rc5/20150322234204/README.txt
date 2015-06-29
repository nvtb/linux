Tegra baseline test results for v4.0-rc5


Here are some basic Tegra test results for Linux v4.0-rc5.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v4.0-rc5/20150322234204/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    Pass: ( 3/ 3): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_v4.0-rc5
Test-Serial: 20150322234204
Commit-ID: bc465aa9d045feb0e13b4a8f32cc33c1943f62d6
Test-Target-Board-Count: 5
Test-Boot-Count: 8
