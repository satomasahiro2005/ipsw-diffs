## cameraispd

> `/usr/libexec/cameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA.__data` | `0x572350` | `0x5ad350` | **`+0x3b000`** |
| `__TEXT.__text` | `0x7f084` | `0x7f3e4` | **`+0x360`** |
| `__TEXT.__cstring` | `0x7e62` | `0x7f0f` | **`+0xad`** |
| `__DATA_CONST.__cfstring` | `0x3040` | `0x3080` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x1073` | `0x10af` | **`+0x3c`** |
| `__TEXT.__oslogstring` | `0x60c1` | `0x60ed` | **`+0x2c`** |
| `__TEXT.__unwind_info` | `0x12c8` | `0x12d0` | **`+0x8`** |
| `__TEXT.__gcc_except_tab` | `0x1a2c` | `0x1a28` | **`-0x4`** |

### Same-size Content Changes

- `__DATA.__objc_const`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__const`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__DATA_CONST.__objc_protolist`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-20.105.6.0.0
+20.106.4.0.0

-  Functions: 1587
+  Functions: 1591

-  CStrings:  1935
+  CStrings:  1944
CStrings:
+ "%s - Error reading kernel config cache - chan: %d, res: 0x%08X\n"
+ "%s - channel configs not valid - exiting\n"
+ "%s - kernel config count %d != firmware %d - chan: %d\n"
+ "/usr/local/share/firmware/isp/2027_01XX.dat"
+ "/usr/local/share/firmware/isp/2327_01XX.dat"
+ "/usr/local/share/firmware/isp/2327_02XX.dat"
+ "20.106.4"
+ "@36@0:8^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II{os_unfair_lock_s=I}^?^v^{__CFDictionary}[7B]{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}16I24^{ISPServicesRemote=@@^?^v*}28"
+ "B24@0:8^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II{os_unfair_lock_s=I}^?^v^{__CFDictionary}[7B]{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}16"
+ "CacheChannelConfigs"
+ "Could not find %s as %s (errno: %d)"
+ "Found %s at %s."
+ "Will use ISP references"
+ "Will use SEP references"
+ "^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II{os_unfair_lock_s=I}^?^v^{__CFDictionary}[7B]{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}"
+ "sparse reference plist"
+ "sparseLP reference plist"
- "%s - Error getting LSC polynomial - chan: %d, res: 0x%08X\n"
- "%s - Error getting camera config - chan: %d, res: 0x%08X\n"
- "20.105.6"
- "@36@0:8^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II^{__CFDictionary}[7B]{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}16I24^{ISPServicesRemote=@@^?^v*}28"
- "B24@0:8^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II^{__CFDictionary}[7B]{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}16"
- "Could not find reference plist at %s (errno: %d). Will use ISP references"
- "Found reference plist at %s. Will use SEP references"
- "^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II^{__CFDictionary}[7B]{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}"
```
