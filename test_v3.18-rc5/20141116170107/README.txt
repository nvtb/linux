Tegra baseline test results for v3.18-rc5


Here are some basic Tegra test results for Linux v3.18-rc5.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v3.18-rc5/20141116170107/


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
Branch: test_v3.18-rc5
Test-Serial: 20141116170107
Commit-ID: fc14f9c1272f62c3e8d01300f52467c0d9af50f9
Test-Target-Board-Count: 3
Test-Boot-Count: 6
