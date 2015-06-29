Tegra baseline test results for v3.18


Here are some basic Tegra test results for Linux v3.18.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v3.18/20141208122141/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Boot to userspace: multi_v7_defconfig:
    Pass: ( 3/ 3): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 3/ 3): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra30-beaver



-------------------------------------------------------------
Branch: test_v3.18
Test-Serial: 20141208122141
Commit-ID: b2776bf7149bddd1f4161f14f79520f17fc1d71d
Test-Target-Board-Count: 3
Test-Boot-Count: 6
