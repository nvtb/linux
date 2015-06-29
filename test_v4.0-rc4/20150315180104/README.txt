Tegra baseline test results for v4.0-rc4


Here are some basic Tegra test results for Linux v4.0-rc4.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v4.0-rc4/20150315180104/


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
    Pass: ( 3/ 3): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver



-------------------------------------------------------------
Branch: test_v4.0-rc4
Test-Serial: 20150315180104
Commit-ID: 06e5801b8cb3fc057d88cb4dc03c0b64b2744cda
Test-Target-Board-Count: 4
Test-Boot-Count: 7
