Tegra baseline test results for v3.17-rc2


Here are some basic Tegra test results for Linux v3.17-rc2.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v3.17-rc2/20140916145434/


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
Branch: test_v3.17-rc2
Test-Serial: 20140916145434
Commit-ID: 52addcf9d6669fa439387610bc65c92fa0980cef
Test-Target-Board-Count: 3
Test-Boot-Count: 6
