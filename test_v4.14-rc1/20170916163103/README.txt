Tegra baseline test results for v4.14-rc1


Here are some basic Tegra test results for Linux v4.14-rc1.
Logs and other details at:

    https://nvtb.github.io//linux/test_v4.14-rc1/20170916163103/


Test summary
------------

Build: zImage:
    FAIL: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 4/ 4): qemu-vexpress64, tegra132-norrin,
		   tegra210-p2371-0000, tegra210-smaug



-------------------------------------------------------------
Branch: test_v4.14-rc1
Test-Serial: 20170916163103
Commit-ID: 2bd6bf03f4c1c59381d62c61d03f6cc3fe71f66e
Test-Target-Board-Count: 9
Test-Boot-Count: 14
