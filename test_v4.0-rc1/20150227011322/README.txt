Tegra baseline test results for v4.0-rc1


Here are some basic Tegra test results for Linux v4.0-rc1.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v4.0-rc1/20150227011322/


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
Branch: test_v4.0-rc1
Test-Serial: 20150227011322
Commit-ID: c517d838eb7d07bbe9507871fab3931deccff539
Test-Target-Board-Count: 3
Test-Boot-Count: 6
