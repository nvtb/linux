Tegra baseline test results for v4.0-rc2


Here are some basic Tegra test results for Linux v4.0-rc2.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v4.0-rc2/20150304011913/


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
Branch: test_v4.0-rc2
Test-Serial: 20150304011913
Commit-ID: 13a7a6ac0a11197edcd0f756a035f472b42cdf8b
Test-Target-Board-Count: 4
Test-Boot-Count: 7
