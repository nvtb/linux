Tegra baseline test results for v3.19-rc4


Here are some basic Tegra test results for Linux v3.19-rc4.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v3.19-rc4/20150111130104/


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
Branch: test_v3.19-rc4
Test-Serial: 20150111130104
Commit-ID: eaa27f34e91a14cdceed26ed6c6793ec1d186115
Test-Target-Board-Count: 3
Test-Boot-Count: 6
