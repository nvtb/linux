Tegra baseline test results for v4.3-rc5


Here are some basic Tegra test results for Linux v4.3-rc5.
Logs and other details at:

    https://nvtb.github.io//linux/test_v4.3-rc5/20151011113102/


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
Branch: test_v4.3-rc5
Test-Serial: 20151011113102
Commit-ID: 25cb62b76430a91cc6195f902e61c2cb84ade622
Test-Target-Board-Count: 5
Test-Boot-Count: 9
