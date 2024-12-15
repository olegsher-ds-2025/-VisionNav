# Project info

> Link to Jira board (https://visionnav.atlassian.net/jira/software/c/projects/VIS/boards/1/timeline)

> Link to Google drive (https://drive.google.com/drive/folders/1Nof7Ir2r33FDJ4FhxQjCpKB10esKr0xH)

## Jetson info
> R28 (release), REVISION: 2.1, GCID: 11272647, BOARD: t186ref, EABI: aarch64, DATE: Thu May 17 07:29:06 UTC 2018

> Elroy Carrier for NVIDIA® Jetson™ TX2/TX2i (https://connecttech.com/product/asg002-elroy-carrier-for-nvidia-jetson-tx2-tx1/)

> Linux tegra-ubuntu 4.4.38-tegra #2 SMP PREEMPT Fri Sep 21 13:58:04 CDT 2018 aarch64 aarch64 aarch64 GNU/Linux
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

<strong>Board ID 3310 is associated with the Jetson TX2</strong>

### How to connect
```
ssh -X nvidia@81.199.124.218 -p 64222 passwd: nvidia
```




## Software info



