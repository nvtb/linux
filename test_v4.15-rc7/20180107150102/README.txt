Tegra baseline test results for v4.15-rc7


Here are some basic Tegra test results for Linux v4.15-rc7.
Logs and other details at:

    https://nvtb.github.io//linux/test_v4.15-rc7/20180107150102/


Test summary
------------

Build: zImage:
    Pass: ( 3/ 3): multi_v7_defconfig, tegra_defconfig,
		   tegra_defconfig%tegra-fw

Build: Image:
    Pass: ( 3/ 3): defconfig, defconfig%jetson-tx2,
		   defconfig%jetson-tx1

Boot to userspace: defconfig:
    Pass: ( 4/ 4): qemu-vexpress64, tegra132-norrin,
		   tegra210-p2371-0000, tegra210-smaug

Boot to userspace: defconfig%jetson-tx1:
    Pass: ( 2/ 2): tegra210-p2371-0000, tegra210-p2371-2180

Boot to userspace: defconfig%jetson-tx2:
    Pass: ( 1/ 1): tegra186-p2771-0000

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 1/ 5): tegra124-nyan-big
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    FAIL: ( 1/ 5): tegra124-nyan-big
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig%tegra-fw:
    FAIL: ( 1/ 2): tegra124-nyan-big
    Pass: ( 1/ 2): tegra124-jetson-tk1

PM: System suspend: multi_v7_defconfig:
    FAIL: ( 1/ 5): tegra124-nyan-big
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig:
    FAIL: ( 1/ 5): tegra124-nyan-big
    Pass: ( 4/ 5): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

PM: System suspend: tegra_defconfig%tegra-fw:
    FAIL: ( 1/ 2): tegra124-nyan-big
    Pass: ( 1/ 2): tegra124-jetson-tk1


-------------------------------------------------------------
Branch: test_v4.15-rc7
Test-Serial: 20180107150102
Commit-ID: b2cd1df66037e7c4697c7e40496bf7e4a5e16a2d
Test-Target-Board-Count: 9
Test-Boot-Count: 14
