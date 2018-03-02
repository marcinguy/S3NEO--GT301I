# S3NEO--GT301I


Follwong LinageOS instructions.

Than create file:

<REPO>/.repo/local_manifests/roomservice.xml
  
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
  <project name="S3NEO/android_device_samsung_s3ve3g" path="device/samsung/s3ve3g" remote="github" revision="lineage-14.1" />
  <project name="S3NEO/android_kernel_samsung_s3ve3g" path="kernel/samsung/s3ve3g" remote="github" revision="lineage-14.1" />
  <project name="LineageOS/android_device_qcom_common" path="device/qcom/common" remote="github" revision="cm-14.1" />
  <project name="LineageOS/android_device_samsung_qcom-common" path="device/samsung/qcom-common" remote="github" revision="cm-14.1" />
  <project name="LineageOS/android_external_stlport" path="external/stlport" remote="github" revision="cm-14.1" />
  <project name="LineageOS/android_external_sony_boringssl-compat" path="external/sony/boringssl-compat" remote="github" revision="cm-14.1" />
  <project name="LineageOS/android_hardware_samsung" path="hardware/samsung" remote="github" revision="cm-14.1" />
  <project name="S3NEO/android_vendor_samsung_s3ve3g_samsung" path="vendor/samsung/s3ve3g" remote="github" revision="lineage-14.1" />
  <project name="LineageOS/android_packages_resources_devicesettings" path="packages/resources/devicesettings" remote="github" revision="cm-14.1" />
  <project name="LineageOS/android_device_samsung_msm8226-common" path="device/samsung/msm8226-common" remote="github" />
</manifest>

Than run 

repo sync

Clone manually

https://github.com/marcinguy/android_device_samsung_msm8226-common

and put it in:

device/samsungs/msm8226-common

You are all set.

Good luck!
