Tegra baseline test results for v3.17-rc1


Here are some basic Tegra test results for Linux v3.17-rc1.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v3.17-rc1/20140916142710/


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
Branch: test_v3.17-rc1
Test-Serial: 20140916142710
Commit-ID: 7d1311b93e58ed55f3a31cc8f94c4b8fe988a2b9
Test-Target-Board-Count: 3
Test-Boot-Count: 6
