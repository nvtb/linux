Tegra baseline test results for v3.16-rc1


Here are some basic Tegra test results for Linux v3.16-rc1.
Logs and other details at:

    http://nvt.pwsan.com/pub/linux/testlogs/test_v3.16-rc1/20140615210102/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Boot to userspace: multi_v7_defconfig:
    FAIL: ( 2/ 2): tegra114-dalmore-a04, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 2/ 2): tegra114-dalmore-a04, tegra30-beaver



-------------------------------------------------------------
Branch: test_v3.16-rc1
Test-Serial: 20140615210102
Commit-ID: 7171511eaec5bf23fb06078f59784a3a0626b38f
Test-Target-Board-Count: 2
Test-Boot-Count: 4
