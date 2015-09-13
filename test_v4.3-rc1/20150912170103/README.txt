Tegra baseline test results for v4.3-rc1


Here are some basic Tegra test results for Linux v4.3-rc1.
Logs and other details at:

    https://nvtb.github.io//linux/test_v4.3-rc1/20150912170103/


Test summary
------------

Build: zImage:
    Pass: ( 2/ 2): multi_v7_defconfig, tegra_defconfig

Build: Image:
    Pass: ( 1/ 1): defconfig

Boot to userspace: defconfig:
    Pass: ( 1/ 1): qemu-vexpress64

Boot to userspace: multi_v7_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver

Boot to userspace: tegra_defconfig:
    Pass: ( 4/ 4): tegra114-dalmore-a04, tegra124-jetson-tk1,
		   tegra20-trimslice, tegra30-beaver



-------------------------------------------------------------
Branch: test_v4.3-rc1
Test-Serial: 20150912170103
Commit-ID: 6ff33f3902c3b1c5d0db6b1e2c70b6d76fba357f
Test-Target-Board-Count: 5
Test-Boot-Count: 9
