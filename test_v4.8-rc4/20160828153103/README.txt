Tegra baseline test results for v4.8-rc4


Here are some basic Tegra test results for Linux v4.8-rc4.
Logs and other details at:

    https://nvtb.github.io//linux/test_v4.8-rc4/20160828153103/


Test summary
------------

Build: zImage:
    FAIL: ( 1/ 2): multi_v7_defconfig
    Pass: ( 1/ 2): tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 4/ 4): qemu-vexpress64, tegra132-norrin,
		   tegra210-p2371-0000, tegra210-smaug

Boot to userspace: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    Pass: ( 5/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra124-nyan-big, tegra20-trimslice, tegra30-beaver


-------------------------------------------------------------
Branch: test_v4.8-rc4
Test-Serial: 20160828153103
Commit-ID: 3eab887a55424fc2c27553b7bfe32330df83f7b8
Test-Target-Board-Count: 9
Test-Boot-Count: 14
