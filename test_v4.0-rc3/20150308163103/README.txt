Tegra baseline test results for v4.0-rc3


Here are some basic Tegra test results for Linux v4.0-rc3.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v4.0-rc3/20150308163103/


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
Branch: test_v4.0-rc3
Test-Serial: 20150308163103
Commit-ID: 9eccca0843205f87c00404b663188b88eb248051
Test-Target-Board-Count: 4
Test-Boot-Count: 7
