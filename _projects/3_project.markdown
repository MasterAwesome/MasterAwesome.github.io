---
layout: page
title: android_device_oneplus_onyx
description: Android 7 for Moto G.
img: https://vectorlogoseek.com/wp-content/uploads/2020/07/lineageos-vector-logo.png
importance: 3
category: fun
---

[<i class="fab fa-github"></i> device tree](https://github.com/MasterAwesome/android_device_oneplus_onyx)\
[<i class="fab fa-github"></i> kernel tree](https://github.com/MasterAwesome/android_kernel_oneplus_msm8974)\
[<i class="fab fa-github"></i> vendor tree](https://github.com/MasterAwesome/android_vendor_oneplus_onyx)

Author of the 3 repositories above to get lineageos support on Oneplus X `onyx`

<center>
<img src="https://fdn2.gsmarena.com/vv/pics/oneplus/oneplus-x-3.jpg" alt="Xiaomi Mi A3" title="Xiaomi Mi A3" data-canonical-src="https://fdn2.gsmarena.com/vv/pics/oneplus/oneplus-x-3.jpg" style="max-width: 100%;">
</center>
<p>
&nbsp;
</p>

The OnePlus X (codenamed _"onyx"_) is a mid-range smartphone from OnePlus.
It was announced on Oct 2015..


Basic   | Spec Sheet
-------|-------------------------:
CPU     | Quad-core 2.3 GHz Krait 400
CHIPSET | Qualcomm Snapdragon 801
GPU     | Adreno 330
Memory  | 3GB RAM
Shipped Android Version | 5.1.1 Oxygen OS
Storage | 16GB
MicroSD | Up to 128 GB (uses SIM 2 slot)
Battery | 2525 mAh
Dimensions | 5.51 x 2.72 x 0.27 in
Camera  | 13 MP, f/2.2, phase detection autofocus, LED flash

<p>
&nbsp;
</p>

## Device manifest
```xml
<manifest>
  <project name="MasterAwesome/android_device_oneplus_onyx" path="device/oneplus/onyx" remote="github" revision="master"/>
  <project name="CyanogenMod/android_device_oppo_common" path="device/oppo/common" remote="github" />
  <project name="MasterAwesome/android_kernel_oneplus_msm8974" path="kernel/oneplus/msm8974" remote="github" revision="5.1.1" />
  <project name="MasterAwesome/android_vendor_oneplus_onyx" path="vendor/oneplus/onyx" remote="github" revision="master" />
</manifest>
```
