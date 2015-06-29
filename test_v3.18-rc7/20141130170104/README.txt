Tegra baseline test results for v3.18-rc7


Here are some basic Tegra test results for Linux v3.18-rc7.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v3.18-rc7/20141130170104/


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
Branch: test_v3.18-rc7
Test-Serial: 20141130170104
Commit-ID: 009d0431c3914de64666bec0d350e54fdd59df6a
Test-Target-Board-Count: 3
Test-Boot-Count: 6
