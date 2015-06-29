Tegra baseline test results for v3.18-rc4


Here are some basic Tegra test results for Linux v3.18-rc4.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v3.18-rc4/20141109150105/


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
Branch: test_v3.18-rc4
Test-Serial: 20141109150105
Commit-ID: 206c5f60a3d902bc4b56dab2de3e88de5eb06108
Test-Target-Board-Count: 3
Test-Boot-Count: 6
