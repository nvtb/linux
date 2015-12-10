Tegra baseline test results for v4.4-rc1


Here are some basic Tegra test results for Linux v4.4-rc1.
Logs and other details at:

    https://nvtb.github.io//linux/test_v4.4-rc1/20151210043242/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_v4.4-rc1
Test-Serial: 20151210043242
Commit-ID: 8005c49d9aea74d382f474ce11afbbc7d7130bec
Test-Target-Board-Count: 5
Test-Boot-Count: 9
