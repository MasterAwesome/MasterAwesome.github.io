---
layout: page
title: android_device_xiaomi_laurel_sprout
description: Android 11 for laurel_sprout with stock vendor images.
img: https://vectorlogoseek.com/wp-content/uploads/2020/07/lineageos-vector-logo.png
importance: 1
category: fun
---

[<i class="fab fa-github"></i> device tree](https://github.com/MasterAwesome/android_device_xiaomi_laurel_sprout)\
[<i class="fab fa-github"></i> kernel tree](https://github.com/MasterAwesome/android_kernel_xiaomi_laurel_sprout)\
[<i class="fab fa-github"></i> vendor tree](https://github.com/MasterAwesome/android_vendor_xiaomi_laurel_sprout)\
[<i class="fab fa-github"></i> vendor images tree](https://github.com/MasterAwesome/android_vendor_xiaomi_laurel_sprout-images)

Author of the 4 repositories above to get lineageos support on the Android one device `laurel_sprout`

<center>
<img src="https://i01.appmifile.com/webfile/globalimg/products/pc/mi-a3/MIA3_02.jpg" alt="Xiaomi Mi A3" title="Xiaomi Mi A3" data-canonical-src="https://i01.appmifile.com/webfile/globalimg/products/pc/mi-a3/MIA3_02.jpg" style="max-width: 100%;">
</center>

<p>
&nbsp;
</p>

The Xiaomi Mi A3 (codenamed _"laurel_sprout"_) is a entry-level smartphone from Xiaomi.

|Basic   | Spec Sheet|
|-------|----------:|
|CPU     | 8x2GHz Kryo 260|
|Chipset | Qualcomm Snapdragon 665|
|GPU     | Adreno 610|
|ROM     | 64/128 UFS 2.1|
|RAM     | 4GB|
|Android | 9.0|
|Battery | 4030 mAh|
|Display | 720x1560 pixels, 6.0|
|Rear Camera  | 48MP/2MP/8MP|
|Front Camera | 32MP|

<p>
&nbsp;
</p>

## Device manifest

```xml
<?xml version="1.0" encoding="UTF-8"?>

<manifest>
	<!-- DEVICE TREE -->
	<project name="MasterAwesome/android_device_xiaomi_laurel_sprout" path="device/xiaomi/laurel_sprout" remote="github" />

	<!-- VENDOR TREE -->
	<project name="MasterAwesome/android_vendor_xiaomi_laurel_sprout" path="vendor/xiaomi/laurel_sprout" remote="github" />
	<project name="MasterAwesome/android_vendor_xiaomi_laurel_sprout-images" path="vendor/xiaomi/laurel_sprout-images" remote="github" />

	<!-- KERNEL TREE -->
	<project name="MasterAwesome/android_kernel_xiaomi_laurel_sprout" path="kernel/xiaomi/laurel_sprout" remote="github" />
</manifest>
```

## Builds
Builds for this tree is at: [https://gitlab.com/MasterAwesome/laurel_sprout-builds](https://gitlab.com/MasterAwesome/laurel_sprout-builds). Please refer to commit-id to know the latest commit
