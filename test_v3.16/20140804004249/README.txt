Tegra baseline test results for v3.16


Here are some basic Tegra test results for Linux v3.16.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v3.16/20140804004249/


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
Branch: test_v3.16
Test-Serial: 20140804004249
Commit-ID: 19583ca584d6f574384e17fe7613dfaeadcdc4a6
Test-Target-Board-Count: 3
Test-Boot-Count: 6
