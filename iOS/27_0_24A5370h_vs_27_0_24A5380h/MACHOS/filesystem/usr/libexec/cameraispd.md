## cameraispd

> `/usr/libexec/cameraispd`

### Section Size Changes

| Section | Old | New | Δ |
| :-- | --: | --: | --: |
| `__DATA_CONST.__const` | `0x92a8` | `0x9a28` | **`+0x780`** |
| `__TEXT.__text` | `0x7c5e8` | `0x7cb80` | **`+0x598`** |
| `__TEXT.__cstring` | `0x75df` | `0x7754` | **`+0x175`** |
| `__DATA_CONST.__cfstring` | `0x2a60` | `0x2bc0` | **`+0x160`** |
| `__TEXT.__oslogstring` | `0x5ecb` | `0x5f4b` | **`+0x80`** |
| `__TEXT.__auth_stubs` | `0x1ee0` | `0x1f20` | **`+0x40`** |
| `__TEXT.__objc_methtype` | `0x1034` | `0x1067` | **`+0x33`** |
| `__DATA_CONST.__auth_got` | `0xf80` | `0xfa0` | **`+0x20`** |
| `__DATA_CONST.__got` | `0xc80` | `0xc90` | **`+0x10`** |
| `__TEXT.__const` | `0x2c08` | `0x2c18` | **`+0x10`** |
| `__TEXT.__unwind_info` | `0x1238` | `0x1248` | **`+0x10`** |
| `__DATA.__bss` | `0x80` | `0x8c` | **`+0xc`** |

### Same-size Content Changes

- `__DATA.__data`
- `__DATA.__objc_const`
- `__DATA.__objc_data`
- `__DATA.__objc_selrefs`
- `__DATA_CONST.__auth_ptr`
- `__DATA_CONST.__objc_arraydata`
- `__DATA_CONST.__objc_arrayobj`
- `__DATA_CONST.__objc_intobj`
- `__TEXT.__gcc_except_tab`
- `__TEXT.__objc_methlist`

### Other Changes

```diff

-20.50.6.0.0
+20.55.3.0.0

-  Functions: 1550
-  Symbols:   911
-  CStrings:  1829
+  Functions: 1556
+  Symbols:   917
+  CStrings:  1840
Symbols:
+ _AMFDRSealingMapCopyLocalData
+ _CFPreferencesGetAppBooleanValue
+ _kFigCaptureStreamMetadata_AH
+ _kFigCaptureStreamMetadata_IREnabled
+ _unlink
+ _xpc_connection_copy_entitlement_value
CStrings:
+ "%s: Failed to create file \"%s\" because of permissions. Deleting it (in case it exists) and trying again"
+ "%s: Failed to create file %s: %s"
+ "/usr/local/share/firmware/isp/dcs_isp_fw.bin"
+ "20.55.3"
+ "<UNKNOWN>"
+ "@36@0:8^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II^{__CFDictionary}{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}16I24^{ISPServicesRemote=@@^?^v*}28"
+ "Audit: XPC peer missing %{public}s (pid %{private}d) — would reject\n"
+ "B24@0:8^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II^{__CFDictionary}{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}16"
+ "EnforceClientEntitlement"
+ "ISPServicesRemoteFDRCalDataKey"
+ "PRF1: %s-%s: Unexpected references size (Expected %ld, Got %d)\n"
+ "PRF1: %s-%s: Unexpected references size after compression (Expected %ld, Got %ld)\n"
+ "PRF1: %s-%s: Unknown format %d"
+ "PRF1: Couldn't create reference file %s to write\n"
+ "PRF1: Failed to save plist %@\n"
+ "Rejecting XPC peer missing %{public}s (pid %{private}d)\n"
+ "^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II^{__CFDictionary}{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}"
+ "com.apple.private.cameraispd.client"
+ "fopen_protected"
- "20.50.6"
- "@36@0:8^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}16I24^{ISPServicesRemote=@@^?^v*}28"
- "B24@0:8^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}16"
- "Couldn't create reference file %s to write\n"
- "Failed to save plist"
- "Unexpected references size (Expected %ld, Got %d)\n"
- "Unexpected references size after compression (Expected %ld, Got %ld)\n"
- "^{ISPDevice={ISPDeviceCachedConfigs=IB{sCIspCmdConfigGet=ISSIIIII}^{ISPDeviceCachedConfigChannel}^{ISPModuleParams}}^?^v^{ISPDeviceController}I^{__CFDictionary}I^{ISPMotionManager}^{ISPDeviceImpactManager}^{ISPServicesRemote}^{ISPExclaveDebugService}^{SystemStatus}I[4096c]{?=[8I]}^{ISPFirmwareWorkProcessor}BBII^{ISPPlatformInfoStruct}i^v^{__CFRunLoopSource}III{_opaque_pthread_mutex_t=q[56c]}B[7{ISPNotification=*Bi}][7{ISPNotification=*Bi}]{ISPNotification=*Bi}{ISPNotification=*Bi}{ISPNotification=*Bi}II{DCSAudioAccelClientConfigStruct=Q@?^?@?^?}^{DCSAudioAccelManager}}"
```
