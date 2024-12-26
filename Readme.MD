# Project info

> Link to Jira board (https://visionnav.atlassian.net/jira/software/c/projects/VIS/boards/1/timeline)

> Link to Google drive (https://drive.google.com/drive/folders/1Nof7Ir2r33FDJ4FhxQjCpKB10esKr0xH)

## Jetson info
> [EN715-R1.0.20.4.6](https://www.avermedia.com/professional/product-detail/EN715#download) - will try to update to latest version

> [Delivery document from ThirdEye](jetsons.pdf) from Yoel Motola (CTO•Third Eye Systems Ltd yoel.motola@gmail.com +972526662075)




## Obsolete - Jetson info
> R28 (release), REVISION: 2.1, GCID: 11272647, BOARD: t186ref, EABI: aarch64, DATE: Thu May 17 07:29:06 UTC 2018 [doc](https://developer.download.nvidia.com/embedded/L4T/r28_Release_v2.1/Tegra_Linux_Driver_Package_Release_Notes_R28.2.1.pdf)

> Elroy Carrier for NVIDIA® Jetson™ TX2/TX2i (https://connecttech.com/product/asg002-elroy-carrier-for-nvidia-jetson-tx2-tx1/)

> Linux tegra-ubuntu 4.4.38-tegra #2 SMP PREEMPT Fri Sep 21 13:58:04 CDT 2018 aarch64 aarch64 aarch64 GNU/Linux

> [Jetson Documentation](AVerMedia_UM_EN715_NO111B_NX211B_TN111B+20240221.pdf)

```
sudo cat /proc/device-tree/nvidia,proc-boardid
3310:0000:C03
sudo cat /proc/device-tree/nvidia,dtsfilename
tegra186-tx2-cti-ASG002-mPCIe.dts
sudo cat /proc/device-tree/nvidia,dtbbuildtime
Jun 26 201814:03:53
sudo cat /proc/device-tree/nvidia,boardids
3310:0000:C03
```
```
nvidia@tegra-ubuntu:~$ sudo cat /etc/nv_boot_control.conf
TEGRA_OTA_BOOT_DEVICE	/dev/mmcblk0boot0
TEGRA_OTA_GPT_DEVICE	/dev/mmcblk0boot1
TNSPEC 3310-B01-fuselevel_production
```

GCID: 11272647 and BOARD: t186ref indicate that the board is part of the NVIDIA Jetson TX2 family.
t186ref specifically refers to the Jetson TX2 platform, as it is based on the Tegra X2 (Parker) SoC.
The date and revision suggest an older L4T version (R28.2.1), which aligns with Jetson TX2 support during that time.

<strong>Board ID 3310 is associated with the Jetson TX2</strong>

### How to connect
```
ssh -X nvidia@81.199.124.218 -p 64222 passwd: nvidia
```




## Software info



