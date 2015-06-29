Tegra baseline test results for v3.19-rc1


Here are some basic Tegra test results for Linux v3.19-rc1.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v3.19-rc1/20150108014100/


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
Branch: test_v3.19-rc1
Test-Serial: 20150108014100
Commit-ID: 97bf6af1f928216fd6c5a66e8a57bfa95a659672
Test-Target-Board-Count: 3
Test-Boot-Count: 6
