Tegra baseline test results for v3.18-rc3


Here are some basic Tegra test results for Linux v3.18-rc3.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v3.18-rc3/20141102153105/


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
Branch: test_v3.18-rc3
Test-Serial: 20141102153105
Commit-ID: 0df1f2487d2f0d04703f142813d53615d62a1da4
Test-Target-Board-Count: 3
Test-Boot-Count: 6
