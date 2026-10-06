## cameraispd

> `/usr/libexec/cameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x3be2c0` | `0x572350` | **`+0x1b4090`** |
| `__TEXT.__text` | `0x7e754` | `0x7f080` | **`+0x92c`** |
| `__TEXT.__cstring` | `0x7c85` | `0x7e7c` | **`+0x1f7`** |
| `__TEXT.__oslogstring` | `0x5fd3` | `0x60c1` | **`+0xee`** |
| `__DATA_CONST.__const` | `0x9ac0` | `0x9ae0` | **`+0x20`** |
| `__TEXT.__const` | `0x2c18` | `0x2c08` | **`-0x10`** |
| `__TEXT.__objc_methtype` | `0x1067` | `0x1073` | **`+0xc`** |
| `__TEXT.__unwind_info` | `0x12c0` | `0x12c8` | **`+0x8`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__cfstring`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-20.77.1.0.0
+20.104.4.0.0

-  Functions: 1578
+  Functions: 1587

-  CStrings:  1916
+  CStrings:  1936
CStrings:
+ "%s - ABDNet: frame %d, id %d \n"
+ "/usr/local/share/firmware/isp/2727_01XX.dat"
+ "/usr/local/share/firmware/isp/3527_02XX.dat"
+ "/usr/local/share/firmware/isp/3527_03XX.dat"
+ "/usr/local/share/firmware/isp/4227_01XX.dat"
+ "/usr/local/share/firmware/isp/4427_01XX.dat"
+ "/usr/local/share/firmware/isp/7127_02XX.dat"
+ "/usr/local/share/firmware/isp/7327_01XX.dat"
+ "/usr/local/share/firmware/isp/7327_02XX.dat"
+ "20.104.4"
+ "@36@0:8^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II^{__CFDictionary}[7B]{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}16I24^{ISPServicesRemote=@@^?^v*}28"
+ "AH_angle_camPort"
+ "AH_angle_delta"
+ "AH_angle_max"
+ "AH_angle_min"
+ "AH_angle_sessionDuration"
+ "AH_angle_start"
+ "AH_angle_stop"
+ "B24@0:8^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II^{__CFDictionary}[7B]{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}16"
+ "Failed to report the ISP Hinge Angle metrics to analyticsd: %08X\n\n"
+ "Unexpected client Get data length=%zu expected=%zu (pid %{private}d)\n"
+ "Unexpected client Set data length=%zu expected=%zu (pid %{private}d)\n"
+ "^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II^{__CFDictionary}[7B]{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}"
+ "com.apple.applecamerad.AHAngleMetrics"
- "20.77.1"
- "@36@0:8^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II^{__CFDictionary}{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}16I24^{ISPServicesRemote=@@^?^v*}28"
- "B24@0:8^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II^{__CFDictionary}{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}16"
- "^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II^{__CFDictionary}{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}"
```
