Tegra baseline test results for v3.18-rc6


Here are some basic Tegra test results for Linux v3.18-rc6.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v3.18-rc6/20141123160102/


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
Branch: test_v3.18-rc6
Test-Serial: 20141123160102
Commit-ID: 5d01410fe4d92081f349b013a2e7a95429e4f2c9
Test-Target-Board-Count: 3
Test-Boot-Count: 6
