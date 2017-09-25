Tegra baseline test results for v4.14-rc2


Here are some basic Tegra test results for Linux v4.14-rc2.
Logs and other details at:

    https://nvtb.github.io//linux/test_v4.14-rc2/20170924170104/


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
Branch: test_v4.14-rc2
Test-Serial: 20170924170104
Commit-ID: e19b205be43d11bff638cad4487008c48d21c103
Test-Target-Board-Count: 9
Test-Boot-Count: 14
